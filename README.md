# AliSwap Interface

An open source interface for AliSwap -- a protocol for decentralized exchange of Ethereum tokens.

- Interface: [aliswap2024.com](https://aliswap2024.com)

## Accessing the AliSwap Interface

To access the AliSwap Interface, use an IPFS gateway link from the
or visit [aliswap2024.com](https://aliswap2024.com).


## Development

### Install Dependencies

```bash
yarn
```

### Run

```bash
yarn start
```

### Configuring the environment (optional)

To have the interface default to a different network when a wallet is not connected:

1. Make a copy of `.env` named `.env.local`
2. Change `REACT_APP_NETWORK_ID` to `"{YOUR_NETWORK_ID}"`
3. Change `REACT_APP_NETWORK_URL` to e.g. `"https://{YOUR_NETWORK_ID}.infura.io/v3/{YOUR_INFURA_KEY}"` 

## Contributions

**Please open all pull requests against the `master` branch.** 
CI checks will run against all PRs.
