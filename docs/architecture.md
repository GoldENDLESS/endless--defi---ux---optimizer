# Architecture & Technical Overview

## Project: AI-Assisted Cross-Chain DeFi Aggregator (ACDA)

### 1. Core Components

1. *Frontend DApp UI*
   - Built using React + TypeScript
   - Connects via Endless Wallet adapter

2. *Aggregator Core Logic*
   - Move smart contracts query liquidity from multiple protocols
   - AI logic to suggest optimal yields

3. *AI Reward Oracle*
   - On-chain AI model provides recommendations

4. *Cross-Chain Bridge Integration*
   - Uses Endless Bridge for asset transfers

### 2. Tech Stack

- *Endless Web3 SDK* — Wallet & network integration
- *Move Smart Contracts* — On-chain aggregation logic
- *AI Components* — Portfolio optimization suggestions

### 3. Implementation Flow

1. User connects wallet via Endless Wallet.
2. Frontend requests data from aggregation smart contract.
3. Contract queries liquidity pools across supported chains.
4. AI model evaluates options & scores yields.
5. Frontend displays recommendations.
6. User executes swap or deposit via cross-chain bridge.
