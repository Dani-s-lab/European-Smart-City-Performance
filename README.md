# 🏙️ European Smart City Performance

Benchmarking, drivers and hidden value across 65 cities

<p align="center">
  <img src="images/Smart_City_Cover.png" width="100%">
</p>

## 📊 Overview

This project analyzes the performance of 65 European smart cities to understand what differentiates leading and lagging cities in the Smart City Index.  
The analysis compares performance across the five key drivers (People, Government, Environment, Mobility, Economy), evaluates the role of Purchasing Power, and identifies the weakest drivers that represent the most strategic areas for improvement.

The goal is to provide a clear, visual benchmark that supports data‑driven discussions on urban development and highlights where cities can focus to close structural gaps.

## 🧱 Driver Definitions

To better interpret the dashboards, the Smart City Index drivers are defined as follows:

- **People:** education, cultural diversity and social inclusion.  
- **Environment:** environmental sustainability, pollution monitoring and energy‑management initiatives.  
- **Government:** transparency, digital public services and effectiveness of local administration.  
- **Mobility:** transport efficiency, infrastructure, accessibility and ICT integration.  
- **Economy:** productivity, economic vitality and support for entrepreneurship and innovation.  
- **Smart City Index:** aggregate score combining all drivers into a unified performance metric.

## 🧭 Methodology
- Filtered the dataset to include only the 65 European cities available in the source, ensuring a consistent and comparable analytical scope.
- Included only city‑level indicators and excluded the Living driver after confirming it was reported at national rather than city level.
- Merged the Smart Cities Index dataset with Purchasing Power from the World Economic Data (Kaggle) to support exploratory analysis.
- Used Purchasing Power only for a scatter‑plot comparison because it is national‑level data from a different reference year.
- Focused the analysis on cross‑city performance across the remaining drivers to identify structural gaps, outliers and improvement opportunities.

## 🔑 Key Insights

**1) Smart City Index vs Purchasing Power**  
Purchasing Power has only a limited influence on performance. Top cities score well economically, yet the #1 city has lower Purchasing Power than the #2, showing that economic strength supports—but does not determine—smart‑city leadership.

**2) Benchmark of Drivers (Top 10)**  
Among top cities, **People** is consistently the strongest driver, while **Economy** is the weakest. Mobility stands out in 4 of the top 5 cities, acting as an enabler that reinforces other non‑economic drivers.

**3) Driver Performance (Top 10)**  
Performance gaps are balanced, but **People** is the most frequent top driver (5 of 10 cities), followed by Environment and Governance. Economy leads in only one city, confirming that structural quality and citizen‑centric policies matter more than national wealth.

**4) Underrated Cities**  
The Smart City Index generally aligns with city performance (average deviation –0.78), but one city is significantly undervalued, suggesting hidden potential not fully captured by the index.

**5) Smart City Distribution**  
The distribution is asymmetric: high‑performing cities show consistent scores, while lower‑performing ones vary widely, indicating uneven development strategies and infrastructure gaps.

## 🔄 Workflow Diagram

![Workflow](images/Diagram_Smart_City.png)

## 📸 Dashboard Gallery  

### 1) Smart City Index vs Purchasing Power  
Comparison between the highest‑ and lowest‑ranked cities, showing how Purchasing Power aligns with Smart City Index scores. (Power BI)  
![Dashboard 1](images/Smart_City_IndexVSPurchasing_Power.png)

### 2) Smart City Driver Benchmark (Top 10)  
Cross‑driver comparison for the top 10 cities, highlighting differences in structural performance across People, Environment, Government, Mobility and Economy. (Power BI)  
![Dashboard 2](images/Smart_City_Driver_Benchmark.png)

### 3) Smart City Driver Performance (Top 10)  
Overview of dominant drivers, driver gaps and performance balance across the top‑ranked cities. (Power BI)  
![Dashboard 3](images/Smart_City_Driver_Performance.png)

### 4) Smart City Underrated Cities  
Identification of cities whose Smart City Index score underestimates their actual driver performance. (Power BI)  
![Dashboard 4](images/Smart_City_Underrated_Cities.png)

### 5) Smart City Distribution 
Exploratory distribution of Smart City Index scores to highlight variability across European cities. (Plotly)
![Plotly](images/Smart_City_Distribution_.png)

## 🚀 Next Steps  

If additional data becomes available, the analysis could be extended by:

- **Time‑series analysis** — Exploring how Smart City Index scores evolve over multiple years.  
- **Additional indicators** — Integrating new drivers or complementary socio‑economic variables to enrich the analytical depth.

These enhancements would provide a broader perspective while keeping the current analytical framework intact.

## 📦 Dataset

- **World Economic Data** — Contains national‑level Purchasing Power indicators.  
  Source: Kaggle  
  License: CC0 – Public Domain  
  Reference year: ~4 years ago  

- **Smart Cities Index Dataset** — Includes city‑level smart‑city performance indicators across five drivers.  
  Source: Kaggle  
  License: CC0 – Public Domain  
  Reference year: ~5 years ago  
