Implementation of contracts for [ERC-4337](https://eips.ethereum.org/EIPS/eip-4337) account abstraction via alternative mempool.

# Installation

```bash
yarn install
```

# Getting Started

```
cp .env.example .env
```

```
INFURA_ID @ https://app.infura.io/dashboard 
ETHERSCAN_API_KEY @ https://etherscan.io/myapikey
PRIVATE_KEY @ rec create a sep account for dev
COVERAGE=<boolean> (true or false)
```

# Testing

```bash
yarn test
```

# Compiling

```bash
yarn compile
```

# Deploying

```bash
yarn deploy --network <network>
```

# Resources

- [EIP-4337](https://eips.ethereum.org/EIPS/eip-4337)
