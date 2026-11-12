# ⚽ A Data-Driven Study of Football Player Performance and Market Value

## 📌 Project Overview

This project explores the application of Machine Learning techniques to analyse football player performance, identify performance consistency across multiple seasons, and predict player market value.

The study focuses on developing predictive models that help identify consistent football players and estimate their market value based on historical performance statistics, player attributes, and other relevant factors.

The project consists of two main stages:

1. **Player Performance Consistency Prediction:** Classifying football players as Consistent or Inconsistent using classification algorithms.
2. **Player Market Value Prediction:** Estimating football players' market value using regression algorithms, incorporating performance metrics and consistency labels.

The objective is to demonstrate how data analytics and machine learning can support data-driven decision-making in football scouting, player acquisitions, and transfer market valuations.

## 🎯 Project Objectives

- Analyse football player statistics across multiple seasons.
- Identify key performance indicators that influence player consistency.
- Classify players as Consistent or Inconsistent using machine learning.
- Predict football player market value using regression models.
- Compare different machine learning algorithms based on their performance.
- Explore the relationship between long-term player consistency and market value.

## 📊 Dataset

The dataset was obtained from **Kaggle** and contains football player information and performance statistics across four seasons (2017/18 to 2020/21).

**Dataset Details:**
- Total Records: 2,075 players
- Total Features: 548 columns
- Seasons Covered: 2017/18, 2018/19, 2019/20, 2020/21
- Market Values: Player market values in Euros
- Leagues Covered: Europe's Top Five Leagues

**Data Sources:**
- Transfermarkt – Player information and market values.
- FBref – Football player performance statistics.

### Key Dataset Attributes

- Player Information: Player name, club, age, position, and nationality.
- Financial Information: Market value and remaining contract years.
- Performance Statistics: Goals, assists, matches played, minutes played, shots, tackles, interceptions, and other performance indicators.

## 🛠️ Technologies & Tools Used

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn, XGBoost
- **Development Environment:** Jupyter Notebook

## ⚙️ Methodology

The project follows a structured machine learning workflow.

### 1. Data Pre-processing

The following techniques were applied to prepare the dataset:

- Handling missing values using mean and median imputation.
- Replacing missing categorical values with appropriate labels.
- Feature scaling using MinMax Scaling and Standard Scaling.
- Categorical encoding using One-Hot Encoding.
- Feature engineering using Polynomial Features to capture complex relationships between variables.

### 2. Player Performance Consistency Prediction

Classification algorithms were implemented to categorise players based on their performance consistency across multiple seasons.

**Algorithms Used:**

- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

**Evaluation Metrics:**

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

### 3. Player Market Value Prediction

Regression algorithms were developed to estimate football player market values using player characteristics, performance statistics, and consistency labels.

**Algorithms Used:**

- Multiple Linear Regression
- XGBoost Regressor
- Ridge Regression

**Evaluation Metrics:**

- Root Mean Squared Error (RMSE)
- R-squared (R²)

### 4. Model Comparison

The classification and regression models were compared to identify the best-performing algorithms for their respective prediction tasks.

## 📈 Results & Findings

### Classification Model Results

Three classification algorithms were evaluated to predict player performance consistency.

**Best Performing Model: Gradient Boosting Classifier**

Gradient Boosting achieved the best overall performance across accuracy, precision, recall, and F1 score, outperforming Random Forest and Decision Tree classifiers.

### Regression Model Results

The regression models were evaluated using R-squared and Root Mean Squared Error.

| Model | R-squared (R²) | RMSE |
|---|---:|---:|
| Linear Regression | 0.578 | 9,563,124 |
| XGBoost Regressor | 0.631 | 9,328,315 |
| Ridge Regression | **0.663** | **8,690,594** |

**Best Performing Model: Ridge Regression**

Ridge Regression achieved the highest R-squared score of 0.663 and the lowest RMSE of 8,690,594, making it the best-performing regression model in this study.

### Key Findings

- Gradient Boosting was the most effective classifier for identifying consistent and inconsistent players.
- Ridge Regression provided the most accurate market value predictions among the evaluated regression models.
- Player performance consistency across multiple seasons is an important factor in understanding market value.
- Machine learning can help football clubs make more informed decisions regarding player scouting, recruitment, and valuation.

## ⚠️ Limitations

The study identified several limitations:

- The dataset covers only Europe's Top Five Leagues.
- Performance statistics are limited to four seasons.
- External factors such as injuries, media attention, sponsorships, and team dynamics were not fully incorporated.
- Complex machine learning models may be susceptible to overfitting.
- Football transfer market fluctuations can affect actual player values.

## 🚀 Future Improvements

Potential areas for further research include:

- Incorporating additional football leagues and more seasons.
- Including injury history and team performance.
- Considering external factors influencing player market value.
- Exploring deep learning techniques for improved predictions.
- Using more detailed in-game statistics and event-level data.

## 🎓 Academic Information

**Project Type:** Master's Dissertation

**University:** University of Essex

**Department:** Department of Mathematical Sciences

**Module:** MA981 – Dissertation

**Author:** Vedanth Udhay Sawant

**Submission Date:** September 17, 2024

## 📄 Disclaimer

This project was developed as part of an academic dissertation. The predictions and findings are based on historical football player statistics and the machine learning models implemented in the study. Predicted market values should be considered analytical estimates rather than actual transfer market valuations.

---

⭐ If you find this project interesting, feel free to explore the repository and its implementation.
