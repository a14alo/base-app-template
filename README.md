# base-app-template
this is my test app on base
README.md (skeleton)
# Base dApp Template

Small starter for deploying a SimpleStorage contract to Base (Sepolia testnet) and connecting with a React frontend.

## Quickstart

1. Clone repo
2. Copy `.env.example` to `.env` and fill `PRIVATE_KEY`
3. `cd hardhat` → `npm install` → `npx hardhat compile`
4. `npx hardhat run scripts/deploy.js --network baseSepolia`
5. Note deployed contract address and open `frontend`:
   - `cd frontend` → `npm install` → `npm run dev`
6. In the frontend enter the contract address, connect wallet, and interact.
