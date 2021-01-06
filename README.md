# Hardhat Vue.js Starter Template

> Still in heavy development

A starter template for Ethereum dApps that uses the following tools:

- Hardhat
- Waffle
- ethers.js
- Vue
- Web3Modal

## Run Vue app

```bash
cd frontend && npm run serve
```

## Tests

### Solidity/Hardhat

```bash
npx hardhat test
```

## Deployment to ganache

```bash
npx hardhat run scripts/deploy.js --network ganache
```

## Deployment to a remote blockchain

```bash
npx hardhat run scripts/deploy.js --network goerli
```

## Verify on Etherscan

```bash
npx hardhat --network mainnet etherscan-verify --api-key <apikey>
```
