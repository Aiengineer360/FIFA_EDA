# FIFA Football Match Exploratory Data Analysis (EDA)

## Overview

This project provides an in-depth Exploratory Data Analysis (EDA) of football match data sourced from Kaggle. The dataset includes detailed information about matches, players, teams, and their attributes, allowing for a comprehensive analysis of various factors influencing match outcomes.

## Dataset

The dataset used in this project is available on Kaggle:
- [Soccer Dataset](https://www.kaggle.com/datasets/hugomathien/soccer)

## Project Structure

1. **Data Import and Preprocessing**:
   - Importing necessary libraries.
   - Downloading and converting the dataset from SQLite to CSV files.
   - Filtering relevant columns and creating a cleaned dataset.

2. **Data Analysis**:
   - Handling missing values and imputing numerical and categorical columns.
   - Calculating goal differences and defining match outcomes.
   - Preparing team and player data for further analysis.

3. **Visualizations**:
   - Histograms and boxplots for home and away team goals.
   - Correlation heatmaps to understand relationships between features and match results.
   - Seasonal trends in goals and home team win rates.
   - Analysis of team performance metrics such as defensive pressure, team width, and aggression.

4. **Insights**:
   - Identifying teams and players that consistently outperform others.
   - Analyzing the impact of different tournament types on match outcomes.

## Key Findings

- **Goal Difference and Match Results**: The goal difference between home and away teams is a strong indicator of match outcomes.
- **Seasonal Trends**: Certain months and seasons show higher goal counts and home team win rates.
- **Team Performance**: Teams with higher defensive pressure and aggression tend to have better win rates.

## Usage

To run this project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Aiengineer360/FIFA-Football-Match-EDA.git
   cd FIFA-Football-Match-EDA
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook FootBall-Match-EDA.ipynb
   ```

## Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- sqlite3

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

## Acknowledgments

- Kaggle for providing the dataset.
- The open-source community for their valuable libraries and tools.

## Contact

For any questions or feedback, please reach out to ai.engineer360@gmail.com
