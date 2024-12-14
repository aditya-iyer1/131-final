# Predicting NFL Wins using Machine Learning

## Overview
This project aims to predict the outcome of NFL games (win/loss) based on a variety of game and team features. The primary objective is to identify the features that most strongly contribute to a team’s chances of winning.

Key features analyzed include:

Expected Points Added (EPA): A metric that evaluates the contribution of individual plays to a team's scoring potential.
Team performance metrics: Variables such as rushing attempts, passing yards, turnovers, and player efficiency.
EPA and related variables are particularly relevant because they offer a dynamic perspective on play effectiveness and overall team strategy. By leveraging these features, this project seeks to uncover meaningful insights into what drives team success.

The model's goal is to predict the binary outcome of a game (win or loss) while also highlighting the most significant factors influencing these predictions. To achieve this, multiple machine learning algorithms, such as random forests and logistic regression, will be employed.

### Evaluation Metrics
Models will be evaluated using metrics including:

Accuracy: Measures the percentage of correct predictions.
AUC-ROC: Assesses the model's ability to distinguish between wins and losses.
Other relevant measures to ensure robustness and fairness in performance assessment.
This project will not only focus on prediction accuracy but also on uncovering the key features influencing game outcomes. The findings will provide valuable insights for teams, analysts, and sports enthusiasts.

## Data Source
The data is sourced from the nflfastR package, a comprehensive resource for NFL play-by-play data. This package provides detailed, high-resolution data on:

Every play in NFL games.
Player and team performance metrics.
Game events, such as scores, penalties, and turnovers.

### Why nflfastR?

It is regularly updated and maintained by the nflfastR community.
The data includes valuable features like EPA, rushing attempts, and passing yards that are crucial for predictive modeling.
It is open-source and widely used in sports analytics, ensuring reliability and accessibility.
This rich dataset forms the foundation for developing predictive models and conducting in-depth analyses of NFL game outcomes.