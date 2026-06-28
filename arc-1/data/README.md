# Arc 1 data

NBA player season totals, one CSV per season.

- **Source:** Basketball-Reference (basketball-reference.com), "Player Stats: Totals". Data © Sports Reference LLC.
- **Retrieved:** 2026-06-27, via the browser "Get table as CSV" export.
- **Seasons:** 2022-23, 2023-24, 2024-25.
- **Schema:** `season, name, team, pos, games, minutes, points, rebounds, assists, steals, blocks, turnovers` — one row per player per season.
- **Transformations:** renamed columns to the schema above; added `season`; collapsed each traded player to one row (their combined-season totals, attributed to the team they played the most games for).
- **Use:** a small subset included for educational use in this course. See sports-reference.com for terms.
