# Heart Disease EDA

Exploratory data analysis on a heart disease dataset using Python (pandas, seaborn, matplotlib, plotly).

## What I did
- Loaded the data and checked basic stats (shape, nulls, duplicates)
- Replaced zero values in `Cholesterol` and `RestingBP` with column means
- Plotted distributions, boxplots, and count plots for all key features
- Built a correlation heatmap and pairplot to identify strong predictors
- Added interactive Plotly charts for Age and Cholesterol vs Heart Disease

## Key Findings
- `Oldpeak` is the strongest predictor of heart disease
- Lower `MaxHR` and older `Age` are associated with higher risk
- Asymptomatic chest pain and male sex show higher disease rates in this dataset