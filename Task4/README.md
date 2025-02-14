# DATA ANALYSIS TASK - 4

## Objective
This project aims to predict house prices based on various features using a linear regression model. The goal is to understand how different features like area, number of rooms, and amenities influence house prices.

---

## Dataset
- **Dataset Name**: [Housing.csv](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset)
- **Key Columns**:
  - `area`: Size of the house in square feet.
  - `bedrooms`: Number of bedrooms.
  - `bathrooms`: Number of bathrooms.
  - `stories`: Number of stories.
  - `parking`: Availability of parking spaces.
  - `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `prefarea`: Binary categorical features (Yes/No).
  - `furnishingstatus`: Categorical feature (Furnished, Semi-Furnished, Unfurnished).
  - `price`: Target variable representing house price.

---

## Steps Performed

### 1. Data Exploration
- Inspected the dataset for:
  - Missing values and handled them by removing incomplete rows.
  - Outliers using boxplots for numerical columns.
  - Statistical distributions of features using histograms.

### 2. Data Preprocessing
- **Binary Features**: Converted `Yes/No` columns to binary values (1/0).
- **Categorical Features**: Applied one-hot encoding to `furnishingstatus` to avoid the dummy variable trap.
- **Numerical Features**: Normalized columns like `area`, `bedrooms`, and `bathrooms` to bring them into the [0,1] range using Min-Max Scaling.

### 3. Feature Correlation
- Visualized feature correlations with the target variable (`price`) using a heatmap.
- Highlighted key predictors of house prices.

### 4. Model Training
- Split data into:
  - **Training Set**: 80% of the data.
  - **Testing Set**: 20% of the data.
- Trained a linear regression model using the training data.

### 5. Model Evaluation
- Evaluated the model's performance using:
  - **Root Mean Square Error (RMSE)**: Measures prediction accuracy.
  - **R² Score**: Explains the variability in the data captured by the model.

---

## Results
- **RMSE**: Lower values indicate better prediction accuracy.
- **R² Score**: Closer to 1 indicates a better model fit.
---

## Visualizations
1. **Distribution of Numerical Variables**: Highlighted distributions of features like `area` and `price`.
2. **Outlier Detection**: Boxplots for key numerical features.
3. **Correlation Heatmap**: Visualized relationships between features and the target variable.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository_url>
