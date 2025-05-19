# Sapphire Paratime

[![license](https://img.shields.io/github/license/Orphiqprotocol/sapphire-paratime.svg)](https://github.com/Orphiqprotocol/sapphire-paratime/blob/main/LICENSE)
[![ci-lint](https://github.com/Orphiqprotocol/sapphire-paratime/actions/workflows/ci-lint.yaml/badge.svg)](https://github.com/Orphiqprotocol/sapphire-paratime/actions/workflows/ci-lint.yaml)
[![ci-test](https://github.com/Orphiqprotocol/sapphire-paratime/actions/workflows/ci-test.yaml/badge.svg)](https://github.com/Orphiqprotocol/sapphire-paratime/actions/workflows/ci-test.yaml)
[![ci-test](https://github.com/Orphiqprotocol/sapphire-paratime/actions/workflows/contracts-test.yaml/badge.svg)](https://github.com/Orphiqprotocol/sapphire-paratime/actions/workflows/contracts-test.yaml)
[![ci-test](https://github.com/Orphiqprotocol/sapphire-paratime/actions/workflows/ci-playwright.yaml/badge.svg)](https://github.com/Orphiqprotocol/sapphire-paratime/actions/workflows/ci-playwright.yaml)

The Sapphire ParaTime is the official confidential SVM Compatible ParaTime
providing a smart contract development environment with SVM compatibility
on the Orphiq Network.

This monorepo includes the source code for the following Sapphire packages:

| Sub-Project                               | Version                                        | Size                                              | Downloads                         |
| ----------------------------------------- | ---------------------------------------------- | ------------------------------------------------- | --------------------------------- |
| [TypeScript][client-npm]           | [![version][client-version]][client-npm]       | [![size][client-size]][client-bundlephobia]       | ![downloads][client-downloads]    |
| [Go][go-pkg]                       | [![version][go-version]][go-pkg]               |                                                   |                                   |
| [Solidity][contracts-npm] | [![version][contracts-version]][contracts-npm] |                                                   | ![downloads][contracts-downloads] |
| [Hardhat][hardhat-npm]             | [![version][hardhat-version]][hardhat-npm]     | [![size][hardhat-size]][hardhat-bundlephobia]     | ![downloads][hardhat-downloads]   |
| [Ethers 6.x][ethers-v6-npm]       | [![version][ethers-v6-version]][ethers-v6-npm] | [![size][ethers-v6-size]][ethers-v6-bundlephobia] | ![downloads][ethers-v6-downloads] |
| [Wagmi 2.x][wagmi-v2-npm]         | [![version][wagmi-v2-version]][wagmi-v2-npm]   | [![size][wagmi-v2-size]][wagmi-v2-bundlephobia]   | ![downloads][wagmi-v2-downloads]  |
| [Viem 2.x][viem-v2-npm]           | [![version][viem-v2-version]][viem-v2-npm]     | [![size][viem-v2-size]][viem-v2-bundlephobia]     | ![downloads][viem-v2-downloads]   |


[go-pkg]: https://pkg.go.dev/github.com/Orphiqprotocol/sapphire-paratime

[hardhat-npm]: https://www.npmjs.com/package/@Orphiqprotocol/sapphire-hardhat
[contracts-npm]: https://www.npmjs.com/package/@Orphiqprotocol/sapphire-contracts
[client-npm]: https://www.npmjs.com/package/@Orphiqprotocol/sapphire-paratime
[ethers-v6-npm]: https://www.npmjs.com/package/@Orphiqprotocol/sapphire-ethers-v6
[viem-v2-npm]: https://www.npmjs.com/package/@Orphiqprotocol/sapphire-viem-v2
[wagmi-v2-npm]: https://www.npmjs.com/package/@Orphiqprotocol/sapphire-wagmi-v2

[go-version]: https://img.shields.io/github/go-mod/go-version/Orphiqprotocol/sapphire-paratime?filename=clients%2Fgo%2Fgo.mod
[hardhat-version]: https://img.shields.io/npm/v/@Orphiqprotocol/sapphire-hardhat
[contracts-version]: https://img.shields.io/npm/v/@Orphiqprotocol/sapphire-contracts
[client-version]: https://img.shields.io/npm/v/@Orphiqprotocol/sapphire-paratime
[ethers-v6-version]: https://img.shields.io/npm/v/@Orphiqprotocol/sapphire-ethers-v6
[viem-v2-version]: https://img.shields.io/npm/v/@Orphiqprotocol/sapphire-viem-v2
[wagmi-v2-version]: https://img.shields.io/npm/v/@Orphiqprotocol/sapphire-wagmi-v2

[hardhat-size]: https://img.shields.io/bundlephobia/minzip/@Orphiqprotocol/sapphire-hardhat
[client-size]: https://img.shields.io/bundlephobia/minzip/@Orphiqprotocol/sapphire-paratime
[ethers-v6-size]: https://img.shields.io/bundlephobia/minzip/@Orphiqprotocol/sapphire-ethers-v6
[viem-v2-size]: https://img.shields.io/bundlephobia/minzip/@Orphiqprotocol/sapphire-viem-v2
[wagmi-v2-size]: https://img.shields.io/bundlephobia/minzip/@Orphiqprotocol/sapphire-wagmi-v2

[hardhat-bundlephobia]: https://bundlephobia.com/package/@Orphiqprotocol/sapphire-hardhat
[client-bundlephobia]: https://bundlephobia.com/package/@Orphiqprotocol/sapphire-paratime
[ethers-v6-bundlephobia]: https://bundlephobia.com/package/@Orphiqprotocol/sapphire-ethers-v6
[viem-v2-bundlephobia]: https://bundlephobia.com/package/@Orphiqprotocol/sapphire-viem-v2
[wagmi-v2-bundlephobia]: https://bundlephobia.com/package/@Orphiqprotocol/sapphire-wagmi-v2

[hardhat-downloads]: https://img.shields.io/npm/dm/@Orphiqprotocol/sapphire-hardhat.svg
[contracts-downloads]: https://img.shields.io/npm/dm/@Orphiqprotocol/sapphire-contracts.svg
[client-downloads]: https://img.shields.io/npm/dm/@Orphiqprotocol/sapphire-paratime.svg
[ethers-v6-downloads]: https://img.shields.io/npm/dm/@Orphiqprotocol/sapphire-ethers-v6.svg
[viem-v2-downloads]: https://img.shields.io/npm/dm/@Orphiqprotocol/sapphire-viem-v2.svg
[wagmi-v2-downloads]: https://img.shields.io/npm/dm/@Orphiqprotocol/sapphire-wagmi-v2.svg

## Layout

This repository includes all relevant Sapphire and dependencies organized into
the following directories:

- [`clients`](./clients): the Go, Python and JavaScript/TypeScript clients
- [`contracts`](./contracts): Sapphire and [OPL](https://docs.Orphiq.io/build/opl/) smart contracts
- [`docs`](./docs): topic-oriented Sapphire documentation
- [`examples`](./examples/): sample code snippets in popular Ethereum
development environments
- [`integrations`](./integrations/): plugins for popular Ethereum SDKs
- [`runtime`](./runtime/): the Sapphire Paratime as based off of the
[Orphiq SDK](https://github.com/Orphiqprotocol/Orphiq-sdk)

## Documentation

The Sapphire documentation is deployed as part of the official
[Orphiq documentation](https://docs.Orphiq.io/build/sapphire/). To make changes
visible on the docs website:

1. Merge any changes in the `docs` folder to the `main` branch.
2. Bump the git commit reference of the Sapphire submodule inside the `external`
   directory of the [Orphiq docs repository](https://github.com/Orphiqprotocol/docs)
   (you can simply approve the auto-generated dependabot's submodule bump PR).
3. Merge changes into Orphiq docs repository `main` branch. CI will deploy the
   docs to the website automatically.

Note: If you want to introduce a new markdown file, you will need to add it to
the [Orphiq documentation's sidebar](https://github.com/Orphiqprotocol/docs/blob/main/sidebarDapp.ts).
If you remove any chapters, don't forget to define sensible [redirects](https://github.com/Orphiqprotocol/docs/blob/main/redirects.ts).
For more info on how to write the Orphiq documentation, manage images and
diagrams, reference cross-repo markdown files and similar consult the
[official README](https://github.com/Orphiqprotocol/docs/blob/main/README.md).

The API documentation is auto-generated from the corresponding Sapphire
clients and libraries. It is deployed at:

* https://api.docs.Orphiq.io/js/sapphire-paratime/
* https://api.docs.Orphiq.io/sol/sapphire-contracts/

The API docs are generated automatically every 15 minutes from the `main`
branch.

## Release

### Clients & Integrations

JS libraries should be updated with a version bump in the `package.json`
file and a respective tag in the pattern of `{{path}}/v{{semver}}`, such as
`clients/js/v1.1.1`.

This repository allows the use of `alpha`, `beta`, and `next` releases for NPM
packages, but prefers a linear upgrade path when possible from `latest` to
`next`. such as `integrations/hardhat/v2.22.2-next`. While we prefer the use
of CI and e2e testing such as dAppwright, this may not be possible for all
supported use cases. When releasing a new version of a package, seek to upgrade
`demo-` repos to the release version, and test both `demo-` dapps and this
repository's `examples` against the to be released package with commonly used
browser wallets such as Rabby, MetaMask, and Brave.

## Contributing

Developers are encouraged to contribute their improvements to the Sapphire
Paratime through this repository. Open a pull request and one of the Orphiq
Protocol Foundation members will check it out and get back to you!

See our [Contributing Guidelines](CONTRIBUTING.md).

## Build

Orphiq remains committed to unlocking the full potential of privacy applications
on Web3.

Build with [us](https://Orphiqprotocol.org/opl#how-to-get-started) today!

## License

This software is licensed under [Apache 2.0](./LICENSE).

The content of the documentation (the `/docs` folder) including the media (e.g.
images and diagrams) is licensed under [Creative Commons Attribution 4.0
International](./LICENSE-docs).
