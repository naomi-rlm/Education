# Differences in Educational Policy/Funding on Act scores across the US

> This project will look at how socioeconomic factors and student teacher ratios affect ACT scores.

---

## Project Overview

I investigated whether school performance, measured by average ACT score, can be predicted from socioeconomic factors such as median household income, unemployment rate, percent of students receiving free/reduced price lunch, and the student teacher ratio. Using cleaned district/school data, I found percentage of students with free and reduced lunch to be the biggest contibutor. Student-teacher ratio was the only factor to not have a significant correlation.

- **Objective:** Investigate how socioeconomic factors affect high school student preformance. 
- **Domain:** Education
- **Key Techniques:** Data Cleaning and Integration, Correlation Analysis, Simple Linear Regression, Quadratic Regression Testing, Multiple Linear Regression, R-squared, Mean absolute error, Residual analysis, Normalization of predictor variables

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** https://www.edgap.org/#5/37.719/-96.899

https://data-nces.opendata.arcgis.com/datasets/43b42be85c4749e48267f83f1f6ffa60_0/explore?location=32.339121%2C-96.020508%2C4.46&showTable=true

https://www.dropbox.com/scl/fi/o8wf1f534pb4u7uavgjxm/ccd_sch_029_1617_w_1a_11212017.csv?rlkey=k2aey38xie2vz9ge4a0v3rrib&e=1&dl=0

- **Description:** The analysis used three school-level datasets from EdGap, NCES, and the Common Core of Data (CCD), containing roughly 15,000–20,000 U.S. public schools in CSV/tabular format. Key features included average ACT score (outcome) and socioeconomic predictors such as median household income, unemployment rate, percent of students on free/reduced-price lunch, and student–teacher ratio, along with basic school identifiers (NCESSCH ID, state, ZIP).
  
- **License:** N/A

---

## Analysis

All notebooks can be found in the code folder. The first notebook is Education_Cleaning which cleans and joins the used datasets. This notebook needs to be run first. Next is Education_Analysis which has all the methods used to analyze the data. Run this once you have the cleaned dataset.

---

## Results

The analysis shows that socioeconomic conditions, especially the percentage of students receiving free or reduced-price lunch, are strong predictors of ACT performance, while student–teacher ratio contributes little explanatory power. These results suggest that community and economic factors shape academic outcomes more than classroom metrics alone. Improving educational equity may therefore require policies that address poverty and family resources, not just school-level staffing.

---

## Authors

- Naomi Le Mouel - [@naomi-rlm](https://github.com/naomi-rlm)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

Libraries used:
-pandas
-seaborn
-numpy
-matplotlib
-statsmodels
-scikit-learn
-plotly

