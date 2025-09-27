# 🌍 FAO Food Security Data Analysis (2013–2017)

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

---

## 🔧 Tools & Libraries
The analysis was performed in **Python** using the following libraries:
- `pandas` (data manipulation)
- `numpy` (numerical operations)
- `matplotlib` / `seaborn` (visualizations)
- `jupyter` (interactive notebook)

---

## 🚀 Key Steps in the Analysis
1. **Data import & cleaning**
   - Handling missing values (`NaN`)
   - Renaming columns for consistency
   - Harmonizing units (e.g., converting thousands → individuals, tons → kg)

2. **Exploratory Data Analysis (EDA)**
   - Dimensions of datasets
   - Column types & distributions
   - First insights and descriptive statistics

3. **Data transformation**
   - Adjusting scales
   - Normalizing values where necessary

4. **Visualization**
   - Trends by country and year
   - Comparisons between food aid, undernutrition, and population

5. **Conclusions**
   - Identifying potential gaps between availability and nutritional needs
   - Highlighting key insights for food security

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

