# Google Search Trends Analysis with PyTrends

This project analyzes Google search interest over time and across countries using the PyTrends library, an unofficial Python API for Google Trends.

The goal is to explore how public interest changes over time for programming languages and political figures, and how search popularity differs by region.

<img width="567" height="432" alt="bc4964bd-0c99-4e5f-b676-ef0f85941326" src="https://github.com/user-attachments/assets/5b6664b3-bb16-4629-a314-058469be50d9" />

<img width="543" height="502" alt="3a7cd41f-8a55-463e-855e-4d8f9a25ec31" src="https://github.com/user-attachments/assets/80f7f7d1-e231-448a-a724-2d1ad69dffe2" />

<img width="543" height="500" alt="c5b52fea-1ad9-4c97-8a2d-cde425af6061" src="https://github.com/user-attachments/assets/78fd1fbe-508f-4731-a9ca-d946d0e763f6" />

## Project Overview

Using PyTrends, this project:

- Retrieves Google search interest data
- Compares multiple keywords over time
- Visualizes long-term and short-term trends
- Analyzes regional (country-level) search popularity
- Demonstrates real-world trend analysis using public data

This project is ideal for time-series analysis, data visualization, and social trend exploration.

## What Does This Data Represent?

Google Trends data shows relative search interest, not absolute search counts.

- Values range from 0 to 100
- 100 = peak popularity for the selected time and region
- Values are normalized by Google
- Data reflects how popular a term is compared to itself over time

This data does not represent the total number of searches.

## Technologies Used

- Python
- pandas
- matplotlib
- pytrends

## Installation

Install the required library:

```
pip install pytrends
```

## Analyses Performed

1. Programming Language Trends (5 Years)

Keywords analyzed:

- Python
- R
- C++
- Java
- HTML

Purpose:

Compare long-term popularity of programming languages and observe rising and declining trends over time.

2. Political Figure Trend Comparison (5 Years)

Keywords analyzed:

- Kilicdaroglu
- Erdogan

Purpose:

Compare public search interest between political figures and observe interest changes over long periods.

3. Short-Term Trend Analysis (12 Months)

Keywords analyzed:

- Murat Kurum
- İmamoğlu

Purpose:

Analyze recent search interest dynamics and capture short-term fluctuations.

4. Focused Keyword Comparison

Focused comparison between:

- Python
- C++

Purpose:

Highlight relative popularity between selected keywords and simplify trend comparison.

## Regional Interest Analysis

This project also analyzes search interest by country:

- Retrieves country-level interest data
- Identifies top 10 countries searching for "Python"
- Visualizes country-based popularity using bar charts
- Demonstrates data slicing and ranking

## Visualizations

The project includes:

- Line plots for trend analysis over time
- Comparative keyword plots
- Bar charts for country-level interest

All visualizations are created using matplotlib.
