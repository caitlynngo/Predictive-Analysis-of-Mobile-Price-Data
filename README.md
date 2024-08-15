# 📱 Predictive Analysis of Mobile Price Data 📞

## 📌 Project Overview & Objective
This repository is about the third portfolio submission of COMP2200 unit using Mobile Price Dataset. This portfolio requires students train classification models to predict mobile phone prices and evaluate the strengths and weaknesses of these models.

## 📊 Dataset Description
The dataset includes information about various mobile phones, such as battery power, Bluetooth, clock speed, dual SIM, front and rear camera megapixels, internal memory, mobile depth, mobile weight, number of cores, pixel resolution, RAM, screen height and width, talk time, and whether the phone supports 3G or 4G.

The target variable of this dataset is `price range`.

## 🗂 Tools and Libraries Used
* Jupyter Notebook
* Python
  * `Pandas`
  * `Numpy`
  * `Scikit-learn`
  * `Seaborn`
  * `Matplotlib`

## 📍 Key Tasks 
1. Explore and Clean the data:
* Load the dataset, impute missing values and remove outliers.
2. Study the correlation and Select most correlated variables
* Plot the correlation matrix & Pick the features that are strongly correlated with `price range`
* `ram`, `battery_power`, `px_height`, `px_width` were the four chosen features to train models.
3. Split the dataset
* Training set : Test set = 8 : 2
4. Train a Logistic Regression Model & Evaluate the Performance
* Train the logistic regression model using the selected features.
* Conduct the accuracy of the model on both training and test sets.
* Evaluate Logistic Regression Model based on important metrics including MSE, Root MSE, and R^2 score.
5. Train a KNN Model
* Train the KNN Model with selected features.
* Conduct the accuracy of the model on both training and test sets.
6. Tune the KNN Model & Evaluate the Performance
* Tune the hyper-parameter K using GridSearchCV to find the optimal K value.
* Visualise and give the insight how K impacts the prediction performance.

## 🎊 Results
1. Accuracy of Logistic Regression Model:
* Logistic Regression train accuracy: 96%
* Logistic Regression test accuracy: 96.2%
2. Accuracy of KNN Model (before tuning with K = 2)
* KNN Train Accuracy: 94.82 %
* KNN Test Accuracy: 89.65 %
3. Accuracy of KNN Model with the best K value after turning (K = 13)
* KNN with best K on test set: 92.17%

## 📝 Grade for this Assignment
High Distinction Grade




