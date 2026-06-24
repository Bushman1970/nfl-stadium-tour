# Bush Family NFL Stadium Tour

A single-page family scrapbook tracking our goal: **attend an NFL game at every team's home stadium.**

**Status:** 7 of 32 stadiums visited (~22%). The page shows an interactive US map, a progress bar, a memory from every visit, and the stadiums still to go.

## Visited so far

| Date | Stadium | Game |
|------|---------|------|
| Oct 26, 2014 | EverBank Field — Jacksonville | Dolphins 27, Jaguars 13 |
| Oct 10, 2021 | Heinz Field — Pittsburgh | Steelers 27, Broncos 19 (Levi's 15th birthday) |
| Oct 9, 2022 | Raymond James — Tampa Bay | Buccaneers 21, Falcons 15 |
| Oct 15, 2023 | Soldier Field — Chicago | Vikings 19, Bears 13 |
| Dec 24, 2023 | Hard Rock — Miami | Dolphins 22, Cowboys 20 |
| Oct 13, 2024 | AT&T Stadium — Dallas | Lions 47, Cowboys 9 |
| Dec 15, 2024 | NRG Stadium — Houston | Texans 20, Dolphins 12 |

## How it's built

A single self-contained `index.html` — no build step. The map uses [D3](https://d3js.org) + [TopoJSON](https://github.com/topojson) with the [us-atlas](https://github.com/topojson/us-atlas) topology, loaded from CDN. Game facts were researched in June 2026 (ESPN, NFL.com, Wikipedia, team sites).

To update after a new game: edit the `visited` / `remaining` arrays in `index.html` and bump the progress numbers in the hero. The canonical content lives in the family vault (`wiki/concepts/NFL Stadium Tour.md`).

Published with GitHub Pages.
