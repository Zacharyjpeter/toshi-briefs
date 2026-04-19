# toshi-briefs

Public static host for shareable Toshi Partners theme briefs (guest message patterns, monthly action briefs, etc.).

Served via **GitHub Pages** from the `main` branch root.

## URL pattern

Any HTML file in `/briefs/` is reachable at:

```
https://zacharyjpeter.github.io/toshi-briefs/briefs/<filename>.html
```

Example:

```
https://zacharyjpeter.github.io/toshi-briefs/briefs/toshi_messages_action_brief_2026-04-18.html
```

The root URL (`https://zacharyjpeter.github.io/toshi-briefs/`) renders [index.html](index.html), which lists all briefs newest-first.

## What belongs here

- Aggregate theme briefs, action plans, and monthly reports meant for internal team sharing.
- **Non-sensitive, aggregated output only.** No PII, guest details, booking-level data, financials, credentials, or API keys.

## What does NOT belong here

- Anything from `toshi-messages`, `toshi-pnl`, `toshi-bookings`, or other operational repos.
- Raw exports, transaction data, or per-property numbers.
- Anything you wouldn't be comfortable posting on the public internet — this repo is **public**.

## Adding a new brief

1. Drop the HTML file into `/briefs/` using the `YYYY-MM-DD_description.html` naming convention.
2. Update [index.html](index.html) with a link to the new brief (newest at top).
3. Commit and push — the Pages build runs automatically.
