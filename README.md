# Fifa-EDA-
Comprehensive Exploratory Data Analysis (EDA) of FIFA Player Statistics using Python. This project uncovers insights into player performance, valuation, age demographics, and club rankings using Seaborn, Matplotlib, and Pandas.

# FIFA Player Data - Exploratory Data Analysis (EDA) ⚽📊

## Project Overview
This project performs an in-depth Exploratory Data Analysis on the FIFA dataset to understand the attributes that define professional football players. The analysis covers player demographics, performance metrics (Overall vs. Potential), financial valuations, and club-level statistics.

The goal is to provide data-driven insights into how age, nationality, and position influence a player's market value and skill set.

## Dataset Features
The dataset includes 18,000+ players with 18 key attributes:
- **Demographics:** Name, Age, Nationality, Club.
- **Performance:** Overall Rating, Potential, Skill Moves, Preferred Foot.
- **Financials:** Value, Wage, Release Clause.
- **Physicals:** Height, Weight, Position.

## Project Workflow

### 1. Data Cleaning & Preprocessing
- Handled missing values in `Club`, `Value`, and `Release Clause`.
- Conducted duplicate checks and data type conversions.
- Visualized missing data patterns using the `missingno` library.

### 2. Univariate Analysis
- Analyzed the distribution of player ages and ratings.
- Identified top-contributing nationalities (England, Germany, Spain).

### 3. Bivariate & Multivariate Analysis
- **Age vs. Rating:** Explored how player ratings peak around age 30.
- **Value vs. Wage:** Visualized the correlation between a player's market value and their weekly salary.
- **Feature Correlation:** Generated a heatmap to see how physical attributes relate to overall performance.

### 4. Key Insights
- **Top Performers:** Identified the highest-rated players (e.g., Cristiano Ronaldo, L. Messi).
- **Club Rankings:** Determined the top clubs based on average player ratings (e.g., Juventus, FC Barcelona).
- **Growth Prospects:** Calculated "Potential Growth" to identify the best young players for long-term investment.

## Technologies Used
- **Python** (Core Analysis)
- **Pandas & NumPy** (Data Manipulation)
- **Matplotlib & Seaborn** (Data Visualization)
- **Missingno** (Missing Data Visualization)

