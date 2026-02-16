# 🦁 NguliFxAlgo — AI Powered Expert Advisor (Safety First)

NguliFxAlgo is a professional AI powered algorithmic trading system built for real‑world conditions. It combines adaptive market intelligence with institutional risk controls, clear notifications, and battle‑tested presets. The goal is simple: protect capital, reduce decision stress, and grow accounts responsibly.

## Why Traders Choose NguliFxAlgo
- Adaptive to market conditions: automatically reads regimes and adjusts behavior.
- Risk comes first: daily loss stops, equity drawdown guards, correlation limits.
- Alerts that matter: real‑time status, trade updates, and risk warnings.
- Notifications that matter: real‑time status, trade updates, and risk warnings across multiple channels (mobile push, Telegram, e-mail, in app).
- AI as strategy/decision layer: optional AI engine can act as primary signal generator, regime validator, or risk adjuster with full human override.
- Scales with you: from small accounts to larger deployments.
- Clean setup: presets for different styles, optional AI assist, and a clear dashboard.

## What It Can Do
- Regime awareness: trending, ranging, compression, expansion, volatile phases.
- Strategy control: Auto, Scalper, or Swing modes (with intelligent switching in Auto).
- News guard: pauses at high‑impact events to avoid chaotic fills.
- Dynamic risk: ATR‑based sizing with session‑aware scaling and circuit breakers.
- Execution quality: monitors spread/slippage and reports broker conditions.
- Notifications hub: mobile push, EMail and Telegram (optional) with rich context.
- AI Decision Layer: optional, on-chart status, influences entries/exits, regime confirmation, and risk sizing with human override.
- Licensing and stability: reliable server validation with clear on‑chart status.

## Safety First
- Circuit breakers: daily loss and equity drawdown caps.
- Portfolio awareness: correlation checks to avoid overexposure.
- Session discipline: professional vs. off‑peak behavior.
- Controlled exits: break‑even, trailing, and partials when enabled.
- Expiry reminders: time‑based license warnings before expiry.

## Quick Start
- Copy files into MT5 Data Folder → MQL5.
- Compile in MetaEditor (F7).
- Attach to your chart and load a preset.
- Enable WebRequest for licensing: https://license.botifysocial.com
- Keep license key private; do not share presets with secrets.

## Requirements
- Windows with MetaTrader 5.
- Stable internet and a VPS recommended for 24/5 operation.
- Modern broker conditions (reasonable spreads and reliable execution).

## Supported Use Cases
- Conservative growth with strict risk caps.
- Professional hours focus (London/New York overlap).
- Automated or semi‑automated operation with clear oversight.

## Inputs Overview (167 Tunable Settings)
All configuration is driven by inputs stored in preset (.set) files. You don’t need to memorize them—each preset ships with sensible defaults. Here’s a compact guide to how they’re organized and what they influence:

- Risk Management
  - Position risk %, daily loss stop, equity guard, max trades/day.
  - Correlation limits and per‑symbol caps to prevent stack‑ups.
- Trade Management
  - Break‑even switches, trailing styles (step or ATR), partial close triggers.
  - Take‑profit/stop‑loss behavior and rounding for broker precision.
- Sessions & Time Controls
  - Professional/off‑peak session multipliers and trading windows.
  - Friday auto‑close and end‑of‑week protection.
- News Filter
  - Impact levels to avoid, pre/post buffers, affected currencies.
  - Complete halt vs. reduced risk around sensitive events.
- Strategy & Signals
  - Auto/Scalper/Swing mode, switching sensitivity, fallback rules.
  - Moving averages, RSI thresholds, regime detector sensitivity.
- AI (Optional)
  - Enable/disable AI, influence level (advisory to autonomous), model endpoint.
  - Safeguards to prevent over‑intervention.
- Execution Quality & Broker Conditions
  - Spread/slippage tolerances, rejection handling, retry logic.
  - Logging levels and broker score reporting.
- Notifications
  - Mobile push and Telegram toggles, progress intervals, intel depth.
  - Circuit‑breaker and system heartbeat messages.
- Capital Protection & Circuit Breakers
  - Hard stops for the day, account‑wide equity limits, cooldown timers.
  - Daily profit lock (optional) to protect green days.
- Licensing
  - License key input, server timeout, activation behavior.
  - Expiry warning window (days) and reminder cadence.
- Backtesting & Optimization Aids
  - Data guards, modeling assumptions, quick‑test toggles.
  - Preset variants for different symbols/timeframes.

Tip: You can import a .set file, adjust only what you need, and export your own template for safe reuse. The deploy script supports injecting secrets locally so public presets stay clean.

## Built‑In Advantages
- Consistency over noise: rules, limits, and habits encoded into the system.
- Fewer surprises: market regime awareness avoids forcing trades in bad conditions.
- Cleaner operations: one on‑chart dashboard, reduced flicker, and clear statuses.
- Grows with you: from starter accounts to larger capital with the same discipline.

## Licensing & Activation
- Licensed for authorized accounts only.
- Activation limits protect fair use; the dashboard shows clear license status.
- Alerts are time‑based as expiry approaches so you can renew calmly.
- WebRequest must include: https://license.botifysocial.com

## Support
- Email and chat support provided for installation and usage guidance.
- Community channels available for updates and best‑practice presets.

## Risk Notice
Trading involves risk. NguliFxAlgo focuses on capital protection and discipline, but no system can eliminate losses. Operate within your tolerance and local regulations.

—

NguliFxAlgo — trade with structure, protect your capital, and grow with confidence.
