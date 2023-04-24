# zkSync Era Smart Account and Paymaster template

**A starter template to create smart contract accounts or paymasters on zkSync Era.**

This project was scaffolded with [zksync-cli](https://github.com/matter-labs/zksync-cli).

## Project structure

- `/contracts`: smart contracts.
- `/deploy`: deployment and contract interaction scripts.
- `/test`: test files
- `hardhat.config.ts`: configuration file.

## Commands

- `yarn hardhat compile` will compile the contracts.
- `yarn run deploy --script FILENAME` will execute the specified deployment script.


### Environment variables

In order to prevent users to leak private keys, this project includes the `dotenv` package which is used to load environment variables. It's used to load the wallet private key, required to run the deploy script.

To use it, rename `.env.example` to `.env` and enter your private key.

```
WALLET_PRIVATE_KEY=123cde574ccff....
```


## Official Links

- [Website](https://zksync.io/)
- [Documentation](https://v2-docs.zksync.io/dev/)
- [GitHub](https://github.com/matter-labs)
- [Twitter](https://twitter.com/zksync)
- [Discord](https://discord.gg/nMaPGrDDwk)
