Objective: To clean and preprocess the Titanic dataset using Python libraries like Pandas, NumPy, Seaborn, and Matplotlib. The goal is to handle missing values, encode categorical features, scale numerical features, and detect outliers.

Tools Used:
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

Steps Performed

1. Loaded the Dataset  
   - Loaded the Titanic dataset from a CSV file.

2. Explored the Dataset
   - Checked data types, null values, and statistical summaries.

3. Handled Missing Values
   - Filled missing values in `Age` with median.
   - Filled missing values in `Embarked` with the mode.

4. Encoded Categorical Variables  
   - Converted `Sex` into binary format (0: male, 1: female).
   - Used one-hot encoding for `Embarked`.

5. Normalized Numerical Features  
   - Applied `StandardScaler` to `Age` and `Fare` columns.

6. Visualized Outliers
   - Used boxplots to detect outliers in `Age` and `Fare`.

7. Saved the Cleaned Dataset  
   - Exported the cleaned dataset to `titanic_cleaned.csv`.
  

Outcome: Successfully cleaned the dataset, making it ready for machine learning model development by ensuring:
- No missing values
- All features are numeric
- Data is scaled and normalized
- Potential outliers are identified

Author:Rida Armeen
