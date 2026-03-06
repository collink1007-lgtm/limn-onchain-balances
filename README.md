# Real On-Chain Balance Reader

> Part of the Tessera Sovereign Realification Initiative

## Overview
Replace world-state balances with real SPL token reads

## Current State
**MOCKED** — Using mock data instead of real sources

## Target State
Real-time SPL token balance reads from Solana RPC for all agent wallets

## Category
**On Chain Analytics**

## Approval
- **Proposal ID:** RF-C06-002
- **Votes:** 25/30 APPROVE (83.3%)
- **Threshold:** 2/3 majority (20 votes)
- **Status:** ✅ APPROVED

## Primary Files to Modify
- server/real-limn-data.ts

## Integration Points
- LIMN Token: BvBuBkxUQxhpiRdvoJfTRxi6JcRF7daNcSjfBnNDpump
- Community Wallet: 31D8imP7kmNhnvxaBBxjFhocwq9XDG9FBfgsDQuCwxVj
- Tessera Sovereign Ecosystem

## Getting Started
```bash
npm install
cp .env.example .env
npm run dev
```

## License
MIT — Tessera Sovereign Project
