# GoldBot — Algorithmic Trading System

**This project is strictly confidential and under active development.**

A private algorithmic trading system operating on the XAU/USD (Gold/US Dollar) pair. The system continuously analyzes market conditions and executes decisions based on proprietary logic.

> Source code is intentionally not included in this repository.
> This README serves as a public reference only.

## System overview

- **24/7 Node.js server** (Express) running independently of any browser session
- **Live market data** — XAU/USD price stream over WebSocket (Finnhub)
- **Signal engine** — proprietary analysis logic with approval/ignore decision tracking
- **State persistence** — trades, open position and signal stats survive restarts
- **Live dashboard** — real-time browser view of price, position and trade history
- **Deployed** with process auto-start (Procfile-based hosting)

## Stack

Node.js · Express · WebSocket (ws) · Finnhub API

---

[nikosmart.pl](https://nikosmart.pl)
