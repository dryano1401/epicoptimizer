# Epic Universe Optimizer

Phone-friendly day-of touring optimizer for Universal Epic Universe on June 18, 2026.

## Live page

After GitHub Pages is enabled for this repository, the app should be available at:

https://dryano1401.github.io/epicoptimizer/

## What it does

- Loads waits from a same-origin `queue_times_cache.json` file to avoid iPhone/Safari CORS failures.
- The cache is seeded from the Queue-Times Epic Universe live page and refreshed by GitHub Actions from the Queue-Times JSON API.
- Keeps manual wait entry as a fallback.
- Gives ride-now / skip / recheck guidance based on threshold rules.
- Tracks completed must-do rides locally in the browser.
- Designed for iPhone/Safari and Add to Home Screen.

## iPhone use

1. Open the GitHub Pages URL in Safari.
2. Tap **Load cached Queue-Times waits**.
3. Tap **Auto-refresh: off** to reload the cache every 5 minutes.
4. Use **Share → Add to Home Screen** for app-like use.

## Data attribution

Live wait import is powered by Queue-Times.com public wait-time data. Manual entry remains available if iOS blocks the request or if the cache is stale.

## GitHub Pages setup

Recommended:

Settings → Pages → Deploy from branch → gh-pages / root → Save
