
# 🎓 Student Performance Prediction using  EDA and Linear Regression 


This project builds a Linear Regression model to predict students' **math scores** based on demographic and academic data.

## 📁 Dataset
- Source: `StudentsPerformance.csv`
- Features:
  - Gender
  - Race/Ethnicity
  - Parental Level of Education
  - Lunch
  - Test Preparation Course
  - Reading Score
  - Writing Score
- Target: `Math Score`

## 🧪 Technologies Used
- Python 3.x
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## 🧰 How to Run the Project

1. **Clone this repo**
```bash
git clone https://github.com/yourusername/student-performance-prediction.git
cd student-performance-prediction



pip install -r requirements.txt


python model_train_and_visualize.py



Project Steps
Load and Explore Data using EDA - exploratory data analysics

Preprocess Data

Encode categorical variables using OneHotEncoder

Train Model

Linear Regression with train/test split (80/20)

Evaluate Model

R² Score

RMSE (Root Mean Squared Error)

Visualize Predictions

Scatter plot: Actual vs Predicted values

📈 Results
R² Score: ~0.176

RMSE: ~14.16
📉 Visualization Example
Scatter plot of actual vs predicted math scores with ideal line:






