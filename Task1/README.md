# Data Analysis Task - 1

This project involves analyzing a dataset of student exam scores using Python, following the steps outlined below.

## Project Objectives
1. Perform data loading, exploration, and cleaning using Python libraries.
2. Answer specific data analysis questions.
3. Create visualizations to present insights from the dataset.
4. Document the process and findings.

---

## Dataset
**Source**: [Student Performance Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/00320/student.zip)

### Features:
- **G1, G2, G3**: Grades for three terms.
- **studytime**: Hours spent studying weekly.
- **sex**: Gender (Male/Female).

---

## Steps Implemented

### 1. Data Loading
- Loaded using pandas and displayed the first few rows for inspection.

### 2. Data Exploration
- Checked for missing values and displayed dataset information.
- Summarized dataset dimensions and column data types.

### 3. Data Cleaning
- Handled missing values by replacing them with the median.
- Removed duplicate rows.

### 4. Data Analysis
Addressed the following questions:
1. **Average Final Grade**: Calculated the mean of the `G3` column.
2. **High Achievers**: Counted the number of students scoring above 15 in `G3`.
3. **Correlation Analysis**: Determined the correlation between `studytime` and `G3`.
4. **Gender Comparison**: Compared the average `G3` scores between genders.

### 5. Visualizations
- **Histogram**: Distribution of final grades (`G3`).
- **Scatter Plot**: Relationship between `studytime` and `G3`.
- **Bar Chart**: Average `G3` scores by gender.

---

## Requirements
- Python 3.x
- Libraries: `pandas`, `matplotlib`, `seaborn`

---

## How to Run
1. Clone the repository or download the script.
2. Install dependencies using:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Run the script in a Jupyter Notebook or Python IDE.

---

## Outputs
1. Cleaned dataset.
2. Answers to data analysis questions.
3. Visualizations illustrating key insights.

---

## Learnings
- Gained understanding in data manipulation using pandas.
- Developed basic statistical and correlation analysis skills.
- Created informative visualizations using matplotlib and seaborn.
