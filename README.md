# 3250 Data Wrangling MLB Project

## Overview

This project analyzes hitting performance in Major League Baseball (MLB) using data combined from two sources: **RotoWire** and **ESPN.com**. The main objective is to explore how **years of experience**, **games played**, and **player position** influence three key performance metrics: **batting average**, **home runs**, and **on-base percentage**.

I was inspired to take on this analysis because of my personal connection to baseball—my boyfriend is currently playing at the Division I level with aspirations of entering the MLB draft. His in-depth knowledge of the sport helped me better understand the nuances of player roles, team dynamics, and the statistics behind performance.

## Project Structure
MLB-Data-Wrangling-Project/
│
├── Data/
│ ├── rotowire_data.csv # Downloaded player stats
│ ├── espn_scraped_data.csv # Scraped player info (experience, etc.)
│ └── links.txt # URLs for both sources
│
├── Notebooks/
│ ├── scraping_notebook.ipynb # Scraping ESPN data
│ ├── full_analysis_notebook.ipynb # Data cleaning, merging, and analysis
│ └── README.md # Explanation of contents
│
├── Results/
│ └── Elmore - Data Wrangling Project Report.pdf # Final project report
│
└── README.md # Project overview (this file)
## Key Questions Explored

1. **How does years of MLB experience affect batting average and home runs?**
2. **Do performance metrics differ by field position?**
3. **Does playing time (games played) correlate with improvements in batting average and on-base percentage?**

## Findings

- **Experience**: No significant correlation was found between years of experience and batting average or home runs.
- **Position**: Designated hitters (DH) and first basemen had the highest batting averages and home run totals.
- **Playing Time**: Players who appeared in more games generally had slightly higher batting averages and on-base percentages, possibly due to increased rhythm and familiarity with pitchers.

## Tools & Libraries

- **Python**
- **Pandas**, **NumPy** – data manipulation
- **BeautifulSoup** – web scraping ESPN
- **Matplotlib**, **Seaborn** – data visualization
- **Jupyter Notebook**

## How to Use

1. Open `scraping_notebook.ipynb` in the **Notebooks** folder to see how player experience data was scraped from ESPN.
2. Open `full_analysis_notebook.ipynb` to review the data cleaning, merging, and analysis process.
3. Check the **Results** folder for the final report summarizing all findings with visuals and interpretation.
4. Refer to the **Data** folder for both original and processed datasets.

## Future Work

- Add multi-season data to analyze long-term trends.
- Include player **age**, **injury history**, and **advanced metrics** (e.g., WAR).
- Compare with pitching stats or include defensive performance.

---
