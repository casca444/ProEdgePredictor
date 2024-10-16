# ProEdgePredictor
ProEdgePredictor is a machine learning-driven sports betting model for MLB, NFL, and NBA. It integrates real-time data like odds, player stats, and weather to predict outcomes and identify value bets. Built with XGBoost, it leverages public betting trends and player metrics to optimize betting strategies.

ProEdgePredictor offers a powerful betting tool for three major sports: MLB, NFL, and NBA. By utilizing data-driven machine learning techniques, the model focuses on finding value betting opportunities, with particular emphasis on:

Contrarian Betting: Identifying bets where public sentiment heavily favors one side.
Underdog Performance: Analyzing trends when betting on underdogs in high-scoring or spread-heavy games.
Player and Team Metrics: Incorporating advanced statistics such as ERA, PER, and Quarterback Efficiency.
Weather Conditions: Considering the effects of weather on performance in MLB and NFL.
The project is powered by XGBoost, which is trained on historical game data, allowing the model to make informed, data-driven betting predictions.

Key Features
Cross-sport support for MLB, NFL, and NBA, each with customized metrics for accurate predictions.
Real-time data integration from APIs for odds, public betting percentages, weather, and player stats.
Contrarian and Underdog Analysis to identify high-value bets.
Performance tracking with built-in tools to log and analyze betting results.
Weather impact assessment for MLB and NFL games to optimize total bets.


APIs Used
ProEdgePredictor relies on the following APIs to gather real-time data:

OddsAPI: Retrieves real-time odds and public betting percentages.
OddsAPI Documentation
OpenWeatherMap: Provides real-time weather data for games, essential for MLB and NFL predictions.
OpenWeatherMap Documentation
Fangraphs/Baseball Reference: Used to pull detailed baseball player and team statistics.
Fangraphs
Pro Football Reference: NFL player performance data like quarterback stats and defensive efficiency.
Pro Football Reference
Basketball Reference: NBA player and team efficiency metrics.
Basketball Reference
Model Architecture
The core of ProEdgePredictor is built on XGBoost, which is used to train separate models for MLB, NFL, and NBA predictions. Each sport has its own set of features that feed into the model:

MLB: Starting pitcher stats (ERA, WHIP), weather conditions, public betting percentages.
NFL: Quarterback efficiency, team offense/defense, weather conditions.
NBA: Player efficiency ratings (PER), pace, injuries.
The model outputs a predicted probability for each team’s likelihood of winning, which is then compared to the odds to identify value bets.

License
This project is licensed under the Apache License 2.0. You are free to use, modify, and distribute this software under the terms of the license. Please refer to the LICENSE file for more details.

