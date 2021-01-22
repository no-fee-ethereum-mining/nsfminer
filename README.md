# nsfminer (no stinkin' fees)

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg)](https://github.com/RichardLitt/standard-readme)
[![Gitter](https://img.shields.io/gitter/room/nwjs/nw.js.svg)][Gitter]

> Ethereum (ethash) miner with OpenCL, CUDA and stratum support

**nsfminer** is an Ethash GPU mining application: with nsfminer you can mine every coin which relies on an Ethash Proof of Work.

This is a direct descendent of the Ethminer project at https://github.com/ethereum-mining/ethminer. Since that project
is largely abandoned and unmanaged this personal version is published with the hope that it may continue to be useful. In the spirit
of open source problem reports and pull requests are welcome.

## Features

* OpenCL mining
* Nvidia CUDA mining
* realistic benchmarking
* stratum mining without proxy
* Automatic devices configuration
* farm failover (getwork + stratum)

## Table of Contents

* [Usage](#usage)
    * [Examples connecting to pools](#examples-connecting-to-pools)
* [Build](#build)
    * [Master branch build status](#master-branchr-buildr-status)
    * [Building from source](#building-from-source)
* [Contribute](#contribute)

## Usage

**nsfminer** is a command line program. This means you launch it either
from a Windows command prompt or Linux console, or create shortcuts to
predefined command lines using a Linux Bash script or Windows batch/cmd file.
For a full list of available command, please run:

```sh
nsfminer --help
```

### Examples connecting to pools

Check our [samples](docs/POOL_EXAMPLES_ETH.md) to see how to connect to different pools.

## Build

### Master branch build status

[![CircleCI](https://circleci.com/gh/no-fee-ethereum-mining/nsfminer.svg?style=svg)](https://circleci.com/gh/no-fee-ethereum-mining/fminer)


## Contribute

[![Gitter](https://img.shields.io/gitter/room/ethereum-mining/ethminer.svg)][Gitter]

To meet the community, ask general questions and chat about the miner join [the ethminer channel on Gitter][Gitter].

All bug reports, pull requests and code reviews are very much welcome.

## License

Licensed under the [GNU General Public License, Version 3](LICENSE).

[Gitter]: https://gitter.im/ethereum-mining/ethminer
