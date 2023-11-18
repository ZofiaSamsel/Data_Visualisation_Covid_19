# Data Visualisation Homework

This repository contains a Jupyter notebook showcasing data analysis and visualization of Covid-19 data using Python. The goal is to provide insights into the pandemic's impact by employing various visualization techniques. The notebook utilizes the `owid-covid-data.csv` dataset from Our World in Data and employs Python libraries such as matplotlib, seaborn, geopandas, and bar_chart_race.

## Instructions

### Download the Data:

The notebook uses the Covid-19 dataset from [owid/covid-19-data](https://github.com/owid/covid-19-data). Ensure you have internet access to fetch the data.

### Install Required Libraries:

Execute `!pip install bar_chart_race` to install the necessary libraries.

### Run the Notebook:

Open the Jupyter notebook (`Data_Visualisation_Homework.ipynb`) and execute each cell to visualize the data.

## Data Cleaning

The notebook starts with data cleaning steps, including column selection, creation of new columns for weekly and yearly summaries, removal of invalid locations, and handling NaN values appropriately.

## Visualizations

1. **Total Cases and Vaccinations in European Countries**
   - Bar plot comparing total cases and fully vaccinated percentages.

2. **Total Cases vs GDP Per Capita**
   - Scatter plot exploring the relationship between total cases and GDP per capita.

3. **New Cases and Deaths in Poland (Jan 2020 - Nov 2023)**
   - Dual-axis line plot illustrating daily new cases and deaths in Poland.

4. **Worldwide Total Cases (Nov 2023) - World Map**
   - Choropleth map depicting total Covid-19 cases worldwide.

5. **Total Cases in Different Countries (Jan 2020 - Nov 2023, Monthly)**
   - Line plot showcasing cumulative Covid-19 cases in selected countries.

6. **Total Deaths by European Country - Bar Chart Race**
   - Animated bar chart race illustrating the evolution of total deaths in European countries.

## Why These Visualizations?

Each visualization is chosen to address specific aspects of the Covid-19 dataset, providing insights into regional patterns, economic correlations, temporal trends, and global distribution of cases and deaths.
