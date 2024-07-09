# Income-Prediction-Analysis
Income Prediction Analysis using R, ggplot2, dplyr, and modelr

This project uses R and its data science libraries to analyze the Panel Study of Income Dynamics (PSID) data and predict income based on social factors.

## Tools & Technologies
- R
- ggplot2
- dplyr
- modelr

## Data
The data used in this project is from the PSID 2017 dataset.

## Analysis Steps
1. **Data Cleaning and Preprocessing**:
    - Filtered the data to include respondents aged 18-75.
    - Filtered education years to reasonable levels (5-25 years).

2. **Visualization**:
    - Plotted the distribution of age and education years.
    - Created visualizations for labor income.

3. **Model Development**:
    - Developed a single-factor linear regression model using education years.
    - Developed a multi-factor linear regression model incorporating education years, age, and gender.

4. **Results**:
    - The single-factor model showed that education years could predict a portion of the variation in labor income.
    - The multi-factor model significantly improved predictive power, explaining over 600% more variation in income.

## Key Visualizations
- Age Distribution
- Education Years Distribution
- Labor Income Distribution
- Mean Income by Age
- Predicted vs. Observed Labor Income by Age
