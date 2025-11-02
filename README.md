# Aptos Subscription Pass

A decentralized subscription management system built on the Aptos blockchain using the Move language.

## Overview

Aptos Subscription Pass allows users to purchase and manage time-based subscription passes using APT tokens. All subscription data is stored on-chain, ensuring transparency, immutability, and trustless verification.

## Project Structure

```
aptos-sub-pass/
├── sources/
│   └── subscription.move       # Main smart contract
├── frontend/
│   └── index.html             # Web interface
│
├── Move.toml                  # Move package configuration
└── .aptos/                    # Aptos account configuration
```

## Subscription Tiers

| Tier      | Duration | Price    | Description           |
| --------- | -------- | -------- | --------------------- |
| Weekly    | 7 days   | 0.05 APT | For short-term access |
| Monthly   | 30 days  | 0.15 APT | Regular users         |
| Quarterly | 90 days  | 0.40 APT | Extended access       |
| Yearly    | 365 days | 1.50 APT | Long-term savings     |

## Screenshots

**1. Dashboard**

![Dashboard](./screenshots/dashboard.jpg)

**2. Payment**

![Store Hash](./screenshots/payment.jpg)

![Verify](./screenshots/balance.jpg)

![Verify](./screenshots/wallet.jpg)

---

# Contract Address

0xea365a84a0ab9824484073536f5ed85b3bf6aaa2f7a5c0b15856b7ae9c6c4841

---

# Summary

A decentralized on-chain subscription management system built on Aptos, enabling users to purchase time-based passes using APT with transparent, verifiable tracking.
Includes smart contract, and a frontend for purchasing and validating subscriptions.

