# contracts-archive

Contract sources from the arbitrage project that have no repository of their own.

## ethereum/dydx-arbitrage-2022-07-17

The first executor we deployed on Ethereum mainnet: a dYdX flash loan and two Uniswap-style routers.

| | |
|---|---|
| Address | [`0xB9e61F25Dd836aE289627432b26F640C51c452cf`](https://etherscan.io/address/0xB9e61F25Dd836aE289627432b26F640C51c452cf#code) |
| Deploy transaction | [`0x1d11a345…564cad`](https://etherscan.io/tx/0x1d11a345ba29ca457a257f77c4e99a11eea3b6cfead652eebfee261a29564cad) |
| Deployed | July 17th, 2022 |
| Compiler | solc 0.8.9, optimizer off (Truffle defaults) |

`Arbitrage.sol` is the `source` field of the Truffle build artifact saved when the contract was compiled for deployment. The same source is verified on Etherscan against the deployed bytecode. It imports `@uniswap/v2-periphery` and `@openzeppelin/contracts`, which are standard npm packages and are not copied here.

The BNB Chain and Polygon contracts of the same generation use a DODO flash loan instead, and their source is in [zzz-the-josh-bot](https://github.com/crypto-jambot/zzz-the-josh-bot). The later generations are in [jam-contracts](https://github.com/crypto-jambot/jam-contracts).
