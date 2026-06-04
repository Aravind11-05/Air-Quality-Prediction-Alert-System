# 🌍 Air Quality Analysis and AQI Prediction

## 📌 Project Overview

This project analyzes air quality data from multiple cities and builds a Machine Learning model to predict the Air Quality Index (AQI) based on major air pollutants.

The project includes data preprocessing, exploratory data analysis (EDA), visualization, feature selection, model training, and AQI prediction using a Random Forest Regressor.

---

## 🎯 Objectives

* Analyze air pollution trends using historical data.
* Understand relationships between pollutants and AQI.
* Build a Machine Learning model to predict AQI.
* Evaluate model performance using R² Score.
* Visualize AQI distribution and prediction accuracy.

---

## 📂 Dataset Information

The dataset contains air quality measurements including:

| Feature | Description             |
| ------- | ----------------------- |
| PM2.5   | Fine particulate matter |
| PM10    | Particulate matter      |
| NO2     | Nitrogen Dioxide        |
| CO      | Carbon Monoxide         |
| SO2     | Sulfur Dioxide          |
| AQI     | Air Quality Index       |

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab

---

## 📊 Exploratory Data Analysis

The project includes:

* Data Cleaning
* Missing Value Handling
* Feature Selection
* AQI Distribution Analysis
* Correlation Analysis
* Data Visualization

### AQI Distribution

The AQI distribution was analyzed using histogram visualization to understand pollutant concentration patterns.

---

## 🤖 Machine Learning Model

### Algorithm Used

* Random Forest Regressor

### Features Used

* PM2.5
* PM10
* NO2
* CO
* SO2

### Target Variable

* AQI (Air Quality Index)

---

## 📈 Model Performance

| Metric   | Value |
| -------- | ----- |
| R² Score | 0.906 |

The model achieved approximately **90.64% prediction accuracy**, indicating strong performance in estimating AQI values.

---

## 📉 Prediction Visualization

A scatter plot was used to compare:

* Actual AQI Values
* Predicted AQI Values

The visualization demonstrates a strong correlation between actual and predicted results.

---

## 📁 Project Structure

```text
Air-Quality-Analysis/
│
├── city_day.csv.zip
├── Air_Quality_Analysis.ipynb
├── README.md
```

---

## 🚀 How to Run

1. Clone the repository.
2. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the Jupyter Notebook or Google Colab file.
4. Run all cells sequentially.
5. View visualizations and model results.

---

## 🎯 Key Outcomes

* Performed end-to-end air quality data analysis.
* Built a predictive AQI model using Machine Learning.
* Achieved an R² score of 0.906.
* Generated meaningful insights from environmental data.
* Developed practical experience in data preprocessing, visualization, and predictive analytics.

---

## 👨‍💻 Author

**Aravind M**

GitHub: https://github.com/Aravind11-05

---

⭐ If you found this project useful, consider giving it a star.
