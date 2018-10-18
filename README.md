Pop Wallet
==========
Pop Wallet is a DApp browser and Ethereum wallet - designed to be simple and intuitive and targeted at mainstream, non-crypto literate userbase.

# Principles

- The browser layer is kept as simple and lightweight as possible. Features are traded off for simplicity and functionality is delegated down to the DApp layer. An initial DApp is shipped with Pop Wallet but it is not mandatory for users to access, in general all DApps should be feature rich and browser layer as light as possible.

- No key management for users and no seed phrases for users to write down. The initial version of Pop Wallet encrypts the private key with a password and is only suitable for "small change", not large funds, because if the device is lost then the funds are lost. However future versions will incorporate a smart contract custody system so that the device only acts as an authentication to the funds and backup/recovery is provided by authorising multiple devices.

- No point of centralisation and no single points of failure. The current version of Pop Wallet is a Google Chrome extension - however future version will be stand-alone browser (to remove Google as a single point of failure). The current version connects to an Infura Ethereum node - however future version will connect to light client running locally to remove this point of centralisation.

- The decentralised internet (Web 3) should be accessed in the same familiar way as the traditional internet. Browsing between traditional web pages and DApps should be seamless.

- Principles of decentralisation, security and privacy will be upheld throughout.

- Simplicity for mainstream adoption! The guiding principle - features should be developed in the DApps - not in the browser/wallet layer.

# Roadmap

- [ ] **Milestone 1** - initial release of DApp browser as Chrome extension connecting to Infura. Keys encrypted locally.
Basic DApp included to facilitate send/receive of Ether transactions. Also Basic DApp to provide links to providers where Ether can be bought.

- [ ] **Milestone 2** - Introduction of smart contract custody system ("Smart Wallet"). Smart Wallets can be created and named to store funds in custody smart contracts and alternative devices can request authorisation to such. Gas relayers will be used so that the custody smart contracts will pay gas fees rather then the authorised accounts.
Advanced DApp to include Smart Wallet management and information on authorised accounts/devices.

- [ ] **Milestone 3** - Replace Chrome extension with stand-alone browser (all OS's), replace Infura with local light client. Extend Smart Wallets to be able to set thresholds and multi-sig behaviour.

- [ ] **Milestone 4** - Mobile version of browser (all OS's).

## Other features to be considered
- Potentially replace Ether as default currency with fiat stable coins, e.g. DAI, so that all transactions are in familiar fiat currencies.
- Enable micropayments, e.g. integrate with payment channels such as Raiden.
