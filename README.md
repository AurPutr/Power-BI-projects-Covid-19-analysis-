# Covid-19 Population Impact Analysis

## Description
The goal of this project was to investigate whether a country's population indicators influence the Covid-19 sickness rate. Using Power BI, the analysis explored correlations between population size, population density, and Covid-19 case statistics, with additional insights into mortality patterns by income level.

---

## Project Overview
The project included the following key steps:

- **Data Segmentation**
  - Categorized countries by **population size** (Very big, Big, Middle size, Small, Very small).
  - Classified by **population density type** (Very densely populated, Densely populated, Moderately densely populated, Less densely populated, Very few densely populated).
  - Grouped by **income level** for mortality comparison.

- **Exploratory Analysis**
  - Examined **cases per 100K population** across country size categories.
  - Analyzed case distribution by **country's population density**.
  - Investigated **trends over time** (quarterly breakdown from 2020–2023).
  - Studied the correlation between **sick rate** and **population size**.

- **Key Findings**
  - Larger populations report higher total Covid-19 case counts.
  - Smaller, densely populated countries show higher **disease spread rates**.
  - Mortality rates are higher in **low-income countries**.

---

## Technologies Used
- **Power BI** – for interactive dashboards and visual analysis
- **DAX** – for calculated measures and trend analysis
- **Custom visualizations** – scatter plots, bar charts, decomposition trees, and KPI cards

---

## Install
To view or interact with this project:
1. Open the Power BI `.pbix` file in **Power BI Desktop**.
2. Ensure the Covid-19 dataset is placed in the correct path or connected via parameters.

---

## Analysis Logic
- Loaded Covid-19 case, death, and population data into Power BI.
- Created calculated measures for:
  - **Cases per 100K population**
  - **Case fatality rate (%)**
  - **Sick rate (%)**
- Applied slicers for population density and size categories to enable comparative exploration.
- Designed visuals:
  - **Decomposition tree** – total cases breakdown by size, density, region, income
  - **Bar chart** – distribution of cases by country’s population density
  - **Scatter plot** – correlation between population size and sick rate
  - **Time series** – quarterly Covid-19 case trends

---

## Run
Once the dashboard is loaded in Power BI:
- Use the **Decomposition Tree** to drill down by population indicators.
- Check the **Distribution Chart** to compare countries by density.
- Use the **Correlation View** to observe trends between sick rate and population size.
- Review the **Trend Analysis** to track Covid-19 spread over time.

---

## Visual Insights
The dashboard presents:
- **Case Distribution by Country Size & Density** – showing higher spread rates in smaller, densely populated nations.
- **Mortality by Income Level** – highlighting higher fatality rates in lower-income countries.
- **Population vs Sick Rate Correlation** – showing that total cases increase with population size, though sick rate trends vary.
- **Quarterly Trends** – capturing Covid-19 peaks and declines from 2020–2023.
