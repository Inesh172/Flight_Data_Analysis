# Flight Data Analysis (2004–2008)

This repository contains exploratory data analysis, statistical analysis, and machine learning models performed on the **Harvard Dataverse US Flights Dataset (2004–2008)** (https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7).

The project analyses patterns in flight delays, aircraft age effects, and flight diversion behaviour across the United States aviation network.

The analysis combines:

* Exploratory Data Analysis (EDA)
* Statistical testing
* Logistic Regression modelling
* CatBoost machine learning models
* Feature importance and predictive performance analysis

---

## Dataset

The data used in this project originates from the Harvard Dataverse US Flights database containing flight data from **2004 to 2008**, including:

* Flight schedules
* Arrival and departure delays
* Diversions and cancellations
* Carrier information
* Origin and destination airports
* Aircraft information

The dataset includes millions of domestic US flight records across multiple years, enabling large-scale temporal and operational analysis.

---

## Repository Contents

### `flight_delay_patterns_analysis.ipynb`

Exploratory analysis of:

* Flight delay categories
* Best days and times to minimise delays
* Heatmaps of arrival delays across hours and weekdays
* Aircraft age and utilisation analysis
* ANOVA and Tukey HSD testing on aircraft age categories

### `Pre-Flight Diversion Model_python.ipynb`

Machine learning analysis for predicting flight diversions before departure using:

* Logistic Regression
* CatBoost
* Engineered historical diversion-rate features
* Permutation importance analysis
* PR-AUC, Recall, Precision and Lift evaluation

### `Flight Analysis Report.pdf`

Final report summarising:

* Data preprocessing
* Exploratory analysis
* Statistical testing
* Model construction
* Feature importance interpretation
* Predictive performance comparison


### `flight_data_analysis_R.Rmd`

R Markdown source file containing the same analysis from both python files in R code.

## Tools & Libraries

### Python

* pandas
* numpy
* scikit-learn
* CatBoost
* seaborn
* matplotlib

### R

* tidyverse
* ggplot2
* dplyr
* tidyr

---

## Author

**Inesh Tanasekar**
Programming for Data Science Project
Flight Data Analysis (2004–2008)

