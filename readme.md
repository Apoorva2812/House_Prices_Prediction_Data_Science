# Real Estate Price Prediction Website

This personal project demonstrates the step-by-step process of building a **real estate price prediction web application**. The primary objective is to create a seamless platform that predicts property prices based on user input such as square footage, number of bedrooms, etc.

The project is divided into three main components:

## 1. **Model Development**

- Built a predictive model using **Python** and **scikit-learn** with the **Bangalore home prices dataset** from Kaggle.
- Key data science techniques applied include:
  - Data loading and cleaning
  - Outlier detection and removal
  - Feature engineering and dimensionality reduction
  - Hyperparameter tuning using **GridSearchCV**
  - Model evaluation with **k-fold cross-validation**

## 2. **Backend Development**

- Developed a **Python Flask** server to handle HTTP requests and serve the prediction results from the saved model.
- Integrated the trained model to provide real-time predictions.

## 3. **Frontend Development**

- Designed a user-friendly web interface using **HTML**, **CSS**, and **JavaScript**.
- Implemented interactive input forms for property details, which are sent to the Flask backend to fetch the predicted price.

---

## **Technologies and Tools Used**

- **Python**: Core language for data science and backend development
- **Numpy** and **Pandas**: For efficient data cleaning and preprocessing
- **Matplotlib**: For visualizing trends and distributions
- **Scikit-learn**: For machine learning model building
- **Flask**: To set up the HTTP server and enable model integration
- **HTML/CSS/JavaScript**: For developing a dynamic user interface
- **Jupyter Notebook**, **VS Code**, and **PyCharm**: IDEs for development and debugging

---

## **Project Highlights**

1. Cleaned and prepared a real-world dataset with over 10,000 records.
2. Built a robust regression model with optimized parameters to ensure high accuracy.
3. Deployed the model on a Flask server for easy API integration.
4. Designed an intuitive web application for end users to predict property prices in real time.

---
