# 🏎️ Formula 1 Race Strategy & Performance Prediction using Machine Learning

## 📌 Project Overview

This project focuses on applying Machine Learning to Formula 1 race strategy and performance analysis. It uses historical race data to predict lap times, understand tyre degradation, identify potential pit-stop windows, and simulate competitive race strategies.

The main objective is to demonstrate how machine learning can support data-driven decisions in motorsport.

## 🎯 Project Objectives

- Predict Formula 1 lap times using machine learning algorithms.
- Analyze tyre degradation across Soft, Medium, and Hard compounds.
- Predict potential pit-stop windows using classification models.
- Simulate different tyre combinations and pit-stop strategies.
- Identify competitive race strategies based on predicted race time.

## 🛠️ Technologies Used

- **Programming:** Python
- **Data Collection:** FastF1 API
- **Data Processing:** Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Database:** SQLite, SQLAlchemy
- **Data Visualization:** Plotly
- **Development Environment:** Jupyter Notebook / Kaggle

## ⚙️ Project Workflow

1. **Data Collection:** Retrieve historical Formula 1 race, lap-time, tyre, driver, and weather information using FastF1.
2. **Data Preprocessing:** Handle missing values, remove unsuitable laps, and prepare the dataset.
3. **Feature Engineering:** Create features such as tyre age, fuel proxy, race progress, compound type, and track conditions.
4. **Lap-Time Prediction:** Train and compare Ridge Regression, Random Forest, and Hist Gradient Boosting.
5. **Tyre Degradation Analysis:** Study how tyre performance changes as tyre age increases.
6. **Pit-Window Risk Prediction:** Apply classification algorithms to estimate the probability of an upcoming pit stop.
7. **Race Strategy Optimization:** Simulate tyre combinations and pit-stop lap combinations to identify the lowest predicted race time.

## 📊 Model Performance

### 1. Lap-Time Prediction

| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Hist Gradient Boosting | **0.2632** | **0.3337** | **0.8392** |
| Random Forest | 0.2710 | 0.3496 | 0.8234 |
| Ridge Regression | 0.2945 | 0.3789 | 0.7926 |

Hist Gradient Boosting achieved the lowest MAE and the highest R² among the evaluated models.

### 2. Tyre Degradation Analysis

Analyzed three major dry-weather tyre compounds:

- **Soft:** Higher degradation as tyre age increases.
- **Medium:** Moderate degradation.
- **Hard:** Relatively stable degradation.

The analysis also considers fuel-related effects on lap-time performance.

### 3. Pit-Window Risk Prediction

| Model | ROC-AUC | F1 Score |
|---|---:|---:|
| Logistic Regression | 0.8011 | 0.3602 |
| Hist Gradient Boosting | **0.8524** | **0.4024** |

The models estimate the likelihood of a pit stop occurring within the next three laps.

Model selection in the implementation is based on PR-AUC.

### 4. Race Strategy Optimization

**Example: 2024 Spanish Grand Prix**

The simulator identified the following competitive strategy:

- Strategy: Medium – Soft – Soft
- Number of pit stops: 2
- Pit stops: Lap 28 and Lap 46
- Predicted race time: 5421.05 seconds

This is a simulated result based on the model and strategy assumptions, not a claim about the actual race-winning strategy.

## 📈 Key Learnings

- Practical implementation of machine learning regression and classification.
- Working with real-world motorsport datasets.
- Feature engineering and grouped cross-validation.
- Understanding tyre degradation and race performance.
- Applying predictive models to race strategy simulation.
- Using Python and SQL for data processing and storage.
- Building data visualizations for performance analysis.

## 🚀 Future Improvements

- Incorporate additional seasons of Formula 1 data.
- Improve pit-stop prediction and probability calibration.
- Include safety-car and virtual safety-car strategy optimization.
- Add driver-specific and circuit-specific performance factors.
- Develop an interactive race strategy dashboard.
- Validate simulated strategies against historical race outcomes.

## 👨‍💻 Author

Developed as a Machine Learning and Data Analytics project, combining predictive modeling, motorsport data analysis, and race strategy optimization.
