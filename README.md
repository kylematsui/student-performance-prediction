# Student Performance Prediction

This project explores how well student lifestyle habits and background factors can predict academic performance, specifically **final exam scores**. Using data from a "Student Habits and Performance" dataset, the analysis involves data preprocessing, exploratory data analysis (EDA), and predictive modeling using Linear Regression and Random Forest Regressor.

## 🖥️ View the Full Analysis  
You can explore the complete rendered report, including all code, plots, and outputs, online [here](https://github.com/kylematsui/student-performance-prediction/blob/main/student_habits_analysis_modeling.ipynb).

## 📊 Objective
Build a supervised machine learning model that predicts a student’s **exam score** based on behavioral and environmental features such as study time, sleep, attendance, diet quality, and screen time.

## 🎓 Course Information

This project was completed as the final project for [CS 82B: Principles of Data Science](https://santamonica-prod.modolabs.net/smc_students/course_catalog/course?feed=course_catalog_content&area=a59adfa9-3b37-5f30-a069-3b5bb44477f6&course=93d186ab-04b7-58fa-8dcf-d88ab0be5db8#:~:text=Schedule%20of%20Classes:CS:CS,CS%2D%3E%20CS%2082B%2D1764) at Santa Monica College.
The course focused on applying core data science techniques in Python, including data cleaning, exploratory data analysis, and machine learning using pandas, seaborn, and scikit-learn.

## 🧰 Tools & Libraries
- Python
- Jupyter Notebook
- Visual Studio Code
- `pandas`
- `seaborn`
- `matplotlib`
- `scikit-learn`

## 📁 Files
- `student_analysis.ipynb`: Jupyter Notebook containing all code for data processing, EDA, and modeling
- `student_habits_performance.csv`: Dataset containing student habits and exam scores
- `student_habits_analysis.pdf`: Final report with summary of analysis, and modeling results

## 🔍 Key Steps
- **Data Cleaning**: Verified there were no missing values; converted categorical features
- **EDA**: Explored distributions and correlations between habits and exam performance
- **Feature Engineering**: Scaled numerical features; one-hot encoded categorical features
- **Modeling**: 
  - **Linear Regression** for simple interpretability
  - **Random Forest Regressor** for non-linear patterns
- **Evaluation**: Used RMSE and R² metrics to compare model performance

## 📌 Findings
- Exam scores were positively associated with **study time**, **sleep**, and **attendance**
- Higher usage of **social media** and **Netflix** correlated with lower scores
- **Linear Regression** outperformed Random Forest, achieving:
  - **RMSE**: 5.15  
  - **R²**: 0.897  

## 📎 Data Source
- [Kaggle: Student Habits vs Academic Performance Dataset](https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performance)


## 👤 Author
Kyle Matsui

## 📝 License
This project is licensed under the [MIT License](LICENSE).
