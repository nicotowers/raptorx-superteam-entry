# RaptorX Research Challenge — Kamino (KMNO)

Evidence package for the Superteam Earn bounty: **RaptorX Research Challenge — "Ask better questions, find better alpha"** (125 USDC pool, 1st / 2nd place, agents allowed, deadline 2026-11-02 03:59:59 UTC).

- **Token:** Kamino (KMNO) — mint `KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS` (Solana).
- **Date:** 28-10-2026 (UTC).

## What's in this repo

| Folder | Content |
|---|---|
| `reports/` | Externally-verified report on Kamino/KMNO: 15 public sources, every figure with a URL + timestamp, machine-checked citations. |
| `questions/` | The analytical question(s) for REX AI 5.0 — the judged deliverable. |
| `evidence/` | Raw provider responses (CoinGecko, DeFiLlama, DEX Screener, Solscan, Birdeye, Kamino docs), citation ledger, and verification results. |
| `screenshots/` | Token-page capture, plus the on-platform RaptorX AI report + REX AI 5.0 interaction (in capture). |

## The question to REX AI 5.0 (core of the submission)

See [`questions/RECX-5-questions.md`](questions/RECX-5-questions.md).

> In one line: Kamino shows real protocol fees (~$4.8M / 30d) and a $1.33B TVL, yet the KMNO token shows **$0 holder revenue**, only **conditional** governance, and a **3.9%-of-circulating** unlock landing while **~80%** of sample DEX liquidity sits in one pool (~540x smaller than protocol TVL). Is KMNO a claim on protocol value or a decoupled points token, and what single signal + what liquidity threshold would decide it?

## Report summary (three lines)

Kamino bundles lending, liquidity and leverage on Solana; KMNO enables staking for points benefits and its docs frame governance only conditionally.
CoinGecko reported price USD 0.03878, market cap USD 227.5M, 24h volume USD 8.3M; DeFiLlama logged USD 1.33B TVL.
Next reported unlock: 30-10-2026, ~229M KMNO (~3.9% of circulating); the effectively-locked share and the operational presence of the mint on RaptorX remain under capture.

## Evidence separation (honesty standard)

- **Verified externally** (15 sources, every figure with a URL): mint identity, documented utility, initial allocation, market reference, TVL, borrows, revenue and the queried pools.
- **Provider-reported, with limits:** the unlock event and its calendar. The effectively-locked percentage: **not verified**.
- **Pending (on-platform capture in RaptorX):** the AI report generated inside the platform + the REX AI 5.0 interaction (legible captures).

This is not a buy or sell recommendation.

## Method

- Every number in `reports/KMNO-1.md` carries a source URL and timestamp; citations were machine-verified (`evidence/verification.json`: 0 marked unverified, 15 sources).
- Raw provider responses are preserved in `evidence/` (CoinGecko, DeFiLlama, DEX Screener, Solscan, Birdeye, Kamino official docs).
- The on-platform RaptorX AI report and the REX AI 5.0 interaction are being captured into `screenshots/` and will be added as soon as they land; the external report above stands independently.
