## Salary Prediction using Polynomial Regression

### 👨‍🎓 Student Details

- **Name:** Rohan Ramdhan Decharwal
- **Course:** AI/ML Internship
- **Batch:** Batch 1(A)
- **Mentor:** Nishant Shrivastava

---

## 📌 Objective

The objective of this project is to develop a **Polynomial Regression** model to predict employee salaries based on their position level. Since the relationship between position level and salary is non-linear, Polynomial Regression is used to model this relationship more accurately than Linear Regression.

---

## 📂 Dataset

**Position Salaries Dataset**

🔗 **Kaggle Dataset:**  
https://www.kaggle.com/datasets/akram24/position-salaries

### Input Feature

- Position Level

### Target Variable

- Salary

---

## 🛠 Libraries Used

The following Python libraries were used in this project:

- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## ⚙️ Methodology

The project was completed using the following steps:

1. Loaded the dataset using Pandas.
2. Displayed the first five records, dataset information, and summary statistics.
3. Checked for missing values.
4. Selected the input feature (Position Level) and target variable (Salary).
5. Split the dataset into **80% training** and **20% testing**.
6. Transformed the input feature using **Polynomial Features (Degree = 3)**.
7. Trained a **Polynomial Regression** model.
8. Predicted salaries for the test dataset.
9. Evaluated the model using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score
10. Visualized the results using:
    - Scatter plot of the original dataset
    - Polynomial Regression curve

---

## 📊 Results

The Polynomial Regression model successfully captured the non-linear relationship between position level and salary. The model was evaluated using MAE, MSE, and R² Score to measure prediction accuracy. The Polynomial Regression curve closely followed the distribution of the original data, resulting in better predictions compared to a simple linear model.

---

## 📝 Conclusion

This project demonstrates the effectiveness of Polynomial Regression for predicting employee salaries when the relationship between variables is non-linear. Unlike Linear Regression, which fits a straight line, Polynomial Regression fits a curved relationship that better represents the data. This allows the model to capture more complex patterns and improve prediction accuracy. The evaluation metrics and visualization indicate that Polynomial Regression provides a better fit for this dataset. One major advantage of Polynomial Regression is its ability to model non-linear relationships while still remaining relatively simple to implement and interpret.

---

## 📁 Repository Structure

```
Salary Prediction using Polynomial Regression/
│── Salary Prediction using Polynomial Regression.ipynb
│── README.md
```

---

## 👤 Author

**Rohan Ramdhan Decharwal**

**AI/ML Internship – Batch 1(A)**

**Mentor:** Nishant Shrivastava
