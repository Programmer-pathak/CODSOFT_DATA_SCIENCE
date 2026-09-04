# 📈 Sales Prediction Using Machine Learning

## 📌 Project Overview

This project predicts product sales based on advertising expenditure across different media channels using Machine Learning.

The dataset contains advertising expenditure for **TV, Radio, and Newspaper**, along with the corresponding **Sales** values.

A **Linear Regression** model is trained to learn the relationship between advertising expenditure and product sales.

---

## 🎯 Objective

The objective of this project is to build a Machine Learning regression model that can predict product sales based on advertising expenditure across different media channels.

---

## 📊 Dataset Features

The dataset contains the following columns:

* **TV** – Advertising expenditure on TV
* **Radio** – Advertising expenditure on Radio
* **Newspaper** – Advertising expenditure on Newspaper
* **Sales** – Product sales and the target variable

### Input Features

`TV`, `Radio`, `Newspaper`

### Target Variable

`Sales`

---

## 🔄 Machine Learning Workflow

The project follows the following workflow:

`Dataset Loading → Data Understanding → Exploratory Data Analysis → Feature Selection → Train-Test Split → Model Training → Sales Prediction → Model Evaluation → New Data Prediction`

---

## 🔍 Exploratory Data Analysis

The relationship between advertising expenditure and sales is analyzed using visualizations.

The project examines:

* TV Advertising vs Sales
* Radio Advertising vs Sales
* Newspaper Advertising vs Sales

These visualizations help understand how advertising expenditure across different channels is associated with product sales.

---

## 🤖 Machine Learning Algorithm

### Linear Regression

Linear Regression is used because the target variable, **Sales**, is a continuous numerical value.

The model learns the relationship between advertising expenditure and sales and then uses this relationship to predict sales for unseen advertising data.

---

## 📈 Model Evaluation

The model is evaluated using:

* **Mean Absolute Error (MAE): 1.27**
* **Mean Squared Error (MSE): 2.91**
* **R² Score: 0.91**

The R² score indicates that the trained model explains a large portion of the variation in sales observed in the test data.

---

## 🧪 New Sales Prediction

The trained model can also predict sales for new advertising expenditure.

For example, the notebook demonstrates prediction using advertising values for:

* TV
* Radio
* Newspaper

For the sample advertising data used in the notebook, the model predicted sales of approximately **15.54**.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📁 Project Files

```text
Task_4_Sales_Prediction/
│
├── advertising.csv
├── sales_prediction.ipynb
└── README.md
```

* `advertising.csv` – Dataset used for training and testing
* `sales_prediction.ipynb` – Complete Machine Learning implementation
* `README.md` – Project documentation

---

## ▶️ How to Run

1. Download or clone the repository.
2. Open the `Task_4_Sales_Prediction` folder.
3. Make sure `advertising.csv` and `sales_prediction.ipynb` are in the same folder.
4. Open `sales_prediction.ipynb` using Jupyter Notebook, VS Code, or Google Colab.
5. Install the required Python libraries if necessary.
6. Run all notebook cells from top to bottom.

---

## ✅ Conclusion

The Linear Regression model was successfully used to predict product sales based on advertising expenditure across TV, Radio, and Newspaper.

The model achieved an **R² score of approximately 0.91**, with a **Mean Absolute Error of 1.27** and a **Mean Squared Error of 2.91** on the test dataset.

This project demonstrates a complete basic Machine Learning regression workflow, including data exploration, visualization, feature selection, model training, prediction, evaluation, and prediction on new advertising data.

---

## 👨‍💻 Author

**Ashish Kumar**

GitHub: [Programmer-pathak](https://github.com/Programmer-pathak)
