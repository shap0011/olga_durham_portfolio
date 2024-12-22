## Machine Learning Portfolio

### Project 1: Core features of the Pandas library

[Click to open the file...](https://github.com/shap0011/machine_learning_fall_2024/blob/main/Pandas_Class.ipynb)

In the `Pandas_class.ipynb` file, I explore the core features of the Pandas library, a vital tool for data manipulation in Python. The file covers the following topics: 

<details>
  <summary>Click to see details</summary>

<ul>
  <li><strong>Creating a Python Library and Accessing it in Google Colab</strong>: Mounting a Google Drive folder to integrate external files into the Colab environment.</li>
  <li><strong>Importing Modules (Pandas)</strong>: Setting up the environment for efficient data analysis.</li>
  <li><strong>Pandas DataFrame</strong>: Reading data from a CSV file and exploring structured data tables.</li>
  <li><strong>Indexing DataFrame</strong>: Utilizing <code>.loc</code> and <code>.iloc</code> methods to perform operations such as retrieving values from specific rows and columns, selecting multiple rows, and specifying ranges of rows and columns.</li>
  <li><strong>Manipulating DataFrame</strong>: Executing operations such as adding new columns and rows, sorting the DataFrame, dropping rows and columns, removing duplicates, and checking for missing values.</li>
  <li><strong>Reading Data from Different Sources</strong>: Loading datasets from formats like <code>.xlsx</code>, <code>.txt</code>, <code>.zip</code>, <code>.html</code>, and <code>.json</code>. </li>
</ul>

<p>This project highlights practical skills in data handling.</p>  

</details>

---

### Project 2: Descriptive Statistics - Goodlife Fitness Case Study
[Click to open the file...](https://github.com/shap0011/machine_learning_fall_2024/blob/main/Goodlife_Fitness_Solution.ipynb)

In the `Goodlife_Fitness_Solutions.ipynb` file, I perform a descriptive analysis to create customer profiles for each GoodLife Fitness membership option. This analysis explores key statistical insights and visualizations, covering the following topics:  

<details>
  <summary>Click to see details</summary>
  <ul>
  <li><strong>Importing Libraries and Loading the Dataset</strong>: Import the necessary Python packages and load the <code>GoodlifeFitness.csv</code> dataset.</li>
  <li><strong>Basic Data Exploration</strong>: Print basic information about the dataset, check for null values, and review the data's structure.</li>
  <li><strong>Univariate Analysis</strong>:
    <ul>
      <li>Examine the five-number summary statistics.</li>
      <li>Analyze the dataset's summary, including descriptive stats for categorical data.</li>
    </ul>
  </li>
  <li><strong>Visualization of Numerical Distributions</strong>:
    <ul>
      <li>Plot the distribution of numerical columns such as <code>Age</code>.</li>
      <li>Create boxplots to identify outliers in <code>Age</code>.</li>
    </ul>
  </li>
  <li><strong>Categorical Data Analysis</strong>:
    <ul>
      <li>Determine value counts for each categorical column, including <code>Type</code>.</li>
      <li>Calculate the percentage distribution of user types using normalization.</li>
    </ul>
  </li>
  <li><strong>Bivariate Analysis</strong>: Visualize relationships, such as plotting a boxplot to compare <code>Income</code> with <code>Membership Type</code>.</li>
  <li><strong>Multivariate Analysis</strong>:
    <ul>
      <li>Use <code>pd.crosstab</code> to analyze data across <code>Gender</code> and <code>Type</code>.</li>
      <li>Apply <code>pd.pivot_table</code> to explore data by <code>Income</code> and <code>Type</code>. </li>
      <li>Create scatter plots using Pandas for further insights.</li>
    </ul>
  </li>
</ul>

<p>This case study demonstrates the application of descriptive statistics and visualization techniques to uncover actionable insights regarding fitness memberships.</p>

</details>

---

### Project 3: Standardization of Normal Variables - Z-Score Analysis 
[Click to open the file...](https://github.com/shap0011/machine_learning_fall_2024/blob/main/Z_score_Statistics.ipynb)

In the `Z_score_Statistics.ipynb` file, I perform standardizing normal variables using the Z-score method. This file includes the following steps: 

<details>
  <summary>Click to see details</summary>

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

<p>This project highlights the use of Z-score standardization and the application of Python libraries to prepare data for further analysis.</p>

</details>

---

### Project 4: Data Visualization with Python 
[Click to open the file...](https://github.com/shap0011/machine_learning_fall_2024/blob/main/Data_Visualization.ipynb)

The `Data_Visualization.ipynb` file explores data visualization techniques to gain insights, identify patterns, and draw conclusions using Python.

<details>
  <summary>Click to see details</summary>
  
#### Visualization Libraries in Python
- **Seaborn** and **Matplotlib**:
  - Install or import Seaborn (`import seaborn as sns`).
  - Import Matplotlib (`import matplotlib.pyplot as plt`).
  - Retrieve sample datasets from the Seaborn library.
  - Load the `tips` dataset (`df = sns.load_dataset('tips')`).
  - Perform data exploration:
    - Check variable types.
    - Preview the top 5 rows.
    - Return a summary of the DataFrame.

#### Key Visualization Tasks

**Relationship Between Total Bill and Tip Amount**:
   - Use a scatter plot to visualize and analyze the relationship.
   - Determine the type of correlation (positive, negative, or none).

**Strip Plot**:
   - Visualize average tip amounts by day of the week and time of day:
     - `tip` vs. `day`
     - `tip` vs. `time`

**Bar Plot**:
   - Display average tip amounts:
     - By day of the week.
     - By party size.
     - By smoker status.
     - By gender.

**Pair Plot**:
   - Plot pairwise relationships in the `tips` dataset.
   - Use the `hue` parameter (e.g., by `sex`).

**Distribution Plot**:
   - Use `displot()` to visualize a univariate variable distribution:
     - Plot a histogram with a kernel density estimate (KDE).
     - Calculate and annotate the mean, median, and mode.

**Count Plot**:
   - Visualize counts of observations in each category:
     - Create a count plot by day, with `time` as the hue.

**Heatmap**:
   - Display correlations as a two-dimensional heatmap:
     - Each square represents the correlation between two variables.

**Scatter Plot**:
   - Customize scatter plots for `total_bill` vs. `tip`:
     - Experiment with colors, opacity, and shapes of data points.

**Bar Plot**:
   - Create vertical bar plots to display categorical data:
     - Plot smoker and non-smoker counts using Matplotlib.

**Pie Plot**:
    - Visualize univariate data distribution:
      - Plot the occurrence of different days.

**Exploded Pie Plot**:
    - Separate one or more sectors from the pie:
      - Plot the occurrence of days with an exploded view.

 **Histogram**:
    - Analyze the distribution and spread of continuous variables:
      - Plot a histogram for the `tip` variable.

**Box Plot**:
    - Visualize the five-number summary:
      - Plot the boxplot of `total_bill` to check for outliers.

**Subplots**:
    - Create multiple plots within a single canvas:
      - Use `plt.subplot(numrows, numcols, plot_number)` to position plots.
      - Add a strip plot to visualize `tip` vs. `day`.
</details>

<p>The project highlights the use of powerful visualization libraries like Matplotlib and Seaborn to explore, analyze, and interpret data through various graphical representations, enabling insights into patterns, relationships, and distributions within the dataset.</p>

---

