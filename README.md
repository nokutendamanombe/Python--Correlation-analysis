# Movie Performance Analysis Project

This repository contains a Python-based data analysis project exploring factors influencing the gross revenue of movies. The analysis focuses on uncovering trends and relationships between key variables such as budget, production company, and other movie attributes.

## Overview
The primary objective of this project was to test the hypothesis:
- **Budget is positively correlated with gross revenue.**
- **Production company plays a significant role in determining movie success.**

Using a dataset of movie performance, the analysis reveals insights through data cleaning, transformation, and visualization techniques.

## Features
1. **Data Cleaning**:
   - Removed null values and duplicate entries.
   - Fixed data types for numerical consistency.
   - Encoded categorical variables for correlation analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Calculated correlation coefficients to identify key factors influencing gross revenue.
   - Focused on budget and production company alongside other attributes such as runtime, rating, and genre.

3. **Data Visualization**:
   - Bar plots showcasing feature correlations with gross revenue.
   - Scatter plots with regression lines to display relationships (e.g., budget vs. gross revenue).
   - Heatmaps for correlation matrix visualization.

## Key Insights
- **Budget**: Strong positive correlation (ρ = 0.74) with gross revenue.
- **Production Company**: Moderate positive correlation (ρ = 0.15), indicating some influence on revenue.
- Other features, such as votes and runtime, also showed significant but smaller correlations.

## Tools & Libraries
- **Python**: Core programming language for the analysis.
- **Pandas**: Data cleaning and manipulation.
- **Seaborn & Matplotlib**: Visualizations to communicate findings effectively.
- **NumPy**: Numerical operations.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/movie-performance-analysis.git
