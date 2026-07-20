# ⚽ World Cup 2026 EDA

A data science companion piece to my [World Cup 2026 Group Stage Tracker](https://github.com/jimmy-ai2) — digging into the data behind nearly a century of World Cup history, and what was actually different about the tournament's first-ever 48-team format.

This was my first data science project, moving from frontend development into exploratory data analysis with Python and pandas.

## 📊 Overview

- Explores 21 World Cup editions from 1930 to 2022, plus the complete 2026 tournament
- Covers historical trends (scoring, attendance, tournament size, host advantage), a Golden Boot angle, and a deep dive into the new 48-team format
- Includes a full knockout-stage results log — built and updated round by round as the 2026 tournament played out, from Round of 32 through the Final

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
8. **Results So Far** — full 2026 knockout stage results (Round of 32 → Final), built up round by round as the tournament progressed
9. **Wrap-up / Key Takeaways** — pre-tournament findings and a full knockout-stage summary

## 🔍 Key Takeaways

- Attendance has grown considerably since 1930, peaking in 1994
- Home advantage doesn't guarantee a win — host nations have won the tournament far less often than "home advantage" might suggest
- Scoring rates (both per match and top-scorer tallies) have cooled since the WWII-era tournaments
- The 2026 expansion to 48 teams opened doors for debut nations, mostly from AFC and CONCACAF
- The knockout stage delivered real drama: 9 of 32 matches (28%) went beyond 90 minutes, Germany and Brazil both exited earlier than expected, and Morocco's underdog run carried them to the Quarter-finals
- **Spain won the 2026 World Cup**, beating Argentina 1-0 in extra time in the Final; England took third place

## 🏆 Final Results

- **Champions:** Spain
- **Runners-up:** Argentina
- **Third place:** England
- **Fourth place:** France

## 🔗 Links

- [Portfolio](https://jimmydev-portfolio.netlify.app)
- [Instagram](https://www.instagram.com/jichegi.dev)
