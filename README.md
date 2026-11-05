# Ère

A research and paper-trading platform for algorithmic strategies in frontier and emerging markets, built by [The Elixirs Lab](https://www.theelixirslab.com).

> This repository describes the platform. The trading engine source is private.

## What it does

- **Research:** market data for African exchanges, feature engineering, and an AI committee that reviews each strategy before it runs.
- **Strategy building:** a builder that exports readable MQL5, MQL4 and cTrader code, plus a custom Python runner.
- **Validation:** backtesting with walk-forward validation and post-backtest reporting.
- **Execution:** paper trading and bots behind risk gates. Live execution is in development.

## Strategy engines

- **OCTAVIAN:** a multi-layer confluence scoring engine combining Elliott Wave, smart-money concepts, Wyckoff phases, regime filtering, momentum and divergence, session timing and volume profiling.
- **Zone Architect:** an adaptive institutional zoning system (order blocks, breaker blocks, fair value gaps, liquidity sweeps) with walk-forward backtesting and regime-adaptive risk:reward rules.

## Status

| Area | State |
|---|---|
| Research and backtesting | Working, in staging |
| Paper trading | Live |
| Live execution | In development |
| Plans | Free, Pro and Elite tiers |

## Related research

[Regime detection in illiquid frontier markets](https://www.theelixirslab.com/research/regime-detection)

## Contact

info@theelixirslab.com
