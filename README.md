# The template of hardhat development environment

## Workflow

- Write contracts inside `contracts/`
- `yarn compile`
- `yarn test`
- Add/edit `scripts/` to deploy and deal with contracts
- `yarn executre scripts/[name] --network [localhost|goerli|etc.]`

## Configurations

Run `cp .env.sample .env` and then fill in the variables in `.env` as much as possible.

It's strongly recommended the mnemonic is for development use only and have no economic value.

You can configure environment settings by editting `hardhat.config.ts` (see [official hardhat documentation](https://hardhat.org/hardhat-runner/docs/config))

Also note that `networksConfig` in `helper.ts` allows you to add some custom settings for each network.

## Reference

- [Hardhat documentation](https://hardhat.org/hardhat-runner/docs/getting-started)
- [Ethers.js documentation](https://docs.ethers.io/v5/)

## Todo

- Add test for the sample contract
