🌍 Global Population Data Analysis & Visualization (1960–2024)

This project performs an end-to-end analysis and visualization of global population trends using the World Bank Total Population dataset. It covers data loading, preprocessing, exploratory data analysis (EDA), visualization, and statistical summarization to uncover long-term demographic patterns across countries and regions.

📌 Project Overview

Domain: Data Science / Data Analysis

Dataset Source: World Bank Open Data

Indicator: SP.POP.TOTL (Total Population)

Time Span: 1960–2024

Countries & Regions: 265

Total Records (Cleaned): 17,195

🎯 Objectives

Analyze global population growth over six decades

Identify the most populous countries in recent years

Study population distribution across nations

Compare population growth trends of major countries

Generate clean, reusable datasets and high-quality visualizations

📁 Dataset Description

File Used: API_SP.POP.TOTL_DS2_en_csv_v2.csv

Original Shape: 266 rows × 70 columns

Key Fields:

Country Name

Country Code

Year

Population

Metadata rows were skipped, and the dataset was reshaped for time-series analysis.

🛠️ Tools & Technologies
Programming & Libraries

Python

Pandas – Data loading, cleaning, transformation

NumPy – Numerical operations

Matplotlib – Data visualization

Seaborn – Statistical plotting

Environment

IDE: Jupyter Notebook

Version Control: Git & GitHub

🔄 Workflow & Methodology
1️⃣ Data Loading & Exploration

Imported required libraries and configured plotting styles

Loaded CSV data while handling metadata rows

Inspected dataset structure, columns, data types, and missing values

2️⃣ Data Reshaping & Cleaning

Extracted year-wise columns (1960–2024)

Converted data from wide format to long format using pd.melt()

Converted data types for numerical accuracy

Removed rows with missing population values

Result: Clean dataset with 4 columns and 17,195 rows

📊 Exploratory Data Analysis & Visualizations
📈 Global Population Trend

Line plot showing total population growth from 1960 to 2024

Reveals sustained growth with gradual slowing in recent years
<img width="3661" height="1648" alt="global_population_trend" src="https://github.com/user-attachments/assets/71968721-8c5f-4039-9490-09f1d1d39d3a" />


🏆 Top 10 Most Populous Countries

Horizontal bar chart for the latest year (2024)

Highlights dominance of a few highly populated nations
<img width="3458" height="2110" alt="top10_countries" src="https://github.com/user-attachments/assets/450cd820-738f-4acb-901b-9b79cf2a49d4" />


📉 Population Distribution

Histogram showing population spread across countries

Demonstrates a highly right-skewed distribution
<img width="3011" height="1648" alt="population_distribution" src="https://github.com/user-attachments/assets/36d6df06-68f1-4a98-b1e0-5e3262aa01de" />


🌐 Country-wise Comparison

Multi-line chart comparing population growth of:

India

China

United States

Indonesia

Brazil
<img width="3638" height="1879" alt="country_comparison" src="https://github.com/user-attachments/assets/9717cf19-dbdb-4ade-8640-24762294f176" />


📌 Key Insights

Global Population (1960): ~30.4 billion (aggregated regions included)

Global Population (2024): ~87.9 billion (aggregated regions included)

Overall Growth: ~189% increase

Population Distribution:

Median country population is far lower than the mean

Majority of countries have relatively small populations

Growth Trends:

India shows rapid growth in recent decades

Developed nations exhibit steady, slower growth

📑 Statistical Summary (Latest Year)

Total Countries/Regions: 265

Years Covered: 1960–2024

Average Country Population: ~331 million

Median Country Population: ~10.8 million

Largest Entity: World (aggregated region)

💾 Output Files

Cleaned Dataset:

data/processed/population_cleaned.csv


Saved Visualizations:

global_population_trend.png

top10_countries.png

population_distribution.png

country_comparison.png

Github respository - https://github.com/adityapatil2005/PRIDOGY_TASK01/edit/main

