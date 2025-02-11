# Calories Prediction using Machine Learning

This project predicts the number of calories burned during exercise using various machine learning models, including XGBoost and Random Forest Regressor. The dataset includes user details and exercise parameters to estimate calorie consumption.

## 📂 Dataset
- `exercise.csv` - Contains user exercise details like age, gender, height, weight, duration, and intensity.
- `calories.csv` - Contains the corresponding calories burned.

## 🛠️ Setup Instructions

### 1️⃣ Install Dependencies
Ensure you have Python installed. Then, install the required libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
```

### 2️⃣ Load the Dataset
Place `exercise.csv` and `calories.csv` in the same directory as your script.

### 3️⃣ Run the Script
Execute the Python script to train and evaluate the models:
```python
python calories_prediction.py
```

## 📊 Data Preprocessing
- Merging `exercise.csv` and `calories.csv`
- Handling missing values
- Encoding categorical variables (Gender: Male → 0, Female → 1)
- Feature scaling

## 🔥 Model Training & Evaluation
The following machine learning models are used:
1. **XGBoost Regressor** (Primary Model)
2. Random Forest Regressor
3. Linear Regression, Ridge, and Lasso Regression

Performance is evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R-squared Score

## 📈 Visualization
The project includes exploratory data analysis (EDA) with:
- Heatmap for correlation analysis
- Distribution plots for age, height, weight
- Count plots for gender distribution

## 🔗 Contributing
Feel free to fork the repository, create a new branch, and submit a pull request with improvements.

## 📜 License
This project is open-source and licensed under the MIT License.

---

### 🚀 Happy Coding!

