<!--
parent:
  order: false
-->

<div align="center">
  <h1> Jupiter </h1>
</div>

![banner](docs/jupiter.png)

<div align="center">
  <a href="https://github.com/tharsis/ethermint/releases/latest">
    <img alt="Version" src="https://img.shields.io/github/tag/tharsis/ethermint.svg" />
  </a>
  <a href="https://github.com/tharsis/ethermint/blob/main/LICENSE">
    <img alt="License: Apache-2.0" src="https://img.shields.io/github/license/tharsis/ethermint.svg" />
  </a>
  <a href="https://pkg.go.dev/github.com/tharsis/ethermint">
    <img alt="GoDoc" src="https://godoc.org/github.com/tharsis/ethermint?status.svg" />
  </a>
  <a href="https://goreportcard.com/report/github.com/tharsis/ethermint">
    <img alt="Go report card" src="https://goreportcard.com/badge/github.com/tharsis/ethermint"/>
  </a>
  <a href="https://bestpractices.coreinfrastructure.org/projects/5018">
    <img alt="Lines of code" src="https://img.shields.io/tokei/lines/github/tharsis/ethermint">
  </a>
</div>
<div align="center">
  <a href="https://discord.gg/trje9XuAmy">
    <img alt="Discord" src="https://img.shields.io/discord/809048090249134080.svg" />
  </a>
  <a href="https://github.com/tharsis/ethermint/actions?query=branch%3Amain+workflow%3ALint">
    <img alt="Lint Status" src="https://github.com/tharsis/ethermint/actions/workflows/lint.yml/badge.svg?branch=main" />
  </a>
  <a href="https://codecov.io/gh/tharsis/ethermint">
    <img alt="Code Coverage" src="https://codecov.io/gh/tharsis/ethermint/branch/main/graph/badge.svg" />
  </a>
</div>

Jupiter is a scalable and interoperable Ethereum library, built on Proof-of-Stake with fast-finality using the [Cosmos SDK](https://github.com/cosmos/cosmos-sdk/) which runs on top of [Tendermint Core](https://github.com/tendermint/tendermint) consensus engine. We use the Ethermint version of [Tendermint](https://www.github.com/tharsis/evmos). 

**Note**: Requires [Go 1.17+](https://golang.org/dl/)

## Installation

For prerequisites and detailed build instructions please read the Evmos [Installation](https://evmos.dev/quickstart/installation.html) instructions. Once the dependencies are installed, run:

```bash
make install
```

Or check out the latest [release](https://github.com/tharsis/ethermint/releases).

## Quick Start

To learn how the Ethermint works from a high-level perspective, go to the [Introduction](https://evmos.dev/intro/overview.html) section from the documentation. You can also check the instructions to [Run a Node](https://evmos.dev/quickstart/run_node.html).

For an example on how Ethermint can be used on any Cosmos-SDK chain, please refer to [Evmos](https://www.github.com/tharsis/evmos).

## Community

The following chat channels and forums are a great spot to ask questions about Ethermint:

- [Jupiter Twitter](https://twitter.com/jup_project)
- [Jupiter Discord](https://jup.io/discord)
- [Jupiter Telegram](https://t.me/jupiterproject)

## Contributing

Looking for a good place to start contributing? Check out some [`good first issues`](https://github.com/tharsis/ethermint/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22).

For additional instructions, standards and style guides, please refer to the [Contributing](./CONTRIBUTING.md) document.
