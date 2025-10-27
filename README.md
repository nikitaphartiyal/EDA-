Titanic Dataset Analysis

This project analyzes the Titanic dataset using Python, Pandas, and Seaborn. The objective is to explore relationships between variables and identify trends that influenced passenger survival.

The dataset contains 891 rows and 15 columns, including passenger details such as age, sex, class, fare, and survival status. Some columns like age, deck, and embarked have missing values.

The analysis includes:

Data exploration using describe(), info(), and value_counts() to understand dataset structure and missing data.

Visualization using pairplot() and heatmap() to identify relationships and correlations.

Additional plots including histograms, boxplots, and scatterplots to explore distributions and survival patterns.

Key Observations:

Survival rate is approximately 38%.

Females had a much higher survival rate than males.

First-class passengers survived more often than those in third class.

Younger passengers and children had better survival chances.

Higher fare values were associated with higher survival.

There is a positive correlation between fare and survival, and a negative correlation between class and survival.

Most passengers were between 20 and 40 years old.

1st class fares had higher median and larger variation compared to 2nd and 3rd classes.

Summary:
Survival was strongly related to socio-economic status (class and fare), gender, and age. Wealthier passengers, women, and children had higher chances of survival. The dataset also shows that missing data in age, deck, and embarked columns needs to be addressed for deeper analysis.

This analysis demonstrates how exploratory data analysis (EDA) can uncover key patterns and relationships in real-world datasets using Python visualization tools.
