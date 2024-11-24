# Indigo

This repo is a fork of [nocturne]() that includes the circuits and smart contracts comprising Nocturne. The application is analgous to a VPN which works by replacing your IP address with the one from its server, making it harder for a third party to track your online activities. In this case, Indigo much like a VPN serves to also conceal your actvity but for on-chain transactions by replacing your wallet address with one from ours. 

## Getting Started

- `yarn install`
- `yarn install-deps` (installs `gsed`, `circom`, and `foundry` libraries)
- `yarn build` (builds only contracts)
- `yarn test:unit`

### Building circuits

Circuits can be built by running `yarn build:<circuit-name>` from the `circuits` package directory, or `yarn build:all` to build all of them at once.
