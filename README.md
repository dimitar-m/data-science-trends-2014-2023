# Data Science Stack Exchange Tag Analysis (2014–2023)

## Project Overview

This project analyzes trends in Data Science Stack Exchange (DSSE) posts from 2014 to 2023 to understand the popularity of data science topics over time. The focus is on identifying which tags, such as 'machine-learning,' 'python,' 'deep-learning,' and 'transformer,' have been most discussed and viewed.

## Key Objectives:
- **Identify Trends**: Determine the most popular data science topics (tags) and how they evolved from 2014 to 2023.
- **Examine Post Interaction**: Analyze views, usage, and the relationship between tags and community engagement (views, answers).
- **Visualization**: Provide clear visualizations of the data to highlight key trends and patterns.

## Methods & Techniques:
- **Data Extraction**: Used SQL queries to gather DSSE posts from 2014 to 2023, focusing on questions (PostTypeId = 1).
- **Data Cleaning**: Cleaned and prepared the data using Pandas, handling null values and splitting tag columns for further analysis.
- **Analysis**: Performed group-by operations to aggregate post data by year and tag, analyzing views and usage rates.
- **Visualization**: Created time-series plots with Seaborn to visualize the trends of each tag over time, identifying shifts in data science interests.

## Tools & Libraries Used:
- **Python** (Pandas, Seaborn, Matplotlib)
- **SQL** (Data extraction from DSSE database)
- **Jupyter Notebooks** (for development and analysis)

## Insights:
- The most used and viewed tags in 2023 revealed that foundational topics like Python, machine learning, and deep learning are consistently top interests.
- Emerging trends such as 'pytorch' and 'transformer' tags saw increasing attention, indicating the growing importance of advanced machine learning techniques.
  
## How to Use This Repository:
1. Clone or download the repository.
2. Run the Jupyter notebook to reproduce the analysis and visualizations.
3. Customize and adapt the code for your own analyses or data exploration.

## Conclusion:
This analysis offers insights into how the data science community’s interests have evolved, helping identify the most relevant and timely topics in the field. This project can also serve as a reference for anyone looking to understand the growing trends in data science.
