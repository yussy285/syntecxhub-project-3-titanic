# syntecxhub-project-3-titanic
# Titanic Dataset Exploratory Data Analysis (EDA)

This repository contains an Exploratory Data Analysis (EDA) of the classic Titanic dataset. The goal of this project is to inspect missing data, analyze survival rates across various demographic features, visualize key trends, and extract meaningful business insights.

## Project Structure
- `Titanic_Dataset_EDA.ipynb`: Jupyter/Colab notebook containing all Python code, data visualizations, and detailed analysis.

## Key Insights
1. **Gender Disparity:** Female passengers had a significantly higher survival rate (~74%) compared to male passengers (~19%), reflecting the prioritization of women during evacuation.
2. **Socioeconomic Factor:** First-class passengers achieved the highest survival rate (~63%), whereas third-class passengers had the lowest (~24%), demonstrating a strong correlation between ticket class and survival outcomes.
3. **Age Influence:** Children had a higher likelihood of survival compared to adults and seniors.
4. **Data Quality:** Key demographic columns (`sex`, `pclass`) were complete, whereas columns like `deck` had extensive missingness (>75%), making `pclass` a more reliable proxy for status.

## Technologies Used
- **Python**
- **Pandas** (Data Manipulation)
- **Matplotlib & Seaborn** (Data Visualization)
