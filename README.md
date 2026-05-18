# PolyFollow

Polymarket wallet intelligence and follow alerts for traders who want to monitor top wallets without building their own data pipeline.

## What It Does

- Shows live Polymarket leaderboard data.
- Provides a server-rendered top-wallet proof page that can be shared before signup.
- Surfaces trader PnL, holdings, open positions, and wallet profile context.
- Helps build a watchlist of top wallets to monitor.
- Supports follow-alert workflows for watched wallets and markets.
- Runs in read-only informational mode for the public deployment.

## Why Pay For Founding Access

The public leaderboard is useful, but it does not choose what to watch for you. Founding access is for traders who want setup help now while the hosted beta matures.

For **$49**, founding access covers:

- first wallet/watchlist setup
- leaderboard review for the buyer's trading interests
- alert workflow design for watched wallets or markets
- early beta access as premium follow tooling is rolled out

## Live Verification

The hosted backend is running on a JP cloud host and can access Polymarket public APIs.

Shareable proof page:

```text
```

Example public endpoint:

```text
```

Health endpoint:

```text
```

Expected health response:

```text
polyfollow-ok
```

## Important Risk Notice

PolyFollow is informational analytics only. It is not financial advice, managed trading, custody, or a profit guarantee. Prediction-market trading involves risk of loss.

The public deployment currently has live trading disabled.

```text
TRADING_ENABLED=false
```

## Why This Exists

Prediction-market traders increasingly want wallet intelligence, top-trader monitoring, whale alerts, and copy-ready research workflows. PolyFollow focuses on making those workflows usable without requiring every user to build their own Polymarket API stack.
