#Libraries
numpy and pandas: Used for numerical operations and data manipulation.
StandardScaler, LabelEncoder: Preprocessing tools from scikit-learn.
StandardScaler: Standardizes features by removing the mean and scaling to unit variance.
LabelEncoder: Converts categorical labels (like "Male", "Female") into numeric values.
warnings.filterwarnings("ignore"): Suppresses warning messages to keep output clean.


#Checking for Missing Values and Removing Duplicates
df.isnull().sum(): Displays how many missing values each column has.
fillna(method='ffill'): Fills missing values using forward fill (uses previous value).
drop_duplicates(): Removes any duplicate rows from the dataset.

#Standardization:
All features are scaled to have mean = 0 and standard deviation = 1, this is essential for clustering or distance-based models like K-Means.



