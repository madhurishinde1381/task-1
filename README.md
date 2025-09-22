# task-1
**Data Cleaning & Preprocessing**

Steps Performed:
1. Imported dataset and explored missing values & data types.
2. Handled missing values:
- Age  → Filled with median
- Embarked  → Filled with mode
- Cabin  → Replaced with 'Unknown'
3. Converted categorical variables:
- Sex  → Label Encoding
- Embarked  → One-Hot Encoding
4. Standardized numerical features (Age, Fare).
5. Detected outliers using boxplots and removed beyond 3 standard deviations.6. Saved cleaned dataset as  titanic_cleaned.csv.
  Missing Values (Before Cleaning)
