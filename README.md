##  Video Game Sales Analysis

A data exploration and visualisation project examining global video game sales across different genres, platforms, regions, and years.

### Overview

This project investigates trends in the video game industry by analysing historical sales data. It explores:

- Global sales trends over time  
- Sales performance by region  
- Sales performance by genre  
- Sales performance by platform  
- Top 5 publishers  
- Publisher and genre sales trends  
- Top 10 games by sales  
- Genre trends over time  

### Dataset

- Source: [Kaggle - Video Game Sales Dataset](https://www.kaggle.com/datasets/gregorut/videogamesales)

### Tools & Libraries

- **Python**
- **Pandas** for data cleaning and manipulation
- **Seaborn** & **Matplotlib** for data visualisation
- **Jupyter Notebook** for analysis

### Cleaning Steps

- Filled missing `Publisher` values with 'Unknown'.
- Filled missing `Year` values with 0.
- Created a cleaned copy by dropping rows where Year == 0, Year == 2017, and Year == 2020 for time plot analysis. The years 2017 and 2020 were removed because, compared to historic sales, their data is incomplete and would not provide a clear picture of sales trends over time.

### Visuals Included

- Line chart showing total sales over time  
- Bar chart showing sales by region  
- Line chart showing regional sales trends over years  
- Bar chart showing sales by genre  
- Bar chart showing sales by platform  
- Bar chart showing top 5 publishers  
- Heatmap showing sales by publisher and genre  
- Bar chart showing top 10 games  
- Heatmap showing genre trends over time  

###  Key Findings

| **KPI**                       | **Value**           |
|-------------------------------|---------------------|
| Top Selling Game              | Wii Sports          |
| Top Publisher                 | Nintendo            |
| Most Popular Platform         | PS2                 |
| Most Popular Genre (All Time) | Action              |
| Sales Trend Post 2010         | Declining           |
| Highest Region                | North America       |

### How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/Tariba/video-game-sales-analysis.git
2. Install the necessary Python Libraries:
- Pandas 
- Matplotlib 
- Seaborn 
- Jupyter

you can install them using the following command:

   ```bash
  pip install pandas matplotlib seaborn jupyter
```
3. Open the Jupyter Notebook file (games_sales_analysis.ipynb) to explore the analysis.