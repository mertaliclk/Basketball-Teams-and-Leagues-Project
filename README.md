# Basketball Teams and Leagues Analysis Project

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.x-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0.24.x-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-green)

A comprehensive analysis of NBA teams and player performance, focusing on star players' impact on team success and efficiency metrics comparison.

## 📋 Overview

This project analyzes the relationship between star players' performance and team success in the NBA from 1999 to 2018. It introduces a novel "Player Point" metric and compares it with the NBA's official efficiency calculation method using machine learning approaches.

## 🎯 Project Goals

- Analyze the impact of star players on team success
- Develop and evaluate a new player efficiency metric
- Compare the new metric with NBA's official efficiency calculation
- Implement machine learning models to validate both approaches

## 📊 Key Features

- Custom "Player Point" metric calculation
- Star player identification for each team
- Championship and runner-up team analysis
- Machine learning model implementation (Decision Tree and Random Forest)
- Comparative analysis of efficiency metrics
- Data visualization and statistical analysis

## 🛠️ Technologies Used

- Python 3.x
- Pandas for data manipulation
- NumPy for numerical operations
- Scikit-learn for machine learning
- Matplotlib and Seaborn for visualization
- Jupyter Notebook for development

## 📈 Project Structure

1. **Data Collection and Preprocessing**
   - NBA player statistics (1999-2018)
   - Championship and runner-up team data
   - Data cleaning and feature engineering

2. **Star Player Analysis**
   - Identification of star players
   - "Player Point" calculation
   - Performance comparison between championship and runner-up teams

3. **Machine Learning Implementation**
   - Decision Tree Classifier
   - Random Forest Classifier
   - Model evaluation and comparison

4. **Results and Analysis**
   - Efficiency metric comparison
   - Model accuracy assessment
   - Visualization of findings

## 💻 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/basketball-analysis.git
cd basketball-analysis
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## 📊 Dataset Sources

1. Basketball Players Stats per Season (49 Leagues):
   - [Kaggle Dataset](https://www.kaggle.com/jacobbaruch/basketball-players-stats-per-season-49-leagues)

2. NBA Finals Team Stats:
   - [Kaggle Dataset](https://www.kaggle.com/daverosenman/nba-finals-team-stats)

## 🔍 Key Findings

- Star player performance analysis shows a 68% correlation with team success
- NBA's efficiency metric outperforms the custom "Player Point" metric
- Random Forest model achieves 94.9% accuracy with NBA's efficiency metric
- Decision Tree model shows 92.7% accuracy with NBA's efficiency metric

## 👤 Author

Mert Ali Celik


## 🙏 Acknowledgments

- NBA for providing comprehensive player statistics
- Kaggle for hosting the datasets
- Open-source community for their valuable tools and libraries
