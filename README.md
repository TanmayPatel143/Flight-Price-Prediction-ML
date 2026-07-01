# Flight-Price-Prediction-ML
An end-to-end Machine Learning project for predicting flight ticket prices using regression algorithms. Includes data preprocessing, exploratory data analysis (EDA), feature engineering, model comparison, performance evaluation, and selection of the best model for accurate flight fare prediction.

# ✈️ Flight Fare Prediction using Machine Learning

## 📌 Project Overview

Flight ticket prices fluctuate based on several factors such as airline, departure time, arrival time, source, destination, duration, and the number of stops. This project aims to build a Machine Learning regression model that accurately predicts flight ticket prices, helping travelers make informed decisions and airlines analyze pricing trends.

The project follows a complete Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and comparison of multiple regression algorithms.

---

## 🎯 Objectives

- Perform comprehensive Exploratory Data Analysis (EDA)
- Clean and preprocess the dataset
- Handle missing values and duplicate records
- Perform feature engineering and feature selection
- Train multiple regression models
- Compare model performance using evaluation metrics
- Recommend the best model for production deployment

---

## 📂 Dataset Information

The dataset contains historical flight booking information with the following features:

| Feature | Description |
|---------|-------------|
| Airline | Airline company name |
| Date_of_Journey | Journey date |
| Source | Departure city |
| Destination | Arrival city |
| Route | Flight route |
| Dep_Time | Departure time |
| Arrival_Time | Arrival time |
| Duration | Flight duration |
| Total_Stops | Number of stops |
| Additional_Info | Additional flight information |
| Price | **Target Variable** |

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Exploratory Data Analysis

The project includes:

- Dataset overview
- Missing value analysis
- Duplicate value detection
- Statistical summary
- Univariate analysis
- Bivariate analysis
- Correlation analysis
- Feature distribution
- Outlier detection
- Data visualization

---

## ⚙️ Data Preprocessing

The following preprocessing techniques were applied:

- Handling missing values
- Removing duplicate records
- Feature engineering
- Date and time transformation
- Label Encoding / One-Hot Encoding
- Feature scaling (where required)

---

## 🤖 Machine Learning Models

Multiple regression algorithms were trained and compared:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor *(Optional)*
- Extra Trees Regressor *(Optional)*

---

## 📈 Model Evaluation Metrics

The models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 📊 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Exploratory Data Analysis
5. Feature Engineering
6. Data Preprocessing
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Model Comparison
11. Best Model Selection
12. Conclusion

---

## 📁 Project Structure

```
Flight-Fare-Prediction/
│
├── data/
│   └── Flight_Fare.csv
│
├── notebook/
│   └── Flight_Fare_Prediction.ipynb
│
├── images/
│
├── requirements.txt
│
├── README.md
│
└── .gitignore
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/TanmayPatel143/Flight-Fare-Prediction.git
```

2. Navigate to the project folder

```bash
cd Flight-Fare-Prediction
```

3. Install the required libraries

```bash
pip install -r requirements.txt
```

4. Open the Jupyter Notebook

```bash
jupyter notebook
```

5. Run all notebook cells.

---

## 📌 Results

- Performed complete Exploratory Data Analysis (EDA).
- Built and evaluated multiple regression models.
- Compared model performance using R² Score, MAE, MSE, and RMSE.
- Selected the best-performing model for predicting future flight ticket prices.

---

## 🔮 Future Improvements

- Hyperparameter tuning using GridSearchCV and RandomizedSearchCV
- Model deployment using Flask or FastAPI
- Interactive web interface using Streamlit
- Real-time flight fare prediction
- Integration with live airline datasets

---

## 👨‍💻 Author

**Tanmay Patel**

GitHub: https://github.com/TanmayPatel143

---

## ⭐ If you found this project helpful, consider giving it a star on GitHub!
