
# No‑Fuss NBA Lineups (East/West + Healthy Page)

## Files
- `index.html` — Last‑game lineups, split East/West, alphabetized.
- `healthy.html` — “No injuries/suspensions” lineups, same layout.
- `style.css` — Shared CSS
- `lineups.json` — You update only this.

## `lineups.json` keys
- `conf`: "East" or "West" (required for the split)
- `default_lineup`: 5 players with positions PG/SG/SF/PF/C
- `last_game`: { date, opponent, lineup[5], notes }

## Daily updates
1) Edit the teams that played (last_game.*)  
2) Adjust `default_lineup` if the healthy five changes  
3) Update `meta.last_updated`

## Hosting
Use GitHub Pages with “Deploy from a branch” (main / root).
