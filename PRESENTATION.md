# Abalone Age Prediction - Presentation

## Objective
Predict abalone age from physical measurements to replace manual counting (time-consuming and error-prone).

## Key Findings
- **Strongest correlations with Rings**: Shell weight (0.88), Diameter (0.82).
- **Model performance**: R² = [ta_valeur], MSE = [ta_valeur].
- **Insight**: Shell weight is the most predictive feature for age.

## Methodology
1. **Data Cleaning**: One-Hot Encoding for 'Sex', checked for missing values.
2. **EDA**: Histograms, correlation heatmap, scatter plots.
3. **Modeling**: Linear Regression with standardized features.
4. **Evaluation**: MSE and R² metrics.

## Visualizations
- [Age Distribution Histogram](Abalone_EDA.ipynb#1.-Age-distribution)
- [Correlation Heatmap](Abalone_EDA.ipynb#2.-Correlation-matrix)
- [Shell Weight vs. Age](Abalone_EDA.ipynb#3.-Scatter-plot)

## Author
Solenn Hallegouet - 41284106I - solenn.hallegouet@outlook.fr
