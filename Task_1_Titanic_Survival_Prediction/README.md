# Titanic Survival Prediction

This project is completed as Task 1 of the CodSoft Data Science Internship.

## Objective

Build a Machine Learning model that predicts whether a passenger survived the Titanic disaster.

## Dataset

The downloaded Titanic dataset contains passenger information such as:

* Passenger Class
* Gender
* Age
* Fare
* Cabin
* Embarkation Port
* Survival Status

## Project Workflow

1. Loaded the downloaded Titanic dataset.
2. Checked dataset columns and missing values.
3. Visualized survival count and gender-based survival.
4. Selected useful features for prediction.
5. Converted categorical data into numerical values.
6. Filled missing Age and Embarked values.
7. Split data into training and testing datasets.
8. Trained a Random Forest Classifier.
9. Evaluated the model using accuracy, classification report, and confusion matrix.

## Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* VS Code / Jupyter Notebook / Google Colab

## Machine Learning Algorithm

Random Forest Classifier

## 📊 Model Evaluation

The Random Forest Classifier was evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

The model achieved approximately **81.56% accuracy** on the test dataset.

This means that the model correctly predicted the survival outcome for approximately 82 out of every 100 passengers in the test data.

## ✅ Conclusion

The project demonstrates how Machine Learning can be used to solve a binary classification problem using real-world passenger data.

The complete workflow included data preprocessing, handling missing values, exploratory data analysis, categorical feature encoding, model training, prediction, and evaluation.

The Random Forest Classifier achieved approximately **81.56% accuracy**, showing that passenger characteristics such as gender, passenger class, age, and fare contain useful information for predicting survival.

## ▶️ How to Run

1. Download or clone this repository.
2. Keep `Titanic-Dataset.csv` and `titanic_survival_prediction.ipynb` in the same folder.
3. Open the notebook using Jupyter Notebook, VS Code, or Google Colab.
4. Install the required Python libraries if necessary.
5. Run all notebook cells from top to bottom.

## 👨‍💻 Author

**Ashish Kumar**

GitHub: [Programmer-pathak](https://github.com/Programmer-pathak)
