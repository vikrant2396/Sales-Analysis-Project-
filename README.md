# Australian Apparel Sales Analysis

Data analysis project for AAL (Australian Apparel Limited) analyzing Q4 2020 sales across Australia to support expansion decisions.

## Overview

AAL is a clothing retailer serving Kids, Women, Men, and Seniors across 7 Australian states. This project analyzes sales data to identify high-performing states and recommend strategies for revenue growth.

## Dataset

- **Records**: 7,560 transactions
- **Period**: October - December 2020
- **States**: WA, NT, SA, VIC, QLD, NSW, TAS
- **Customer Groups**: Kids, Women, Men, Seniors
- **Time Periods**: Morning, Afternoon, Evening

## Project Goals

1. Identify states generating highest/lowest revenues
2. Determine best-performing customer groups
3. Analyze sales patterns by time of day
4. Recommend targeted sales strategies

## Installation

```bash
pip install pandas numpy matplotlib seaborn jupyter scipy
```

## Usage

```bash
jupyter notebook Sales_Analysis.ipynb
```

## Analysis Pipeline

### 1. Data Wrangling
- Check for missing values
- Clean and normalize data
- Group data by State, Group, and Time

### 2. Data Analysis
- Descriptive statistics (mean, median, std)
- State-wise revenue analysis
- Customer group performance
- Time-of-day patterns

### 3. Data Visualization
- State-wise sales by customer group
- Group-wise sales across states
- Time-of-day analysis
- Daily, weekly, monthly trends
- Box plots for statistical overview

### 4. Report Generation
- Jupyter notebook with markdown
- Statistical plots using Seaborn
- Insights and recommendations

## Key Visualizations

- **State Performance**: Bar charts comparing sales across states
- **Customer Segments**: Group-wise revenue breakdown
- **Time Analysis**: Sales patterns throughout the day
- **Trends**: Daily, weekly, and monthly sales charts
- **Statistics**: Box plots and distribution plots

## Technologies Used

- **Python 3.8+**
- **Pandas** - Data manipulation
- **NumPy** - Numerical analysis
- **Seaborn** - Statistical visualization
- **Matplotlib** - Plotting
- **Jupyter** - Interactive analysis

## Project Structure

```
├── Sales_Analysis.ipynb
├── AusApparalSales4thQrt2020.csv
└── README.md
```

## Key Findings

**High-Revenue States**: VIC, NSW (metropolitan markets)  
**Low-Revenue States**: NT, TAS (smaller populations)  
**Sales Patterns**: Identified peak and off-peak hours  
**Customer Insights**: Revenue by demographic segment

## Recommendations

**For High-Revenue States**:
- Expand store presence
- Premium product lines
- Loyalty programs

**For Low-Revenue States**:
- Targeted promotional campaigns
- Bundle offers and discounts
- Local partnerships

**Time-Based Strategies**:
- Schedule promotions during low-traffic hours
- Optimize staffing for peak times
- Flash sales during off-peak periods

---

