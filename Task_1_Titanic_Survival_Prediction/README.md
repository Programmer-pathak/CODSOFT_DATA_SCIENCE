# 🚢 Titanic Survival Prediction

## 📌 Project Overview

This project was completed as **Task 1 of the CodSoft Data Science Internship**.

The objective of this project is to build a Machine Learning model that predicts whether a passenger aboard the Titanic survived or not based on passenger information such as age, gender, passenger class, fare, family-related attributes, and embarkation point.

---

## 🎯 Objective

The main objective is to analyze the Titanic passenger dataset, preprocess the data, explore important patterns, and train a classification model capable of predicting passenger survival.

The target variable is:

* `Survived = 0` → Passenger did not survive
* `Survived = 1` → Passenger survived

---

## 📊 Dataset

The project uses the `Titanic-Dataset.csv` dataset.

The following features were selected for model training:

| Feature    | Description                       |
| ---------- | --------------------------------- |
| `Pclass`   | Passenger ticket class            |
| `Sex`      | Gender of the passenger           |
| `Age`      | Age of the passenger              |
| `SibSp`    | Number of siblings/spouses aboard |
| `Parch`    | Number of parents/children aboard |
| `Fare`     | Passenger fare                    |
| `Embarked` | Port of embarkation               |

### Target Variable

`Survived` is used as the target variable for prediction.

---

## 🔄 Project Workflow

The project follows a complete basic Machine Learning classification workflow:

1. Import required Python libraries.
2. Load the Titanic dataset.
3. Understand the dataset structure.
4. Check dataset shape, columns, and missing values.
5. Perform Exploratory Data Analysis.
6. Visualize passenger survival distribution.
7. Analyze survival based on gender.
8. Select relevant input features.
9. Convert categorical values into numerical values.
10. Handle missing values.
11. Split the dataset into training and testing sets.
12. Train a Random Forest Classifier.
13. Predict passenger survival.
14. Evaluate model performance.
15. Analyze the confusion matrix.
16. Examine feature importance.

---

## 📈 Exploratory Data Analysis

Exploratory Data Analysis was performed to understand important patterns in the Titanic dataset.

The project includes visualizations for:

* Overall passenger survival distribution
* Survival based on gender

These visualizations help understand the relationship between passenger characteristics and survival.

---

## 🧹 Data Preprocessing

Before training the Machine Learning model, the dataset was prepared for model training.

### Selected Features

```text id="7fd2x4"
Pclass
Sex
Age
SibSp
Parch
Fare
Embarked
```

### Encoding Categorical Data

The `Sex` feature was converted into numerical values:

```text id="hjdndf"
male   → 0
female → 1
```

The `Embarked` feature was also converted into numerical values:

```text id="y78h51"
S → 0
C → 1
Q → 2
```

### Handling Missing Values

Missing numerical values in `Age` and `Fare` were handled using median imputation.

Missing values in `Embarked` were filled using the most frequent value.

---

## ✂️ Train-Test Split

The dataset was divided into:

* **80% Training Data**
* **20% Testing Data**

A fixed `random_state` was used to make the experiment reproducible.

The target variable was also stratified while splitting the dataset.

---

## 🤖 Machine Learning Algorithm

### Random Forest Classifier

The project uses a **Random Forest Classifier** for passenger survival prediction.

```text id="b0ahgs"
RandomForestClassifier(
    n_estimators=100,
    random_state=42
)
```

Random Forest combines multiple decision trees and uses their collective predictions to perform classification.

---

## 📊 Model Evaluation

The trained model was evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

### Model Accuracy

The model achieved approximately:

**81.56% Accuracy**

This means the trained model correctly predicted passenger survival for approximately 81.56% of the test samples.

---

## 🔢 Confusion Matrix

A confusion matrix was generated to compare:

* Actual Not Survived
* Actual Survived
* Predicted Not Survived
* Predicted Survived

This provides more information about classification performance than accuracy alone.

---

## ⭐ Feature Importance

Feature importance from the Random Forest model was analyzed to understand how strongly different passenger attributes contributed to the model's predictions.

This helps make the Machine Learning model more interpretable.

---

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / VS Code

---

## 📁 Project Structure

```text id="45ltjw"
Task_1_Titanic_Survival_Prediction/
│
├── Titanic-Dataset.csv
├── titanic_survival_prediction.ipynb
└── README.md
```

---

## ▶️ How to Run

### 1. Download the project files

Make sure these files are available in the same project folder:

```text id="63g4wy"
Titanic-Dataset.csv
titanic_survival_prediction.ipynb
```

### 2. Install the required libraries

```bash id="v2kv6n"
pip install pandas matplotlib seaborn scikit-learn jupyter
```

### 3. Open the notebook

Open:

```text id="vpvcn5"
titanic_survival_prediction.ipynb
```

using Jupyter Notebook or VS Code.

### 4. Run the notebook

Run all notebook cells sequentially from top to bottom.

---

## 🎓 Learning Outcomes

Through this project, I practiced:

* Loading and exploring real-world datasets
* Handling missing values
* Encoding categorical variables
* Data visualization
* Feature selection
* Train-test splitting
* Machine Learning classification
* Random Forest Classifier
* Model prediction
* Accuracy evaluation
* Classification reports
* Confusion matrices
* Feature importance analysis

---

## 🚀 Future Improvements

The project can be further improved by:

* Using a preprocessing pipeline
* Comparing multiple classification algorithms
* Performing hyperparameter tuning
* Using cross-validation
* Engineering additional passenger features
* Performing more detailed Exploratory Data Analysis

---

## 📝 Conclusion

The Random Forest Classifier achieved approximately **81.56% accuracy** on the test dataset.

The Titanic dataset was explored and preprocessed by handling missing values, encoding categorical variables, and selecting useful passenger features.

The model was trained to predict passenger survival and evaluated using accuracy, classification report, and confusion matrix. Feature importance was also analyzed to understand which passenger characteristics contributed to the prediction.

This project demonstrates a complete basic Machine Learning classification workflow from data loading and preprocessing to model training, evaluation, and interpretation.

---

## 👨‍💻 Author

**Ashish Kumar**

Aspiring Data Scientist | MCA Student

GitHub: [Programmer-pathak](https://github.com/Programmer-pathak)

---

## 📚 Internship

**Data Science Internship — CodSoft**

This project was developed as part of the Data Science Internship tasks assigned by CodSoft.
