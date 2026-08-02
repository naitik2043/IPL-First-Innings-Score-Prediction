# 🏏 IPL First Innings Score Prediction

A Machine Learning project that predicts the **first innings score** in an IPL match using historical IPL match data. This project applies data preprocessing, feature engineering, exploratory data analysis (EDA), and regression algorithms to estimate the final score based on live match conditions.

---

## 📌 Project Overview

Predicting the first innings score during a live IPL match can help analysts, commentators, and cricket enthusiasts understand the expected outcome of the innings.

This project builds a regression model using features such as:

- 🏏 Batting Team
- 🎯 Bowling Team
- ⏱️ Overs Completed
- 📈 Current Runs
- ❌ Wickets Fallen
- 🔥 Runs Scored in Last 5 Overs
- ⚡ Wickets Lost in Last 5 Overs

The trained model predicts the expected first innings total.

---

## 🚀 Features

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- One-Hot Encoding for Categorical Features
- Machine Learning Model Training
- Model Evaluation
- Score Prediction

---

## 📂 Project Structure

```
IPL-First-Innings-Score-Prediction/
│
├── IPL_Prediction_Model_Training.ipynb
├── Players.xlsx
├── README.md
└── requirements.txt
```

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Machine Learning Workflow

1. Import Dataset
2. Data Cleaning
3. Remove Irrelevant Features
4. Feature Encoding
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Score Prediction

---

## 📈 Model Evaluation

The model is evaluated using regression metrics such as:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📌 Dataset

The dataset contains historical IPL match information used for predicting the first innings score.

Example features include:

- Batting Team
- Bowling Team
- Overs
- Runs
- Wickets
- Runs in Last 5 Overs
- Wickets in Last 5 Overs
- Total Score

---

## ▶️ Getting Started

### Clone the Repository

```bash
git clone https://github.com/naitik2043/IPL-First-Innings-Score-Prediction.git
```

### Navigate to the Project

```bash
cd IPL-First-Innings-Score-Prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter lab
```

or

```bash
jupyter notebook
```

Open:

```
IPL_Prediction_Model_Training.ipynb
```

---

## 🎯 Future Improvements

- Deploy using Streamlit
- Flask API Integration
- Better Feature Engineering
- Hyperparameter Tuning
- Compare Multiple ML Models
- Interactive Web Dashboard

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

If you find any issues, feel free to open an Issue or submit a Pull Request.

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!

---

## 👨‍💻 Author

**Naitik Gupta**

- GitHub: https://github.com/naitik2043
- LinkedIn: www.linkedin.com/in/naitik-gupta2043
