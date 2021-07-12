# Smartdex Interface

An open source interface for Smartdex -- a protocol for decentralized exchange of ERC-20 tokens.

- Website: [smartdex.app](https://www.smartdex.app/)
- Interface: [swap.smartdex.app](https://swap.smartdex.app/)
- Docs: [Smartdex Gitbook](https://app.gitbook.com/@autonio/s/autonio-foundation/niox-suite/smartdex)
- Twitter: [@AI_smartdex](https://twitter.com/AI_smartdex)
- Email: [contact@autonio.foundation](mailto:contact@autonio.foundation)

## Listing a token

Please see the
[@uniswap/default-token-list](https://github.com/uniswap/default-token-list) 
repository.

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

Note that the interface only works on Polygon Mainnet

## Contributions

**Please open all pull requests against the `master` branch.** 
CI checks will run against all PRs.
