# RaptorX Research Challenge — Kamino (KMNO)

Evidence package for the Superteam Earn bounty: **RaptorX Research Challenge — "Ask better questions, find better alpha"** (125 USDC pool, 1st / 2nd place, agents allowed, deadline 2026-11-02 03:59:59 UTC).

- **Token:** Kamino (KMNO) — mint `KMNo3nJsBXfcpJTVhZcXLW7RmTwTt4GVFE7suUBo9sS` (Solana).
- **Date:** 28-10-2026 (UTC).

## Submission & status

- **Bounty:** OPEN, AGENT_ALLOWED, 125 USDC, deadline 2026-11-02 03:59:59 UTC (verified live 2026-10-29).
- **Submission:** `df81978b` — status **Pending** (in the pool, at sponsor judgment), submitted 2026-10-29 via the Superteam Earn agents API (HTTP 200), evidence linked to this repo.
- **Payout:** requires a human Superteam Earn account to claim via claimCode (see `COMPROBANTE-submission-KMNO.md`, section 6).

## What's in this repo

| Folder | Content |
|---|---|
| `reports/` | Externally-verified report on Kamino/KMNO: 15 public sources, every figure with a URL + timestamp, machine-checked citations. |
| `questions/` | The analytical question(s) for REX AI 5.0 — the judged deliverable. |
| `evidence/` | Raw provider responses (CoinGecko, DeFiLlama, DEX Screener, Solscan, Birdeye, Kamino docs), citation ledger, and verification results. |
| `screenshots/` | Token-page capture + the on-platform RaptorX AI (REX AI 5.0 / Claw) report on KMNO — legible, full-text capture. |
| `COMPROBANTE-submission-KMNO.md` | Submission proof: bounty status (OPEN / AGENT_ALLOWED, verified live), the Pending submission, repo evidence (85dace3), and the public-repo security verification. |

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
- **Captured (on-platform, in RaptorX):** the AI report generated inside the platform (REX AI 5.0 / Claw) on KMNO is now in `screenshots/` (legible) with full text in `reports/KMNO-clawai-report-full.txt` and the capture note in `reports/KMNO-1-clawai.md`. Honest caveat: Claw's price figure ($0.0245) lags live CoinGecko ($0.0377, verified 29-10) by ~35% — documented, not papered over.

This is not a buy or sell recommendation.

## Method

- Every number in `reports/KMNO-1.md` carries a source URL and timestamp; citations were machine-verified (`evidence/verification.json`: 0 marked unverified, 15 sources).
- Raw provider responses are preserved in `evidence/` (CoinGecko, DeFiLlama, DEX Screener, Solscan, Birdeye, Kamino official docs).
- The on-platform RaptorX AI report (REX AI 5.0 / Claw) is captured in `screenshots/` + `reports/KMNO-clawai-report-full.txt` (report_id `019f1a0b-c47e-7b06-8008-20594b283d82`, generated 29-10 00:11Z); the external report above stands independently.
