Final submission. 

✅ Summary of Enhancements Made

1. Robust Data Import
	•	Added file existence check before loading.
	•	Displayed first few rows for quick preview.

2. Improved Data Inspection
	•	Included .info(), .shape, and .isnull().sum() to explore structure and missing data clearly.

3. Missing Value Handling
	•	Missing numeric values are filled with column-wise mean using df.fillna(df.mean()).

4. Correlation Heatmap
	•	Visual representation of how features relate to each other using seaborn.heatmap().

5. Feature Scaling + Model Training Pipeline
	•	Introduced Pipeline with StandardScaler and RandomForestRegressor to streamline preprocessing and training.
	•	Used MultiOutputRegressor for predicting multiple target variables.

6. Evaluation Metrics
	•	Calculated and displayed:
	•	R² Score
	•	RMSE (Root Mean Square Error)
	•	Plotted Actual vs. Predicted for each target variable for better interpretability.

7. Reproducibility
	•	Added RANDOM_STATE for consistent results across multiple runs.
