NCAA Football Network Predictor

Can team rankings predict which games land on the biggest networks?

In sports advertising, broadcast network matters enormously - a game on ESPN commands far higher CPMs than one on CBSSN. The problem: ad inventory is often sold before network assignments are confirmed, which means analysts must estimate a game's value from what they do know: the teams.
This project builds a logistic regression model that predicts the probability of a college football game airing on a major network (ESPN, FOX, ABC, or TNT) using AP Top 25 rankings as features.
Data Sources

Game schedule & broadcast data: ESPN public API (site.api.espn.com)
Team rankings: ESPN AP Top 25, Week 15 (2024 season)

Features Used

Home team rank
Away team rank
Average rank of both teams
Best (lowest) rank in the matchup

Tech Stack: Python, pandas, scikit-learn, matplotlib, ESPN API
Key Finding: There is a clear, statistically meaningful relationship between team ranking and major-network placement. The model produces per-game probability scores that can directly inform pre-sale pricing decisions.
