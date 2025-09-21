# Heart Disease Risk Prediction

This project aims to predict the risk of heart disease in patients using a variety of machine learning models. The analysis is based on a dataset that includes demographic, clinical, and lifestyle factors.

---

##  Summary of Findings

The executive summary highlights key insights from the analysis:

* **Model Performance**: Multiple machine learning models were trained and evaluated for their ability to predict heart disease risk. [cite_start]The **Gradient Boosting Classifier** emerged as the top performer with a precision of **0.82** and a recall of **0.86**. The **Random Forest Classifier** also showed strong results, achieving a precision of **0.80** and a recall of **0.85**.
* **Key Risk Factors**: The most significant factors contributing to heart disease risk, according to the analysis, are **chest pain type**, **maximum heart rate achieved**, and **age**. Other important predictors include **cholesterol levels**, **fasting blood sugar**, and **resting blood pressure**.
* **Data Analysis**: The dataset, sourced from a healthcare repository, contains **303 entries** and **14 variables**. The analysis involved several steps, including:
    * **Data Cleaning**: Handled missing values, removed duplicates, and corrected data types to ensure data quality.
    * **Exploratory Data Analysis (EDA)**: Utilized charts and plots to visualize correlations between variables and identify trends.
    * **Feature Engineering**: Created new variables from the existing data, such as a **BMI** feature, to enhance the models' predictive power.
    * **Data Preprocessing**: Normalized numerical data and used one-hot encoding for categorical variables to prepare the dataset for machine learning models.

---

##  Technologies & Libraries

* **Python**: The primary programming language used for the entire project.
* **Pandas & NumPy**: Utilized for efficient data manipulation and numerical operations.
* **Matplotlib & Seaborn**: Employed to create informative visualizations during the EDA phase.
* **Scikit-learn**: The main library for building, training, and evaluating machine learning models.
* **Jupyter Notebook**: The interactive environment used to document the analysis workflow.
