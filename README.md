# FINNPUTER ARCADE

Three games in one repo, ready for GitHub Pages + Telegram (@finnputer_game_bot).

## Structure
- `index.html`      → FINNPUTER ARCADE hub (links to all games)
- `city/index.html` → FINNPUTER CITY
- `flap/index.html` → CANDLE FLAP
- `blaster/index.html` → SPACE BLASTER

## Deploy (GitHub Pages)
1. Create a repo, upload EVERYTHING from this folder into the repo root
   (so `index.html`, `city/`, `flap/`, `blaster/` sit at the top level).
2. Repo → Settings → Pages → Source: `main` → Save.
3. After 1–2 min the URLs are live:
   - Hub:     https://<user>.github.io/<repo>/
   - City:    https://<user>.github.io/<repo>/city/
   - Flap:    https://<user>.github.io/<repo>/flap/
   - Blaster: https://<user>.github.io/<repo>/blaster/
4. Test each URL in your phone browser BEFORE registering.

## Telegram Mini Apps (BotFather)
For CITY and FLAP, in @BotFather:
- `/newapp` → pick @finnputer_game_bot → set title, image, and the Web App URL (the /city/ or /flap/ URL).
- You get links like t.me/finnputer_game_bot/city and /flap.

Post those links (with the cover images) in your channel.

Notes:
- Highscore persistence (CloudStorage) only works inside the real Telegram Mini App; the browser uses localStorage.
