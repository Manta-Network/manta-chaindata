# manta-chaindata

Token and Chain data used in Manta's project


## Usage

### Token Logo

```
// KMA
https://raw.githubusercontent.com/Manta-Network/manta-chaindata/main/assets/tokens/KMA.svg

// USDT
https://raw.githubusercontent.com/Manta-Network/manta-chaindata/main/assets/tokens/USDT.svg
```

### Token List

```
https://raw.githubusercontent.com/Manta-Network/manta-chaindata/main/tokens.json
```

``` json
[
  {
    "id": "calamari-substrate-native-kma",
    "logoKey": "KMA",
    "coinGeckoKey": "calamari-network"
  },
  {
    "id": "calamari-substrate-usdt",
    "logoKey": "USDT",
    "coinGeckoKey": "tether"
  }
]
```

> id: chainId-chainType(-native)?-(symbol.toLowerCase())