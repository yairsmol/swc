# World Cup 2026 — Family Predictor

A single-file web app where the family predicts every 2026 World Cup match,
with a live leaderboard, stats, an auto-generated news feed, and betting-market odds.

- **App:** `index.html` (no build step, no dependencies)
- **Data:** Supabase project **SWC** (`lvcjoltkeksbatehhhlk`) — tables `predictions`,
  `results`, `odds`, with Realtime enabled for live leaderboard updates.
- **Host:** Vercel — static site, nothing to configure.

## Deploy on Vercel
Connect this repo to the `worldcup-2026-family-predictor` Vercel project.
Every push to the default branch auto-deploys. That's it — the app talks to
Supabase directly from the browser using the public anon key.

## Local preview
Just open `index.html` in a browser, or `npx serve`.
