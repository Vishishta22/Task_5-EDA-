# Task 5: Exploratory Data Analysis (EDA) on Titanic Dataset

## Overview
Performing exploratory data analysis (EDA) on the Titanic dataset to extract insights using visual and statistical methods. The analysis was performed using Python (Pandas, Matplotlib, Seaborn) in a Jupyter Notebook.

## Objective
- Use statistical methods (`.describe()`, `.info()`, `.value_counts()`) and visualizations (`sns.pairplot()`, `sns.heatmap()`, histograms, boxplots, scatterplots) to identify patterns, trends, and anomalies.
- Document findings in a PDF report.

## Files
- `Task5_EDA(Titanic).ipynb`: Jupyter Notebook containing the EDA process, code, visualizations, and observations.
- `Task5_EDA(Titanic).pdf`: PDF report of the findings, exported from the notebook.

## Key Insights
- **Survival Rate**: Only 38% of passengers survived the Titanic disaster (342 out of 891).
- **Socioeconomic Factors**: 1st class passengers had a significantly higher survival rate (63%) compared to 2nd (47%) and 3rd class (24%). Higher fares were correlated with higher survival chances (correlation: 0.26).
- **Gender Disparity**: Females had a much higher survival rate (75%) than males (19%), reflecting the "women and children first" policy.
- **Embarkation Port**: Passengers embarking from Cherbourg had the highest survival rate (55%), possibly due to a higher proportion of 1st class passengers.
- **Age**: Age had a weaker influence on survival (correlation: -0.08), though children were more likely to survive.

## How to Run
1. Install Python and the required libraries: pip install pandas matplotlib seaborn jupyter
2. Launch Jupyter Notebook:  jupyter notebook
3. Open `Task5_EDA(Titanic).ipynb` and run all cells to reproduce the analysis.
4. View the PDF report (`Task5_EDA(Titanic).pdf`) for a summary of findings.

## Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Dataset: Titanic dataset (loaded via Seaborn)

## Date and Time of Submission
- Submitted on: 7:35 PM IST, Monday, June 09, 2025.
