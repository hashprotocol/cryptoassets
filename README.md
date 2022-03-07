# Cryptoassets js

Crypto assets data and utilities through a standard interface

## Installation

```bash
npm install @hashprotocol/cryptoassets --save
```

## Usage

```
> const { assets, chains, currencyToUnit } = require('@hashprotocol/cryptoassets')
> assets.BTC.code
BTC
> assets.ETH.decimals
18
> currencyToUnit(assets.BTC, 1)
100000000
> chains.ethereum.safeConfirmations
3
> chains[assets.btc.chain].fees.unit
sat/b
> chains[assets.eth.chain].isValidAddress('0x5A0b54D5dc17e0AadC383d2db43B0a0D3E029c4c)
true

```

## License

[MIT](./LICENSE.md)
