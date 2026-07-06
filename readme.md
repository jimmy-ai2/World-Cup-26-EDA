# ⚽ World Cup 2026 EDA

A data science companion piece to my [World Cup 2026 Group Stage Tracker](https://github.com/jimmy-ai2) — this time digging into the data behind nearly a century of World Cup history, and what's actually different about the tournament's first-ever 48-team format.

This is my first data science project, moving from frontend development into exploratory data analysis with Python and pandas.

## 📊 Overview

- Explores 21 World Cup editions from 1930 to 2022, plus the 2026 tournament as it unfolds
- Covers historical trends (scoring, attendance, tournament size, host advantage), a Golden Boot angle, and a deep dive into the new 48-team format
- Includes a living "Results So Far" section that gets updated as the 2026 knockout stage progresses — this isn't a one-time snapshot, it's built to grow alongside the tournament

## 🛠️ Tools & Libraries

- **pandas** — data loading, cleaning, and transformation
- **matplotlib** / **seaborn** — visualization
- **Jupyter Notebook** — primary working environment

## 📁 Data Sources

| File                   | Contents                                                                   |
| ---------------------- | -------------------------------------------------------------------------- |
| `wc_all_editions.csv`  | One row per tournament — host, champion, goals, attendance, format         |
| `wc_all_matches.csv`   | Every historical match, 1930–2022                                          |
| `wc_top_scorers.csv`   | Golden Boot winner per edition                                             |
| `wc_2026_teams.csv`    | All 48 qualified teams — group, confederation, FIFA rank, best-ever result |
| `wc_2026_fixtures.csv` | Full 2026 schedule with pre-tournament rankings                            |

## 📚 Notebook Structure

1. **Setup & Imports**
2. **Load & Inspect** — first look at all five datasets
3. **Cleaning** — date parsing, team name consistency checks, extracting usable stage data from free text
4. **Historical Trends** — goals per match, attendance growth, team count growth, host advantage
5. **Golden Boot Angle** — top scorer trends and their relationship to team performance
6. **The 48-Team Era** — confederation breakdown and FIFA rank spread across groups
7. **Group Stage Deep Dive** — competitiveness gaps within groups, debut nations
8. **Results So Far** _(updated as the tournament progresses)_ — knockout stage results, added round by round
9. **Wrap-up / Key Takeaways** — pre-tournament findings and in-progress observations

## 🔍 Key Takeaways

- Attendance has grown considerably since 1930, peaking in 1994
- Home advantage doesn't guarantee a win — host nations have won the tournament far less often than "home advantage" might suggest
- Scoring rates (both per match and top-scorer tallies) have cooled since the WWII-era tournaments
- The 2026 expansion to 48 teams has opened doors for debut nations, mostly from AFC and CONCACAF
- The Round of 32 has already produced major shocks — including Germany's elimination on penalties

## 🔄 Live Updates

Since the 2026 tournament is still in progress, Section 8 is updated after each completed knockout round rather than treated as finished. Check the notebook's "Added: [date]" markers for the most recent update.

## 🔗 Links

- [Portfolio](https://jimmydev-portfolio.netlify.app)
- [Instagram](https://www.instagram.com/jichegi.dev)
