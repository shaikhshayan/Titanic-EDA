# Titanic Survival Analysis — EDA

Exploratory data analysis of the Titanic passenger dataset to understand
what factors influenced survival.

## Dataset
[Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data) — 891 passengers, 12 features.

## Key Findings
- Women survived at 3.7× the rate of men
- 1st class passengers survived at 2.6× the rate of 3rd class
- Children under 10 had disproportionately higher survival rates
- Fare and Pclass are strongly correlated with survival

## Visualizations

![Survival Count](survival_count.png)
![Survival by Gender](Survival_by_gender.png)
![Survival by Class](survival_by_class.png)
![Age Distribution](age_distribution.png)
![Fare vs Age](fare_vs_age.png)
![Correlation Heatmap](correlation_heatmap.png)

## Libraries Used
pandas · numpy · matplotlib · seaborn

## How to Run
pip install -r requirements.txt
jupyter notebook titanic_eda.ipynb