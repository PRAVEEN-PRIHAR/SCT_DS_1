# Student Score Analysis

This project is an exploratory data analysis (EDA) of a dataset containing student scores. The primary objective is to understand the relationships between various demographic and socio-economic factors and students' academic performance in Math, Reading, and Writing.

## Project Overview

The analysis is conducted in a Jupyter Notebook using Python and popular data analysis libraries such as pandas, seaborn, and matplotlib. The key steps in this project include:

1.  **Data Loading and Inspection:** The dataset (`Student_score.csv`) is loaded, and its basic properties (e.g., shape, data types, initial rows) are examined.
2.  **Data Cleaning:**
    * An unnecessary "Unnamed: 0" column is removed.
    * The dataset is checked for missing values to identify columns that may require imputation or careful handling.
3.  **Descriptive Statistics:** A summary of the dataset's numerical columns is generated to understand the distribution of scores.
4.  **Data Visualization and Analysis:**
    * **Gender Distribution:** A count plot is created to visualize the distribution of male and female students in the dataset.
    * **Parental Education vs. Scores:** A heatmap is used to show the relationship between the parents' level of education and the average scores of the students.
    * **Parental Marital Status vs. Scores:** A similar heatmap analysis is performed to determine if the parents' marital status has any correlation with student performance.

## Key Findings

* **Gender Distribution:** The dataset contains a slightly higher number of female students than male students.
* **Parental Education:** The analysis indicates a positive correlation between the parents' education level and their children's test scores. Parents with higher academic qualifications (e.g., a master's or bachelor's degree) tend to have children who score higher on average.
* **Parental Marital Status:** The analysis concluded that there is no significant impact on a student's test scores based on their parents' marital status.

## How to Use This Project

To explore this analysis on your own:

1.  **Prerequisites:** Make sure you have Python and Jupyter Notebook installed on your system.
2.  **Libraries:** Install the necessary Python libraries by running:
    ```bash
    pip install pandas matplotlib seaborn
    ```
3.  **Dataset:** Download the `Student_score.csv` file and place it in the same directory as the notebook.
4.  **Run the Notebook:** Launch Jupyter Notebook and open the `Student_score (1).ipynb` file. You can then execute the cells in the notebook to see the analysis and visualizations.

