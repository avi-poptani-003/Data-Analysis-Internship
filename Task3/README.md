# DATA ANALYSIS TASK - 3

## Objective
This project aims to perform customer segmentation using clustering techniques to group customers based on their purchasing behavior. This enables businesses to effectively target each customer segment with tailored strategies.

## Dataset
- **Dataset Name**: [Mall_Customers.csv](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Columns**:
  - `CustomerID`: Unique identifier for each customer.
  - `Gender`: Gender of the customer.
  - `Age`: Age of the customer.
  - `Annual Income (k$)`: Annual income in thousands.
  - `Spending Score (1-100)`: A score based on spending patterns.

## Steps Performed
1. **Dataset Inspection**:
   - Checked for shape, missing values, duplicate rows, and data types.
   - Generated summary statistics to understand value ranges.

2. **Data Preprocessing**:
   - Selected relevant features (`Age`, `Annual Income (k$)`, `Spending Score (1-100)`).
   - Standardized the features using `StandardScaler` for uniform scaling.

3. **Clustering**:
   - Used the **Elbow Method** to determine the optimal number of clusters.
   - Applied **K-Means Clustering** with the optimal number of clusters.

4. **Visualization**:
   - Visualized clusters in 2D using **Principal Component Analysis (PCA)**.
   - Created pair plots to represent feature relationships within clusters.
   - Displayed centroids for better interpretation of cluster characteristics.

5. **Results**:
   - Added a new `Cluster` column to the dataset.
   - Visualized and saved:
     - **Elbow Method plot** (`elbow_method.png`).
     - **Cluster Scatter Plot (PCA)** (`pca_clusters.png`).
     - **Pair Plots** (`pair_plots.png`).

## Cluster Insights
1. Identified high-spending customer groups for loyalty programs.
2. Proposed targeted promotions for specific clusters.
3. Highlighted marketing strategies tailored for income and age segments.

## Dependencies
- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
