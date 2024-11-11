# Video Game Sales EDA

This project provides an exploratory data analysis (EDA) of the **Video Game Sales Dataset** (`vgsales.csv`). The dataset contains information on video game sales, including sales across different regions, the year of release, the platform, genre, and publisher details.

## Table of Contents

- [About the Dataset](#about-the-dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [EDA Overview](#eda-overview)
- [Visualization Examples](#visualization-examples)
- [Dependencies](#dependencies)

---

## About the Dataset

The dataset (`vgsales.csv`) includes the following columns:

- **Rank**: Ranking of overall sales
- **Name**: Name of the game
- **Platform**: Platform of release (e.g., Wii, NES, GB)
- **Year**: Year of release
- **Genre**: Genre of the game (e.g., Action, Sports)
- **Publisher**: Publisher of the game (e.g., Nintendo, Ubisoft)
- **NA_Sales**: Sales in North America (in millions)
- **EU_Sales**: Sales in Europe (in millions)
- **JP_Sales**: Sales in Japan (in millions)
- **Other_Sales**: Sales in other regions (in millions)
- **Global_Sales**: Total worldwide sales (in millions)

## Project Structure

- **EDA Code**: Python code that performs EDA on the dataset, including data visualization and analysis.
- **vgsales.csv**: Dataset file with video game sales data (you'll need to add this to your working directory).

## Installation

1. **Clone this repository** or download the code files.
2. **Install the required dependencies** by running:

   ```bash
   pip install pandas matplotlib seaborn
   ```

3. **Download the dataset** (`vgsales.csv`) and place it in the same directory as the code file.

## Usage

1. **Load the Jupyter Notebook or Python script**.
2. **Run each code cell** in sequence to execute the EDA process.
3. The results will be displayed as tables, prints, and plots that provide insights into the dataset.

## EDA Overview

The EDA explores the `vgsales.csv` dataset through the following steps:

1. **Dataset Overview**: Displays basic information, null values, and data types.
2. **Statistical Summary**: Summarizes descriptive statistics for numerical data.
3. **Sales Distribution**: Histograms showing the distribution of sales across different regions.
4. **Top Publishers by Global Sales**: Bar chart displaying the top 10 publishers.
5. **Sales Trend Over Years**: Line chart showing global sales by year.
6. **Genre Distribution**: Count plot showing the distribution of game genres.
7. **Platform Analysis**: Analysis of the top 10 platforms by global sales.
8. **Correlation Analysis**: Heatmap showing correlations between regional sales.

## Visualization Examples

The EDA generates the following types of visualizations:

- **Histograms** of sales data for different regions.
- **Bar charts** for top publishers and platforms by sales.
- **Line plot** for yearly global sales trends.
- **Count plot** for genre distribution.
- **Heatmap** to visualize correlations between different sales regions.

## Dependencies

- **Python** 3.6+
- **pandas**
- **matplotlib**
- **seaborn**
