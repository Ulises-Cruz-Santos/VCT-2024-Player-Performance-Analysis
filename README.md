# Valorant Champions Tour 2024 Player Performance Analysis

## Overview
This project analyzes the performance metrics of players participating in the Valorant Champions Tour 2024. The analysis includes various aspects of player performance, such as overall ratings, damage and elimination stats, accuracy indicators, and match highlights. The goal is to uncover insights and trends that can inform teams and players on how to improve their performance.

## Table of Contents
- [Project Motivation](#project-motivation)
- [Dataset Description](#dataset-description)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Advanced Analysis](#advanced-analysis)
- [Predictive Modeling](#predictive-modeling)
- [Visualizations](#visualizations)
- [Results and Insights](#results-and-insights)
- [How to Use This Repository](#how-to-use-this-repository)
- [Dependencies](#dependencies)
- [License](#license)

## Project Motivation
The Valorant Champions Tour is a premier esports event, and analyzing player performance can provide valuable insights for teams, players, and analysts. This project aims to:
- Identify top-performing players and teams.
- Uncover key performance metrics that correlate with success.
- Provide actionable insights for performance improvement.

## Dataset Description
The dataset includes detailed performance metrics for players in the Valorant Champions Tour 2024, capturing a wide range of indicators:

### Basic Information:
- Event Name (Event)
- Player Name (Player)
- Team Name abbreviation (Team Abbreviated)
- Team Name complete (Team Complete)
- Rounds Played (Rnd)

### Overall Performance Metrics:
- Rating (R)
- Average Combat Score (ACS)
- Kill:Death Ratio (K:D)
- Kill, Assist, Survive, Trade Percentage (KAST)

### Damage and Elimination Stats:
- Average Damage per Round (ADR)
- Kills per Round (KPR)
- Assists per Round (APR)
- First Kills per Round (FKPR)
- First Deaths per Round (FDPR)

### Accuracy and Skill Indicators:
- Headshot Percentage (HS%)
- Clutch Success Percentage (CL%)
- Clutches Won/Played (CL)
- Clutches Won (CW)
- Clutches Played (CP)

### Match Highlights:
- Maximum Kills in a Single Map (KMax)

### Aggregate Statistics:
- Total Kills (K)
- Total Deaths (D)
- Total Assists (A)
- Total First Kills (FK)
- Total First Deaths (FD)

## Data Preprocessing
The dataset was cleaned and preprocessed to handle missing values, standardize formats, and normalize data for analysis. See [notebooks/01_data_cleaning.ipynb](notebooks/01_data_cleaning.ipynb) for details.

## Exploratory Data Analysis (EDA)
An initial exploration of the dataset was conducted to understand the distribution of key metrics and identify patterns. Visualizations and summary statistics are provided in [notebooks/02_eda.ipynb](notebooks/02_eda.ipynb).

## Advanced Analysis
Further analysis includes correlation studies, cluster analysis, and time series analysis to uncover deeper insights. Details can be found in [notebooks/03_advanced_analysis.ipynb](notebooks/03_advanced_analysis.ipynb).

## Predictive Modeling
Predictive models were built to forecast player performance in future events. Model training, evaluation, and results are documented in [notebooks/04_modeling.ipynb](notebooks/04_modeling.ipynb).

## Visualizations
Interactive dashboards and visualizations are available to explore the data and findings. See the visualizations folder for images and links to dashboards.

## Results and Insights
Key findings and actionable insights are summarized in the final report. The full analysis and recommendations are available in [results/final_report.pdf](results/final_report.pdf).

## How to Use This Repository
1. Clone the repository: `git clone https://github.com/yourusername/valorant-performance-analysis.git`
2. Navigate to the project directory: `cd valorant-performance-analysis`
3. Install dependencies: `pip install -r requirements.txt`
4. Explore the notebooks: Open Jupyter notebooks in the `notebooks` folder.
5. View visualizations: Explore plots and dashboards in the `visualizations` folder.

## Dependencies
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook

Install dependencies using the provided `requirements.txt` file.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
