# TokenBar

TokenBar is a small macOS menu bar app for keeping AI coding-agent usage visible while you work.

It is built for people who use Codex heavily and want a quick local view of token usage, reset pressure, forecasted spend, and work rhythm without opening a dashboard every few minutes.

![TokenBar AI overview](assets/screenshots/tokenbar-overview.png)

## What It Shows

- Codex token usage from local session logs
- 5-hour and weekly quota pressure
- Daily token history with peak-day highlighting
- Estimated dollar usage from local token counts
- Forecast views for usage pace and spend
- Quick Insights for today, weekly pressure, peak day, average day, and projected cost

## AI Overview

The overview is designed as a compact data-storytelling surface. Use the arrow controls to move through different views of the same usage data, including daily bars, cost forecast, work rhythm, cumulative usage, spike detection, heat blocks, pace against average, peak share, weekly burn, and agent activity.

![TokenBar quick insights](assets/screenshots/tokenbar-quick-insights.png)

## Provider Status

TokenBar currently reads Codex usage locally. Claude, Gemini, Cursor, and Antigravity are shown as future connector surfaces until explicit usage APIs or local exports are wired in.

Browser sign-in is not treated as usage authorization. TokenBar does not read browser cookies, passwords, account secrets, or provider tokens.

## Download

Latest macOS arm64 build:

[Download TokenBar](https://github.com/Arnie016/codex-goated-skills/releases/download/v0.1.0/CodexLimitBar-macOS-arm64-2026-05-20.zip)

Because this early build is ad-hoc signed, macOS may show a Gatekeeper warning on first open.

## Status

Early public build. The current app is local-first and focused on Codex. Exact billing, purchased credits, and organization-level usage should still be verified in the official provider dashboard.
