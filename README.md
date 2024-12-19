## Machine Learning Portfolio

### [Project 1: Core features of the Pandas library](https://github.com/shap0011/machine_learning_fall_2024/blob/main/Pandas_Class.ipynb)

---

In the **Pandas_class.ipynb** file, I explore the core features of the Pandas library, a vital tool for data manipulation in Python. The file covers the following topics:  

- **Creating a Python Library and Accessing it in Google Colab**: Mounting a Google Drive folder to integrate external files into the Colab environment.  
- **Importing Modules (Pandas)**: Setting up the environment for efficient data analysis.  
- **Pandas DataFrame**: Reading data from a CSV file and exploring structured data tables.  
- **Indexing DataFrame**: Utilizing `.loc` and `.iloc` methods to perform operations such as retrieving values from specific rows and columns, selecting multiple rows, and specifying ranges of rows and columns.  
- **Manipulating DataFrame**: Executing operations such as adding new columns and rows, sorting the DataFrame, dropping rows and columns, removing duplicates, and checking for missing values.  
- **Reading Data from Different Sources**: Loading datasets from formats like `.xlsx`, `.txt`, `.zip`, `.html`, and `.json`.  

This project highlights practical skills in data handling.  

---

### [Project 2: Descriptive Statistics - Goodlife Fitness Case Study](https://github.com/shap0011/machine_learning_fall_2024/blob/main/Goodlife_Fitness_Solution.ipynb)

---

**Descriptive Statistics - GoodLife Fitness Case Study**  

In the **Goodlife_Fitness_Solutions.ipynb** file, I perform a descriptive analysis to create customer profiles for each GoodLife Fitness membership option. This analysis explores key statistical insights and visualizations, covering the following topics:  

- **Importing Libraries and Loading the Dataset**: Import the necessary Python packages and load the *GoodlifeFitness.csv* dataset.  
- **Basic Data Exploration**: Print basic information about the dataset, check for null values, and review the data's structure.  
- **Univariate Analysis**:  
  - Examine the five-number summary statistics.  
  - Analyze the dataset's summary, including descriptive stats for categorical data.  
- **Visualization of Numerical Distributions**:  
  - Plot the distribution of numerical columns such as *Age*.  
  - Create boxplots to identify outliers in *Age*.  
- **Categorical Data Analysis**:  
  - Determine value counts for each categorical column, including *Type*.  
  - Calculate the percentage distribution of user types using normalization.  
- **Bivariate Analysis**: Visualize relationships, such as plotting a boxplot to compare *Income* with *Membership Type*.  
- **Multivariate Analysis**:  
  - Use `pd.crosstab` to analyze data across *Gender* and *Type*.  
  - Apply `pd.pivot_table` to explore data by *Income* and *Type*.  
  - Create scatter plots using Pandas for further insights.  

This case study demonstrates the application of descriptive statistics and visualization techniques to uncover actionable insights regarding fitness memberships.

---

### [Project 3: Standardization of Normal Variables - Z-Score Analysis](https://github.com/shap0011/machine_learning_fall_2024/blob/main/Z_score_Statistics.ipynb)

---

In the **Z_score_Statistics.ipynb** file, I perform standardizing normal variables using the Z-score method. This file includes the following steps:  

- **Mounting Google Drive in Google Colab**: Access files stored in Google Drive to enable seamless data loading.  
- **Importing Libraries and Loading the Dataset**: Load the necessary Python packages and read the *scores.csv* file into a DataFrame.  
- **Visualizing the Data Distribution**:  
  - Use the Seaborn library for visualization.  
  - Plot the distributions of *SAT* and *ACT* scores.  
- **Calculating Mean and Standard Deviation**:  
  - Compute the mean and standard deviation for *SAT* and *ACT* scores.  
  - Determine the Z-score for the highest scorer in *SAT* and *ACT* among all applicants.  
- **Applying the Z-Score to All Scores**: Standardize the entire table by applying the Z-score formula to all values.  
- **Fit-Transform Using StandardScaler**:  
  - Import `StandardScaler` from `sklearn.preprocessing`.  
  - Initialize the scaler and apply it to the *SATscore* and *ACTscore* columns using `fit` and `transform` methods, or utilize `fit_transform` directly.  
  - Display the updated DataFrame to confirm standardization.  

This project highlights the use of Z-score standardization and the application of Python libraries to prepare data for further analysis.

---
