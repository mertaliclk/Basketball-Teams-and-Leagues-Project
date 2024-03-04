# Basketball Teams and Leagues Analysis Project

### Overview
In basketball leagues, teams often have star players who play a crucial role in their success. This project aims to examine the success of a team in a basketball league based on the performance of its star players compared to other teams.

### Methodology
Efficiency Score Calculation: The efficiency score was calculated using the formula:
     Efficiency = (FGM x 2) + (3PM x 3) / (FGA x 2) + (3PA x 3)

Data Analysis: NBA player data was used to calculate efficiency scores and identify players exceeding the average efficiency.

Machine Learning Models: Decision Tree and Random Forest algorithms were used to compare the efficiency scores calculated in this project with the NBA's current efficiency calculation method.

Feature Comparison: Features used in this project's efficiency score calculation: FGM, FGA, 3PM, 3PA. Features used in NBA's efficiency calculation: PTS, REB, AST, STL, BLK, FGA, FGM, FTA, FTM, TO.

### Results
Decision Tree: Accuracy of 50.0% for this project's efficiency calculation method compared to 92.7% for NBA's method.

Random Forest: Accuracy of 54.3% for this project's method compared to 94.9% for NBA's method.

### Conclusion
Random Forest Algorithm outperformed Decision Tree Algorithm in both calculations.
NBA's efficiency calculation method is more comprehensive due to the use of additional features.

