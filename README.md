# BAN6420-Module-4-Assignment-Netflix-Data-Visualization
Netflix Data Visualization

# Netflix Data Analytics Project

This project provides insights into Netflix's movies and shows using Python and R. It covers data preparation, cleaning, exploration, and visualization to uncover key trends such as content ratings and genre popularity.

## 📁 Project Structure

netflix-data-analytics/
├── netflix_analysis Python.ipynb # Jupyter notebook (Python)
├── netflix_analysis R.ipynb # R script for Ratings Distribution in Jupyter notebook
├── README.md # Project documentation

## 🧩 Requirements

### Python Packages:
- pandas
- matplotlib
- seaborn
- zipfile
- numpy

To install all dependencies, run:

```bash
pip install pandas matplotlib seaborn numpy

R Packages to install:
ggplot2
viridis
dplyr
readr

Features Implemented
Data unzipping and renaming
Missing value treatment

"Unknown" used for director and cast

Mode imputation for rating, country, date added

Descriptive analysis and statistics

Visualizations using matplotlib, seaborn, and ggplot2 to show:

1. Distribution of ratings
2. Most watched genres

Sample Visualizations that were displayed:

Ratings Distribution Bar Plot (Python & R)
Genre Popularity Pie Chart (Python)

HOW TO RUN

In Python:
Unzip the dataset and rename it:

import zipfile
with zipfile.ZipFile("Netflix_Dataset.zip", 'r') as zip_ref:
    zip_ref.extractall()

Load and clean the data:

import pandas as pd
df = pd.read_csv("netflix_data.csv")

Run the PYTHON notebook netflix_analysis.ipynb for:

Missing value handling
Data exploration and description
Visualizations (e.g., Ratings Distribution, Most Watched Genres)

In R:
Run visualization_plot.R to generate a content rating bar chart using ggplot2.






