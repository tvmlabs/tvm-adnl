# ADNL

ADNL protocol implementation (UDP & TCP)

## Table of Contents

- [ADNL](#adnl)
  - [Table of Contents](#table-of-contents)
  - [About](#about)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installing](#installing)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)
  - [Tags](#tags)

## About

Implementation of Abstract Datagram Network Layer (ADNL) Protocol in safe Rust. ADNL is a protocol that provides all low level communications between Everscale/Venom blockshain nodes. Depending on scenario, ADNL can operate on top of UDP or TCP protocols.

## Getting Started

### Prerequisites

Rust complier v1.65+.

### Installing

```bash
git clone --recurse-submodules https://github.com/tonlabs/ever-adnl.git
cd ever-adnl
cargo build --release
```

## Usage

This project output is the library which is used as a part of Everscale/Venom node. Also it can be used in standalone tools.

## Contributing

Contribution to the project is expected to be done via pull requests submission.

## License

See the [LICENSE](LICENSE) file for details.

## Tags

`blockchain` `rust` `tvm`
