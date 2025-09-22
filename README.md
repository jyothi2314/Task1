Load Data – Reads Titanic dataset from CSV, else uses Seaborn’s built-in version.

Explore Data – Shows first rows, dataset info, and missing values.

Handle Missing Values – Fills Age/age with median, Embarked/embarked with mode, and drops Cabin/deck.

Encode Categorical Features – Converts categorical columns into numeric using one-hot encoding.

Scale Numeric Features – Standardizes all numerical columns using StandardScaler.

Outlier Removal – Detects and removes outliers in Fare/fare using the IQR method.

Final Output – Prints cleaned dataset shape and preview.
