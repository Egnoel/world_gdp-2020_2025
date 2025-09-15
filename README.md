# 🌍 GDP Analysis per Country (2020–2025)

## 📌 Project Overview
This project analyzes the Gross Domestic Product (GDP) of 196 countries between 2020 and 2025, based on IMF sources.  
The goal is to explore **global economic trends**, measure **growth rates**, compare **economic blocs** (BRICS vs G7), and identify **patterns of development**.

---

## 📂 Project Structure
- `2020-2025.csv` → original dataset.  
- `analysis.ipynb` → Jupyter Notebook with all steps of the analysis.  
- `README.md` → project documentation.  

---

## ⚙️ Steps of the Analysis
1. **Initial check** → dataset size, columns, datatypes, missing values.  
2. **Reshape to long format** → from wide (years as columns) to long (Country | Year | GDP).  
3. **Exploratory Data Analysis (EDA)** → descriptive stats, distributions, boxplots.  
4. **Growth metrics** → year-over-year growth and CAGR (2020–2025).  
5. **Global comparisons** → country rankings, BRICS vs G7.  
6. **Trend visualization** → time series plots.  
7. **Clusters & correlations** → grouping similar economies.  

---

## 📊 Key Findings
- **Global GDP** shows consistent growth between 2020–2025.  
- **BRICS** countries display higher proportional growth than the **G7**.  
- **Economic inequality** is clear: only a few countries concentrate most of the world’s GDP.  
- **Clustering analysis** separates countries into groups: developed economies, fast-growing emerging markets, and developing countries.  

---

## 🚀 Next Steps
- Extend the analysis with **GDP forecasts beyond 2025**.  
- Compare **GDP per capita** instead of totals.  
- Cross-analyze GDP with **other indicators** (e.g., HDI, inflation, trade balance).  

---

## 🛠️ Tech Stack
- **Python 3**  
- **Pandas / NumPy** for data wrangling  
- **Matplotlib / Seaborn** for visualization  

---

✍️ *Developed by Egnoel*
📎 Dataset source: IMF [Kaggle](https://www.kaggle.com/datasets/codebynadiia/gdp-per-country-20202025/data)
