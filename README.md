# 📊 Netflix Titles Data Analysis

This project explores the Netflix Titles dataset with a focus on data cleaning, descriptive analysis, and visualization. The dataset contains metadata for movies and TV shows available on Netflix, including details like title, director, cast, country, and more.

## 🧾 Project Objectives

- Identify and handle missing values
- Detect and remove duplicate entries
- Perform descriptive analysis
- Visualize key insights from the dataset

## 📁 Dataset

The dataset used in this project is [`netflix_titles.csv`](netflix_titles.csv), which includes the following columns:

| Column Name     | Description                                                       |
|------------------|-------------------------------------------------------------------|
| show_id          | Unique ID for every show                                         |
| type             | Indicates whether it's a Movie or TV Show                        |
| title            | Title of the content                                             |
| director         | Name of the director                                             |
| cast             | Names of the main actors                                         |
| country          | Country of production                                            |
| date_added       | Date when content was added to Netflix                           |
| release_year     | Release year of the content                                      |
| rating           | Age rating (e.g., PG, TV-MA)                                     |
| duration         | Duration in minutes or number of seasons                         |
| listed_in        | Genres/categories                                                |
| description      | Short summary of the content                                     |

## 📊 Analysis Overview

- 🔍 **Missing Values**:
  - Identify columns with missing data
  - Decide whether to fill, drop, or leave them as-is

- 📛 **Duplicates**:
  - Check for duplicate rows
  - Remove exact duplicates to maintain data integrity

- 📈 **Descriptive Statistics**:
  - Distribution of movies vs TV shows
  - Top genres and categories
  - Content added per year
  - Country-wise distribution
  - Common ratings

- 📉 **Visualizations**:
  - Bar charts, pie charts, and line plots using `Matplotlib` and `Seaborn`
  - Time-based trends
  - Heatmaps for correlation (if applicable)

## 🛠️ Tools & Libraries

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

