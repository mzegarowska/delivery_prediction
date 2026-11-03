# Food Delivery Time Prediction (Python)

A Python-based academic project focused on exploratory data analysis, visualization, and machine learning regression techniques to predict food delivery times.

The project investigates relationships between delivery duration and factors such as distance, weather conditions, traffic levels, vehicle type, and courier experience. Three regression models are trained and compared to evaluate their predictive performance.

## Tech Stack & Concepts

- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Core Concepts:** Exploratory Data Analysis (EDA), Data Preprocessing, Statistical Analysis, Data Visualization, Supervised Machine Learning
- **Algorithms:** Linear Regression, Decision Tree Regression, Random Forest Regression
- **Evaluation Metrics:** Mean Absolute Error (MAE), Root Mean Squared Error (RMSE)

## Team & Collaboration (Academic Project)

This project was developed in a two-person team for a second-year university course, using a dataset sourced from Kaggle.

- **My Contributions:**
  - Selected the project topic and dataset from Kaggle.
  - Conducted the initial exploratory data analysis (EDA), including data inspection, preprocessing, and visualization.
  - Worked on the regression analysis and model evaluation, excluding the Decision Tree implementation.
  - Collaborated with my teammate on interpreting the results.

- **Teammate's Contributions:**
  - Implemented the Decision Tree regression model.
  - Collaborated on the final analysis and conclusions.

## Features

- **Exploratory Data Analysis:** Examination of delivery records, descriptive statistics, missing values, and relationships between numerical features.
- **Data Visualization:** Correlation heatmaps, distribution plots, scatter plots, and categorical frequency charts.
- **Data Preprocessing:** Removal of incomplete records, exclusion of order identifiers, and one-hot encoding of categorical variables.
- **Regression Model Comparison:** Training and evaluation of Linear Regression, Decision Tree, and Random Forest models using an 80/20 train-test split.
- **Model Evaluation:** Comparison of prediction errors using MAE and RMSE.
- **Category-Based Analysis:** Additional Random Forest experiments examining prediction errors across weather conditions, traffic levels, times of day, and vehicle types.

## Dataset & Analysis

The dataset contains 1,000 food delivery records with information about delivery distance, weather, traffic conditions, preparation time, courier experience, and total delivery duration.

After removing incomplete records, 883 observations are used for analysis and modeling.

The exploratory analysis identifies delivery distance as the variable most strongly correlated with delivery time (Pearson correlation approximately 0.78).

## Project Structure

- `food_delivery_prediction.ipynb` — Jupyter Notebook containing data exploration, visualizations, regression models, and conclusions.
- `Food_Delivery_Times.csv` — Input dataset required to reproduce the analysis (subject to redistribution permissions).

## How to Run Locally

### Prerequisites

Make sure Python 3 and Jupyter Notebook are installed.

Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn notebook
```

### Execution

1. Place the dataset `Food_Delivery_Times.csv` in the same directory as the notebook.
2. Launch Jupyter Notebook:

```bash
jupyter notebook
```

3. Open `food_delivery_prediction.ipynb`.
4. Select **Run All Cells** to reproduce the analysis and model comparisons.

## Key Findings

- Delivery distance shows a strong positive correlation with delivery time.
- Preparation time has a moderate positive correlation with delivery duration.
- Courier experience shows a weak negative correlation with delivery time.
- Prediction errors vary across delivery conditions and transportation categories.
- Comparing multiple regression algorithms provides insight into the strengths and limitations of different modeling approaches.

## 🎓 Project Context

This project was completed as part of university coursework and demonstrates practical experience in data exploration, preprocessing, regression modeling, and interpreting machine learning results.
