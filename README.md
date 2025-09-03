🎓 Student Score Prediction

This project focuses on building a simple linear regression model to predict student's exam scores based on the number of hours they study.

📌 Objective

- Use the Student Performance Factors dataset.
- Predict Exam Score based on Hours Studied.
- Perform exploratory data analysis (EDA), training, prediction, and evaluation.

📊 Dataset Overview

The dataset contains multiple features related to students, such as:

- Hours_Studied
- Attendance
- Parental_Involvement
- Previous_Scores
- Exam_Score 

➡️ For this task, we use only two columns:
- Input Feature : Hours_Studied
- Target Variable: Exam_Score

🧰 Tools & Libraries

- Python 
- pandas
- matplotlib
- scikit-learn

🔍 Steps Performed

1. Data Loading: Imported the CSV using pandas.
2. Data Cleaning: Handled missing values by dropping them.
3. Exploratory Data Analysis**: Scatter plot to visualize the relationship between `Hours_Studied` and `Exam_Score`.
4. Train/Test Split: 80/20 using train_test_split.
5. Model Training: Used Linear Regression from scikit-learn.
6. Prediction: Made predictions on test data.
7. Evaluation:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score
8. Visualization: Plotted actual vs predicted scores.

📈 Results

Model performance (example output may vary):
- Mean Squared Error (MSE): `X.XX`
- Mean Absolute Error (MAE): `X.XX`
- R² Score: `0.89+` 

🧠 Key Takeaways

- Linear regression works well when a clear linear relationship exists between input and output.
- R² score gives a good measure of fit.
- Visualizations help assess the model’s effectiveness.

👨‍💻 Author
Muhammad Mustaqeem Javed — AI/ML Intern  
