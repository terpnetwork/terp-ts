# terp-network

<p align="center" width="100%">
    <img height="90" src="https://github.com/terpnetwork/chain-registry/blob/master/terpnetwork/images/logo.png?raw=true" />
</p>

<p align="center" width="100%">
  <!-- <a href="https://github.com/CosmosContracts/typescript/actions/workflows/run-tests.yml">
    <img height="20" src="https://github.com/CosmosContracts/typescript/actions/workflows/run-tests.yml/badge.svg" />
  </a> -->
   <a href="https://github.com/CosmosContracts/typescript/blob/main/LICENSE"><img height="20" src="https://img.shields.io/badge/license-MIT-blue.svg"></a>
</p>

Typescript libraries for the Terp ecosystem.

## Packages

#### [terp-network](packages/terp-network/README.md)

TS library with Cosmos SDK and terpSwap smart contracts.

#### [@terp-network/swap](packages/swap/README.md)

TS library with terpSwap smart contracts.

#### [@terp-network/assets](packages/assets/README.md)

Chain Registry info for terp, including asset lists.

## Developing

Checkout the repository and bootstrap the yarn workspace:

```sh
# Clone the repo.
git clone https://github.com/CosmosContracts/typescript
yarn
yarn bootstrap
```

### Building

```sh
yarn build
```
### Publishing

```
lerna publish
# lerna publish minor
# lerna publish major
```
## Credits

🛠 Built by Cosmology — if you like our tools, please consider delegating to [our validator ⚛️](https://cosmology.tech/validator)

Code built with the help of these related projects:

* [@cosmwasm/ts-codegen](https://github.com/CosmWasm/ts-codegen) for generated CosmWasm contract Typescript classes
* [@cosmology/telescope](https://github.com/cosmology-tech/telescope) a "babel for the Cosmos", Telescope is a TypeScript Transpiler for Cosmos Protobufs.
* [chain-registry](https://github.com/cosmology-tech/chain-registry) an npm module for the official Cosmos chain-registry