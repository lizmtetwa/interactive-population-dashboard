# Interactive-population-dashboard
Interactive Population Dashboard: Multi-year analysis of top 20 most populous countries with interactive bar charts and treemaps.
# Interactive Population Dashboard

**Author:** Elizabeth Chambwinja  
**Email:** lizmtetwa@yahoo.co.uk  
**Location:** Fleet, United Kingdom

---

## Problem / Objective

The objective of this project is to analyze global population trends and visualize the **top 20 most populous countries** over multiple years. The project aims to provide insights into population growth, distribution, and changes over time.

---

## Data Source

- Source: [World Bank Population Data](https://datahub.io/core/population)  
- Dataset: `population.csv`  
- Columns: `Country Name`, `Year`, `Population`  
- Years: 1960 to most recent available  
- Includes all countries worldwide

---

## Data Cleaning / Preparation

- Renamed columns for consistency: `Country Name`, `Year`, `Population`  
- Converted `Year` to integer and `Population` to numeric  
- Filtered for the **most recent year** for single-year charts  
- Calculated **top 20 countries per year** for interactive charts  
- Ensured no missing or inconsistent values remained

---

## Exploratory Data Analysis (EDA)

- Analyzed population trends across years  
- Identified top 20 most populous countries for each year  
- Explored population growth patterns for major countries  
- Observed regional differences and emerging populous countries

---

## Visualizations

1. **Bar Chart (Top 20 Countries, Most Recent Year)**  
   - Horizontal bar chart showing population ranking  
   - Hover tooltips show exact population numbers  
   - HTML export: `html/top_20_bar.html`

2. **Treemap (Most Recent Year)**  
   - Shows population distribution of top 20 countries  
   - Color gradient represents population magnitude  
   - HTML export: `html/population_treemap.html`

3. **Altair Interactive Chart (Multi-Year)**  
   - Year slider to explore population changes over time  
   - Filters top 20 countries dynamically for each selected year  
   - HTML export: `html/altair_multi_year.html`

---

## Outcomes / Insights

- China and India consistently dominate global population rankings  
- Countries like the USA, Indonesia, and Brazil remain highly populous but with different growth trends  
- The interactive chart highlights emerging countries and allows year-by-year exploration  
- Visualizations provide a clear and engaging way to understand population distribution globally

---

## Conclusion / Key Learnings

This project demonstrates skills in:  
- Data cleaning and preprocessing  
- Exploratory data analysis  
- Interactive data visualization using **Plotly** and **Altair**  
- Presenting insights clearly for stakeholders or portfolio reviewers  

It is a strong portfolio example for **data analysis, visualization, and Python programming skills**.

---

## Project Files

- `data/population.csv` → source population dataset  
- `notebooks/interactive_population_dashboard.ipynb` → Colab notebook with full analysis  
- `html/top_20_bar.html` → exported interactive bar chart  
- `html/population_treemap.html` → exported interactive treemap  
- `html/altair_multi_year.html` → exported Altair multi-year chart  

---

## How to View

1. Open any of the HTML files in your browser to see the interactive charts.  
2. For the Altair multi-year chart, you can also open it in Google Colab.  
3. Optional: Deploy via GitHub Pages to view charts online (see repository settings).

---

## Technologies Used

- Python 3  
- Pandas  
- Plotly  
- Altair + Vegafusion  
- Google Colab
