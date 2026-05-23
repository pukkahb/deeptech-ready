# Supermarket Sales Prediction & Analysis

A simple data analysis and machine learning project that explores supermarket sales data, identifies patterns in customer spending, and predicts total transaction value using different regression models.

---

## Project Overview

This notebook:

- Loads and explores supermarket sales data
- Performs exploratory data analysis (EDA)
- Visualises customer and branch sales trends
- Preprocesses the dataset for machine learning
- Trains multiple regression models
- Compares model performance
- Identifies the most important factors affecting sales

The goal is to understand what influences customer spending and test how well machine learning models can predict transaction totals.

---

## Dataset

The project uses a supermarket sales dataset (`supermarket_sales.csv`).

Some of the features include:

- Branch
- City
- Customer type
- Gender
- Product line
- Payment method
- Quantity
- Unit price
- Gross income
- Total sales value

Target column:

- `Total` (or `Sales` depending on dataset format)

---

## Technologies Used

### Programming Language

- Python

### Libraries

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## Machine Learning Models Used

The notebook compares different regression models:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- K-Nearest Neighbors (KNN) Regressor

---

## Exploratory Data Analysis (EDA)

The analysis includes visualisations such as:

- Total sales by product line
- Sales distribution by customer type
- Sales comparison across branches
- Customer spending patterns

These plots help reveal which products, customer groups, and branches contribute most to sales.

---

## Data Preprocessing

Before modelling:

- Unnecessary columns are removed
- Leakage columns are dropped to avoid unrealistic predictions
- Categorical variables are converted using one-hot encoding
- Data is split into training and testing sets

Columns like tax, gross income, and cost-related variables were removed because they are directly calculated from total sales.

---

## Feature Importance Analysis

The project also uses a Random Forest model to identify the factors that most influence customer spending.

This helps explain:

- Which customer/store characteristics matter most
- Which variables contribute most to prediction performance

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

### 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
supermarket_analysis.ipynb
```

---

## Project Structure

```text
├── supermarket_analysis.ipynb
├── supermarket_sales.csv
└── README.md
```

---

## Results

The notebook compares the performance of multiple machine learning models using:

- R² Score
- Mean Squared Error (MSE)

The results help determine which model predicts supermarket sales most effectively.

---

## Possible Improvements

Future improvements could include:

- Hyperparameter tuning
- Cross-validation
- More advanced visualisations
- Deployment as a web app
- Real-time sales prediction

---

## Author

Temitayo Ogundimu

---

## License

This project is open-source and free to use for learning and educational purposes.

