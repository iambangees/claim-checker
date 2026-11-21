# Claim Checker

**Before you claim, check what it really costs.**

A one-page checker for free crypto claims, airdrops, whitelist spots and lending offers — the kind that spread through Telegram and X. Paste the pitch, and Claim Checker scans it for trap phrases, then walks you through a red-flag checklist built from real offers checked the hard way.

## What it does

- **Paste-the-pitch scan** — keyword detection for the classic traps: seed-phrase requests, pay-to-unlock, guaranteed returns, mandatory social posting, Developer Mode, non-transferable rewards, lock-ups, pressure tactics and token taxes. Matches are shown with the exact words found, and the matching checklist boxes are ticked (you can untick).
- **Red-flag checklist** — 16 checks in four groups: hard stops, costs & gates, token reality, and trust. Each explains in one line what it means for you.
- **Verdict** — Walk away (any hard stop, or costs stacking up), Proceed with caution, or No known traps found. The report lists what the "free" claim actually asks for, in plain language, and can be copied to share.
- **The golden rules** — six rules that would have caught every bad offer this tool was modelled on.

## Honesty notes

- The scan is keyword matching, not AI judgement — it says so on the page. A clean result means no *known* traps were found, never that an offer is guaranteed safe.
- Everything runs in the visitor's browser. Nothing pasted is uploaded anywhere; there is no backend, no tracking, no accounts.

## Tech

One static page (`site/index.html`) plus a banner drawn with Python/PIL. No build step. Published via GitHub Pages from the `site/` folder.
