## Hey there 👋

![An image of the bitcoin development kit logo](https://github.com/bitcoindevkit/.github/blob/master/profile/bdk-banner.png?raw=true)

Bitcoin Development Kit (BDK) is a suite of software libraries that allows you to build secure, feature-rich, and cross-platform Bitcoin wallets.

Most of the BDK projects are based on the powerful [`rust-bitcoin`](https://github.com/rust-bitcoin/rust-bitcoin) and [`rust-miniscript`](https://github.com/rust-bitcoin/rust-miniscript) libraries.

The home page for the overarching BDK project and the BDK Foundation that supports it is [bitcoindevkit.org](https://bitcoindevkit.org/).

### Project Tiers

We provide the technical infrastructure to maintain a number of software and documentation projects across different maturity levels and support models. To help you navigate these projects, we've categorized them along two dimensions: Maturity Level (Stable or Experimental) and Support Model (Foundation or Community). See "The Book of BDK" [chapter on library tiers](https://bookofbdk.com/getting-started/tiers/#library-tiers) for more details.

The lead and secondary maintainers for each project are responsible for triaging new issues and PRs, providing guidance to contributors, and reviewing and merging changes based on rough consensus from the community.

#### Foundation Supported

##### Stable

| Project                     | Lead Maintainer    | Secondary Maintainer   |
| --------------------------- | ------------------ | ---------------------- |
| [bdk_wallet]                | [ValuedMammal]     | [oleonardolima]        |
| [bdk/crates/core]           | [evanlinjin]       |                        |
| [bdk/crates/chain]          | [evanlinjin]       |                        |
| [bdk/crates/esplora]        | [oleonardolima]    |                        |
| [bdk/crates/electrum]       |                    |                        |
| [bdk/crates/bitcoind_rpc]   |                    |                        |
| [bdk/crates/testenv]        |                    |                        |
| [rust-esplora-client]       | [oleonardolima]    |                        |
| [rust-electrum-client]      |                    |                        |
| [bdk-ffi]                   | [thunderbiscuit]   | [reez]                 |
| [bdk-jvm]                   | [thunderbiscuit]   | [ItoroD]               |
| [bdk-android]               | [thunderbiscuit]   |                        |
| [bdk-swift]                 | [reez]             |                        |
| [bitcoindevkit.org]         | [reez]             | [thunderbiscuit]       |
| [book-of-bdk]               | [thunderbiscuit]   | [reez]                 |

[bdk_wallet]: https://github.com/bitcoindevkit/bdk_wallet
[bdk/crates/chain]: https://github.com/bitcoindevkit/bdk/tree/master/crates/chain
[bdk/crates/core]: https://github.com/bitcoindevkit/bdk/tree/master/crates/core

[bdk/crates/esplora]: https://github.com/bitcoindevkit/bdk/tree/master/crates/esplora
[bdk/crates/electrum]: https://github.com/bitcoindevkit/bdk/tree/master/crates/electrum
[bdk/crates/bitcoind_rpc]: https://github.com/bitcoindevkit/bdk/tree/master/crates/bitcoind_rpc

[bdk/crates/testenv]: https://github.com/bitcoindevkit/bdk/tree/master/crates/testenv
[rust-esplora-client]: https://github.com/bitcoindevkit/rust-esplora-client
[rust-electrum-client]: https://github.com/bitcoindevkit/rust-electrum-client

[bdk-ffi]: https://github.com/bitcoindevkit/bdk-ffi
[bdk-jvm]: https://github.com/bitcoindevkit/bdk-jvm
[bdk-android]: https://github.com/bitcoindevkit/bdk-ffi/tree/master/bdk-android
[bdk-swift]: https://github.com/bitcoindevkit/bdk-ffi/tree/master/bdk-swift

[bitcoindevkit.org]: https://github.com/bitcoindevkit/bitcoindevkit.org
[book-of-bdk]: https://github.com/bitcoindevkit/book-of-bdk

##### Experimental

| Project                     | Lead Maintainer    | Secondary Maintainer   |
| --------------------------- | ------------------ | ---------------------- |
| [bdk/crates/coin-select]    | [evanlinjin]       |                        |
| [bdk-tx]                    | [ValuedMammal]     |                        |
| [bdk-sp]                    | [nymius]           |                        |
| [electrum_streaming_client] | [evanlinjin]       |                        |
| [bdk-bitcoind-client]       | [ValuedMammal]     |                        |
| [bdk-sqlite]                | [ValuedMammal]     |                        |
| [bdk-dart]                  | [reez]             |                        |
| [bdk-rn]                    | [thunderbiscuit]   |                        |
| [bdk-cli]                   | [tvpeter]          |                        |
| [BDKSwiftExampleWallet]     | [reez]             |                        |
| [devkit-wallet]             | [thunderbiscuit]   |                        |

[bdk/crates/coin-select]: https://github.com/bitcoindevkit/coin-select
[bdk-tx]: https://github.com/bitcoindevkit/bdk-tx
[bdk-sp]: https://github.com/bitcoindevkit/bdk-sp
[electrum_streaming_client]: https://github.com/bitcoindevkit/electrum_streaming_client
[bdk-bitcoind-client]: https://github.com/bitcoindevkit/bdk-bitcoind-client
[bdk-sqlite]: https://github.com/bitcoindevkit/bdk-sqlite
[bdk-dart]: https://github.com/bitcoindevkit/bdk-dart
[bdk-rn]: https://github.com/bitcoindevkit/bdk-rn
[bdk-cli]: https://github.com/bitcoindevkit/bdk-cli
[BDKSwiftExampleWallet]: https://github.com/bitcoindevkit/BDKSwiftExampleWallet
[devkit-wallet]: https://github.com/bitcoindevkit/devkit-wallet

#### Community Supported

##### Stable

| Project                     | Lead Maintainer    | Secondary Maintainer   |
| --------------------------- | ------------------ | ---------------------- |
| [bdk-kyoto]                 | [rustaceanrob]     |                        |
| [bdk-python]                |                    |                        |
| [bdk-wasm]                  | [darioAnongba]     |                        |
| [bdk-reserves]              | [ulrichard]        |                        |
| [rust-cktap]                | [notmandatory]     |  [reez]                |
| [awesome-bdk]               | [thunderbiscuit]   |                        |

[bdk-kyoto]:https://github.com/bitcoindevkit/bdk-kyoto
[bdk-python]: https://github.com/bitcoindevkit/bdk-python
[bdk-wasm]: https://github.com/bitcoindevkit/bdk-wasm
[bdk-reserves]: https://github.com/bitcoindevkit/bdk-reserves
[rust-cktap]: https://github.com/bitcoindevkit/rust-cktap
[awesome-bdk]: https://github.com/bitcoindevkit/awesome-bdk

##### Experimental

| Project                     | Lead Maintainer        | Secondary Maintainer   |
| --------------------------- | ---------------------- | ---------------------- |
| [bdk-sqlx]                  | [matthiasdebernardini] |                        | 
| [bdk/crates/file_store]     |                        |                        |
| [bitcoin-ffi]               |                        |                        |

[bdk-sqlx]: https://github.com/bitcoindevkit/bdk-sqlx
[bdk/crates/file_store]: https://github.com/bitcoindevkit/bdk/tree/master/crates/file_store
[bitcoin-ffi]: https://github.com/bitcoindevkit/bitcoin-ffi

### 😃 Join our community

Community is fundamental to building and maintaining free and open source software and documentation. Please connect with 
us on GitHub and the BDK [discord server](https://discord.gg/UbTmGbNF3M)!

[ValuedMammal]: https://github.com/ValuedMammal
[evanlinjin]: https://github.com/evanlinjin
[reez]: https://github.com/reez
[thunderbiscuit]: https://github.com/thunderbiscuit
[rustaceanrob]: https://github.com/rustaceanrob
[oleonardolima]: https://github.com/oleonardolima
[tvpeter]: https://github.com/tvpeter
[ItoroD]: https://github.com/ItoroD
[nymius]: https://github.com/nymius
[darioAnongba]: https://github.com/darioAnongba
[notmandatory]: https://github.com/notmandatory
[ulrichard]: https://github.com/ulrichard
[matthiasdebernardini]: https://github.com/matthiasdebernardini

[https://bitcoindevkit.org]: https://bitcoindevkit.org
