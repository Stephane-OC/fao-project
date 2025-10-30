# 🌍 FAO Food Security Data Analysis (2013–2017)

📗 [Open notebook on GitHub](https://github.com/Stephane-OC/fao-project/blob/main/Food_Security_Analysis_2013_2017.ipynb)  
🌙 [Dark mode version (HTML)](https://stephane-oc.github.io/fao-project/ )

## 📖 Project Overview
This project is part of a data analysis study on **global food availability and nutrition**, based on datasets provided by the **Food and Agriculture Organization of the United Nations (FAO)**.

The aim of this work is to analyze the historical data (2013–2017) regarding:
- Food availability
- Undernutrition
- Population trends
- Food aid

Julien previously worked on the 2018–present period. 
This repository focuses on the **historical part (2013–2017)**.

---

## 📂 Repository Structure
- `Food_Security_Analysis_2013_2017.ipynb` → Main Jupyter Notebook with code and analysis  
- `population.csv` → Population data (in thousands, later harmonized to individuals)  
- `dispo_alimentaire.csv` → Food availability data (quantities, usage, types)  
- `aide_alimentaire.csv` → Food aid distributed (in tons)  
- `sous_nutrition.csv` → Undernutrition indicators  
- `Lexique_des_donnees.pdf` → Data dictionary (column definitions and units)  
ax.set_title("Top 10 des pays avec la plus forte disponibilité alimentaire (kcal/personne/jour)",
             color="#f1c40f", fontsize=13, pad=15)
---

## 🔧 Tools & Libraries
The analysis was performed in **Python** using the following libraries:
- `pandas` (data manipulation)
- `numpy` (numerical operations)
- `matplotlib` / `seaborn` (visualizations)
- `jupyter` (interactive notebook)

---

## 🚀 Key Steps in the Analysis

1. **Libraries Import & Data Loading**  
   - Importing required libraries (Pandas, NumPy, Matplotlib)  
   - Loading Excel datasets (population, food availability, food aid, undernourishment)  
   - Initial data cleaning and formatting  

2. **Exploratory Data Analysis (EDA)**  
   - Exploring dataset dimensions, columns, and missing values  
   - Standardizing column names and units  
   - Descriptive statistics and first insights for each dataset  

3. **Undernutrition Analysis**  
   - Calculating the proportion of undernourished people by country and year  
   - Estimating the theoretical number of people that could be fed  
   - Analyzing the use of available food resources (human consumption, animal feed, losses, etc.)  
   - Correlating average caloric intake with undernutrition rates  
   - Identifying the most affected countries and major trends (2013–2018)  

4. **Continental Analysis**  
   - Computing average undernutrition rates by continent  
   - Analyzing the evolution of undernutrition between 2013 and 2018  
   - Highlighting global disparities and key regions of concern  

5. **Conclusion**  
   - Summary of key findings  
   - Identified inequalities in food distribution  
   - Insights for improving global food security 

---

## 📌 Scenario
Marc, an expert in food security at FAO, provided the following brief:

> “We are conducting a large study on global food and nutrition. 
Julien analyzed the 2018–present period before leaving. 
You will be in charge of the **historical analysis (2013–2017)** using the provided datasets.

> Julien already drafted a notebook with key steps. Feel free to complement this with additional analyses you find relevant.”

---

## 📊 Deliverables
- Jupyter Notebook with documented analysis  
- Visualizations and insights about global food and nutrition between 2013 and 2017  
- Harmonized dataset ready for further reporting  

---

## 🙌 Credits
- Data source: [FAOSTAT](http://www.fao.org/faostat/en/#data)  
- Project brief provided by **Marc – Nutrition and Food Security Expert (FAO)**  

