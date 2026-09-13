# 🚢 Titanic Survival Prediction (Machine Learning Project)

![Titanic](https://shields.io)
![Language](https://shields.io)
![ML](https://shields.io)

Welcome to the **Titanic Survival Prediction** repository! This project is based on the famous Kaggle competition, where the goal is to predict which passengers survived the Titanic shipwreck using machine learning models based on passenger data (like age, sex, passenger class, fare, etc.).

---

## 📌 Project Overview
The sinking of the Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the widely considered "unsinkable" RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others. This project builds a predictive model to answer the question: **“What sorts of people were more likely to survive?”** using passenger data.

---

## 📊 Dataset Structure
The dataset consists of passenger information such as:
- `PassengerId`: Unique ID for each passenger
- `Survived`: Survival (0 = No, 1 = Yes)
- `Pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- `Sex`: Sex of the passenger
- `Age`: Age in years
- `SibSp`: Number of siblings / spouses aboard the Titanic
- `Parch`: Number of parents / children aboard the Titanic
- `Ticket`: Ticket number
- `Fare`: Passenger fare
- `Cabin`: Cabin number
- `Embarked`: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

---

## ⚙️ Workflow & Steps Included
1. **Exploratory Data Analysis (EDA):** Visualizing data, understanding correlations, and identifying missing values.
2. **Data Cleaning & Preprocessing:** 
   - Imputing missing values (`Age`, `Embarked`, `Fare`).
   - Dropping or transforming high-cardinality features like `Cabin` and `Ticket`.
3. **Feature Engineering:** Creating new meaningful features (e.g., family size, title extraction from names).
4. **Model Training & Evaluation:** Training multiple Classifiers (Logistic Regression, Decision Trees, Random Forest, XGBoost, etc.) and evaluating them using accuracy and cross-validation scores.
5. **Hyperparameter Tuning:** Fine-tuning the best-performing model to get optimal accuracy.

---

## 💻 Tech Stack Used
- **Language:** Python
- **Libraries:** Pandas, NumPy, Seaborn, Matplotlib, Plotly, Scikit-learn, XGBoost, LightGBM.

---

## 🚀 How to Run this Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/datawithabdulrehman/Titanic_Survival_Prediction.git
   cd Titanic_Survival_Prediction
   ```

2. **Install Dependencies:**
   Make sure you have Python installed, then run:
   ```bash
   pip install -r requirements.txt
   ```
   *(Note: If `requirements.txt` is not present, install core libraries manually: `pip install pandas numpy matplotlib seaborn scikit-learn`)*

3. **Run the Notebook:**
   Open Jupyter Notebook or VS Code to run the `.ipynb` file:
   ```bash
   jupyter notebook
   ```

---

## 🤝 Connect with Me
Let's connect to learn, collaborate, and bring a positive change in the data science industry!

* **GitHub:** [@datawithabdulrehman](https://github.com/datawithabdulrehman)
* **Kaggle:** [@datawithabxrehman](https://www.kaggle.com/datawithabxrehman)
* **LinkedIn:** [Abdul Rehman](https://www.linkedin.com/in/datawithabdulrehman/)


---
*If you like this project, feel free to star ⭐ this repository!*
