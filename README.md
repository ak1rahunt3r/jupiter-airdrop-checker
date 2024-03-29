# jupiter-airdrop-checker
Solana wallets checker for `Jupiter` airdrop. Written on `.Net Framework 4.8` with `SolNet SDK`. Supported `Socks4` ans `Socks5` proxies. Multithread work with proxy mode.

![](https://github.com/ak1rahunt3r/jupiter-airdrop-checker/blob/main/example.png?raw=true)

### Setup
Private keys file looks like:
```
<pk1>
<pk2>
<pk3>    
```

Seeds file looks like:
```
<seed1>
<seed2>
<seed3>
```

Proxy file looks like:
```
199.58.185.9:4145
199.102.104.70:4145
103.174.178.245:2016
```

How to use:
- Extract archive with binaries
- Select mode work with (check private keys or seeds)
- Select file with private keys or seeds
- Select proxy mode (no proxy, socks4/5 supported)
- Select file with proxies
- Select thread count (dont use multithread without proxies)
- Start bot
- Checker results will be saved to `output` folder.

### Donate Me
```
SOL: C2J4EB2Pb3SHXWZX1CE3MWySpoJAzuXU8MRwAvosTHvV
ETH: 0xEB7b3aa5f0D5833866610F5401c0AF29f70E6C25
```
### Disclaimer
This project is intended solely for educational purposes, and the creator assumes no responsibility for any potential site spam from its use.
