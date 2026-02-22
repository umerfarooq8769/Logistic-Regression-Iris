# 📉 Iris Prediction using Linear Regression
An experimental approach to classify Iris flower species using a Regression model.

## 📌 Project Overview
While Linear Regression is typically used for predicting continuous values, this project explores its application in a classification task by rounding off predictions to the nearest class labels.

## 🛠️ Technical Details
- **Algorithm:** Linear Regression (Experimental for classification).
- **Visualization:** PCA (Principal Component Analysis) to reduce 4D features into 2D for plotting.
- **Library:** Scikit-Learn, Matplotlib, Pandas, NumPy.
- **Rounding Logic:** Used `np.rint()` to convert continuous outputs into discrete class integers.



## 📊 Workflow
1. **Feature Engineering:** Loading the Iris dataset and scaling features.
2. **Dimensionality Reduction:** Applying PCA to visualize the clusters of Setosa, Versicolor, and Virginica.
3. **Training:** Fitting the Linear Regression model on 90% of the data.
4. **Evaluation:** Converting predictions to integers to calculate the accuracy score.



## 💡 Key Learning
This project helped me understand the mathematical difference between Regression and Classification, and why specialized models like Logistic Regression are preferred for categorical data.

---
**Developed By:** Umer Farooq (AI Level 2 Graduate)
