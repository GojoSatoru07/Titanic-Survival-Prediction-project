
# Titanic Survival Prediction Project

Welcome to the Titanic Survival Prediction Project!  
In this project, we build a machine learning model to predict whether a passenger survived the Titanic disaster based on features like age, sex, ticket fare, and more.

---

## 📂 Project Structure

```bash
├── data/               # Raw or processed datasets (optional)
├── models/             # Saved machine learning models (optional)
├── notebooks/          # Jupyter/Colab notebooks
├── README.md           # Project documentation
├── requirements.txt    # List of Python libraries needed (optional)
└── main.py             # Main script (optional)
```

---

## 📋 Project Description

The Titanic dataset is a classic machine learning problem from Kaggle.  
The goal is to **predict survival** based on passenger information such as:

- Age
- Fare
- Sex
- Pclass (Passenger class)
- Family size (engineered feature)

We clean the data, engineer new features, scale the data, and apply machine learning models.

---

## 🛠 Technologies Used

- Python 3.x
- pandas
- numpy
- scikit-learn
- KNNImputer
- StandardScaler
- Logistic Regression / Random Forest (add whichever model you used)

---

## 📈 Key Steps

1. **Data Cleaning**
   - Handle missing values using **KNN Imputation**.
   - Log transformation on skewed `Fare` column.
   - Feature engineering: Created `FamilySize`.

2. **Feature Encoding**
   - Binary encoding for `Sex`.
   - One-hot encoding for `Embarked` (after fixing missing values).

3. **Model Building**
   - Split into training and test sets.
   - Standardized features using **StandardScaler**.
   - Trained models and evaluated accuracy.

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/GojoSatoru07/Titanic-Survival-Prediction-project.git
```

2. Install required packages:

```bash
pip install -r requirements.txt
```

3. Run the main script or open the notebook:

```bash
python main.py
```
or open the `.ipynb` notebook in Jupyter/Colab.

---

## 📊 Results

(✅ You can add a line here like:  
*"Our Logistic Regression model achieved an accuracy of 78% on the test set."*  
Or whatever your final result was!)

---

## 📚 Acknowledgments

- [Titanic: Machine Learning from Disaster (Kaggle)](https://www.kaggle.com/c/titanic)
- Thanks to scikit-learn and pandas for awesome libraries!

---

## ✨ Future Improvements

- Try other models like Random Forest, XGBoost.
- Perform hyperparameter tuning.
- Use ensemble techniques.
- Visualize feature importance.

---

# 🚢 "Women and children first" — Let's see if machine learning can predict who survived!
