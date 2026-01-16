# European Football Data Analysis (2002-2023)

## Project Overview
An exploratory data analysis of 20 years of European football matches, examining team performance, home advantage, and scoring patterns across Europe's top leagues and competitions.

## Dataset
**Source:** [Kaggle - European Soccer Data](https://www.kaggle.com/datasets/willfitzhugh/european-soccer-data)

# **Tools & Technologies**
- **Python**
- **pandas** - data manipulation and analysis
- **matplotlib** - data visualization
- **numpy** - numerical operations
- **Jupyter Notebook** - interactive analysis environment

# **Key Findings:**
- 106,876 match records (104,412 completed matches)
- 20 seasons (2002/2003 - 2022/2023)
- Leagues: England, Spain, Germany, Italy, France
- Competitions: Domestic leagues, domestic cups, UEFA Champions League, UEFA Europa League
- 1,936 teams tracked

# **Analysis Process**

### 1. Data Cleaning
- Removed 2,464 unplayed/placeholder matches
- Retained null values in extra time and penalty columns (indicating matches that didn't require them)
- Final dataset: 104,412 completed matches

### 2. Exploratory Data Analysis
Investigated patterns in:
- Home vs away performance by team
- Win distributions across countries and leagues
- Goal scoring patterns and distributions
- Home field advantage across teams

### 3. Visualizations Created
- Team win comparisons (home vs away)
- Country-level performance analysis
- Goal distribution (boxplot)
- Home advantage calculations

## Key Findings

### Team Performance
- **Barcelona** leads Europe with **422 home wins** (2002-2023)
- **Bayern Munich** has the most away wins with **323 victories**
- **Barcelona** ranks in the top 2 for both home and away wins, showing consistent excellence

### Home Advantage
- **Sevilla** has the biggest home advantage among all European teams
- Home teams demonstrate a clear performance boost compared to away fixtures

### League Analysis
- **England** recorded the most total wins (**8,378**) among all countries
- Reflects the volume and competitiveness of English football competitions

### Scoring Patterns
- Most matches are low-scoring affairs (as shown on the boxplot).
- Outliers exist with some matches featuring unusually high goal tallies
- Goal distribution shows football's typically conservative scoring nature

## Project Structure
```
├── Full_Dataset.csv          # Raw dataset
├── analysis.ipynb            # Jupyter notebook with full analysis
└── README.md                 # Project documentation
```

## Next Steps:
- Build predictive model for match outcomes (win/draw/loss prediction)

## Insights for Football Fans:
This analysis reveals that while elite clubs like Barcelona and Bayern dominate across contexts, **home advantage remains a significant factor** in European football. 
The consistency of top performers and the low-scoring nature of most matches highlight football's competitive balance and tactical nature.

## Contact
**Victory Kachidere Odumeh**  
[Github Link](https://github.com/pHanToMcaNCoDE) | [LinkedIn](https://www.linkedin.com/in/victory-kachidere-odumeh-421761223/) | [Email Address](victory.odumeh@gmail.com)

---
*This project was created as part of my data science portfolio to demonstrate data cleaning, exploratory analysis, and visualization skills.*
