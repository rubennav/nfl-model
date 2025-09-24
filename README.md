# NFL-Betting-Analysis
## Project Overview
Built a fully functional NFL betting simulation program in Excel that models MoneyLine, spread, and over/under outcomes using historical data, advanced probability, scenario analysis, and 5,000+ iteration simulations.
The workbook simulates 272 games across the 2023–2024 NFL seasons, generating over 1.3 million score outcomes and actionable win probabilities. It transforms Excel into a predictive analytics tool comparable to professional sports betting software.

## Key Contributions
• End-to-End Data Pipeline: Collected, cleaned, and transformed NFL datasets from 2023–2024 seasons (team stats, field goals, schedules, standings) using Power Query.

• Custom Simulation Engine: Built a 5,000-iteration probabilistic model using LET, BINOM.INV, XLOOKUP, SUMPRODUCT, DROP, IF, SUMIF, IFERROR, and array formulas to simulate touchdowns, field goals, 2-point conversions, and overall game flow.

• Predictive Metrics & Insights: Engineered metrics including Strength of Schedule, home-field adjustments (10% advantage), game flow predictions, and confidence scores for betting reliability.

• Dynamic Dashboards: Created user-friendly dashboards for upcoming games, showing simulated odds, projected scores, spreads, moneyline, total points, and win probabilities.

Example:
Ravens vs Chargers — Predicted score: 26.49 to 26.99, Chargers 51.54% win probability.

## Dashboard Features
Team Selection: Dropdowns for selecting Home and Away teams. Automatically updates all simulations.
Score & Win Probability: Displays projected scores and win chances for both teams.
Betting Lines:
    • Spread: Predicted point differential
    • Moneyline: Simulated win odds
    • Total Points (Over/Under): Expected total score
Game Range Filter: Select a date range to populate all upcoming games.
Upcoming Games Table: Lists all games within the selected range with simulated results and betting lines.
User-Friendly Design: Interactive slicers, numeric and percentage views, optimized for quick decision-making.

## Data Sources
All datasets are publicly available:
- [NFL.com Offensive Stats 2024](https://www.nfl.com/stats/team-stats/offense/scoring/2024/reg/all)
- [NFL.com Defensive Receiving Stats 2024](https://www.nfl.com/stats/team-stats/defense/receiving/2024/reg/all)
- [NFL.com Defensive Rushing Stats 2024](https://www.nfl.com/stats/team-stats/defense/rushing/2024/reg/all)
- [NFL Standings](https://www.nfl.com/standings/)
- [Pro-Football-Reference 2023–2024 Games](https://www.pro-football-reference.com/years/2024/games.htm)
- [Stathead Drive Finder](https://stathead.com/football/drive_finder.cgi?request=1&year_min=2023&year_max=2023)

> Note: Data is publicly sourced. GitHub does not host these files; download directly from the provided links.

## Workbook Sheets Overview
2023 NFL Data – Raw team and game data
2024 NFL Data – Raw team and game data
NFL Standings – Season rankings and records
Game(s) Data – All game-level statistics
Team Ratings – Calculated metrics for offense and defense
Strength of Schedule – Weighted difficulty metrics
Team Map – Visual representation of teams and locations
Miscellaneous Stats – Supplemental constants used in simulations
Simulation – 5,000+ iteration probabilistic engine
Dashboard – Interactive results with betting analytics
