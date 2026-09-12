# Moneyball-DecisionScience
The Mathematics of Knowing When to Act: From the 37% Rule to Agentic AI.
# Moneyball Scout Agent — Microsoft Fabric demo

Files:
- moneyball_historical_players.csv — synthetic labeled training data
- moneyball_incoming_prospects.csv — 100 sequential candidates to score
- Moneyball_37Percent_AgenticAI_Fabric.ipynb — Fabric-ready notebook

Demo goal:
Train a classifier, score incoming candidates, apply the secretary-problem 1/e stopping threshold, persist decisions to a Lakehouse, and ground a Fabric Data Agent on the resulting tables.

The data is synthetic and is intended for education/demo use, not real scouting.
