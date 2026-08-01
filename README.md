# IPL Analysis Dashboard

Power BI dashboard covering IPL seasons 2008–2025 — match results, team standings, and top individual performers (Orange Cap, Purple Cap, most sixes/fours) on a single page, filterable by season.

## File
`IPL.pbix` — open with Power BI Desktop.

## Data Model
- **ball_by_ball_data** — main fact table, source of most measures (runs, wickets, boundaries, cap holders, match results)
- **ipl_matches_data** — match info (season, venue)
- **teams_data** — team names and logos
- **players-data-updated** — player details

## What's on the dashboard
- Total matches, total teams, total 4s/6s, centuries and half-centuries
- Orange Cap — top run-scorer (name, runs, strike rate, team)
- Purple Cap — top wicket-taker (name, wickets, team)
- Most sixes and most fours hit, with player and team
- Champion and runner-up team for the season
- Team standings table — matches played, won, lost, tied, no result, points

## Filter
Season dropdown (top right) — filters everything on the page.

## How to use
1. Open `IPL.pbix` in Power BI Desktop.
2. Pick a season from the dropdown, or leave it blank for all-time totals.
3. Check the KPI cards for season highlights and the table at the bottom for full standings.
