# FEVM Starter Kit

A minimal Hardhat project to deploy Solidity smart contracts to the Filecoin Virtual Machine (FEVM).

## Setup

```bash
git clone <repo-url>
cd fevm-starter
cp .env.example .env
# Add your PRIVATE_KEY to .env
npm install
```

## Deploying to Calibration Testnet

```bash
npx hardhat compile
npx hardhat run scripts/deploy.js --network calibration
```

## Links
- [Calibration Faucet](https://faucet.calibration.fildev.network/)
- [FEVM Docs](https://docs.filecoin.io/smart-contracts/ethereum/)
- [Filfox Explorer](https://calibration.filfox.info/en)
