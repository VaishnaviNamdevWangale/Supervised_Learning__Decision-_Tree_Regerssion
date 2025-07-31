1.Import Libraries
  Used core libraries like pandas, numpy, sklearn, and matplotlib for data processing and visualization.

2.Load Dataset
  Read the dataset using pd.read_csv() and performed initial inspection using .head() and .info().

3.Exploratory Data Analysis (EDA)
  Checked for:
  Null values
  Duplicate rows
  Feature type
  Used visualizations to understand relationships between variables.

4.Data Cleaning
  Removed or filled null values.
  Dropped duplicate rows.
  Converted data types and formatted categorical features.

5.Feature Selection & Encoding
  Selected relevant columns for training.
  Applied label encoding or one-hot encoding to categorical features.
  Train-Test Split
  Used train_test_split() from Scikit-learn to divide the dataset (typically 70% training, 30% testing).

6.Model Training
  Trained various models such as:
  Linear Regression
  Decision Tree Regressor
  Random Forest Regressor
  Compared performance using r2_score and mean_squared_error.

7.Model Evaluation
  Evaluated models on test data.
  Chose the best-performing model based on metrics.
 
  8.Saving Model
  Used pickle to save the best model for later use in deployment.
