# ⚽ Messi Goal Analysis & Predictive Modeling

## 📌 Project Overview

This project was developed as the final project of the Data Analytics Bootcamp at Ironhack.

The project analyzes Lionel Messi's goal-scoring performance throughout his club career. The main objective was to explore patterns in his scoring performance and build predictive models to identify the factors associated with scoring multiple goals in a match.

The project includes data cleaning, exploratory data analysis, feature engineering, machine learning, and an interactive Power BI dashboard.

---

## 📊 Power BI Dashboard

<img width="1420" height="799" alt="image" src="https://github.com/user-attachments/assets/fb45e333-78f7-452a-927c-f7d8446f0ba1" />

The dashboard explores Messi's goal-scoring performance across different dimensions, including:

- Goals by competition and tournament stage
- Home vs. away performance
- Goals by days without scoring
- Performance across seasons
- Whether the goal was the opening goal of the match
- Top 10 favorite opponents

---

## 🎯 Project Objective

The main question explored in this project was:

> **Which factors are associated with Lionel Messi scoring multiple goals in a match?**

The analysis focuses on identifying historical patterns and evaluating whether different match and performance-related variables can help predict high-scoring performances.

---

## 📂 Data Source

The dataset used in this project comes from Kaggle:

**Messi, Neymar, Ronaldo, Lewandowski All Goals**

The analysis focuses specifically on Lionel Messi's club career.

---

## 🧹 Data Cleaning & Preparation

The dataset required several preprocessing and cleaning steps, including:

- Date conversion and standardization
- Season classification
- Standardization of goal-minute formats
- Removal of irrelevant or duplicated columns
- Transformation of categorical variables
- Classification of opponents
- Encoding match venue as home or away
- Transformation of the target variable for predictive modeling

The target variable was transformed to distinguish between matches with one goal and matches with multiple goals.

---

## 🔍 Exploratory Data Analysis

The exploratory analysis focused on identifying patterns in Messi's scoring performance.

The main areas explored include:

- Goals across different seasons
- Home vs. away performance
- Goals by competition and tournament stage
- Favorite opponents
- Match context and competition instances
- Relationship between goals and days without scoring

One of the most relevant variables explored was **Days Since Last Goal**, which was later included in the predictive models.

---

## ⚙️ Feature Engineering

Several variables were created and transformed during the analysis:

- **Days Since Last Goal**
- Opponent classification
- Home/Away encoding
- Whether the goal was the opening goal of the match
- Numerical representation of the season

---

## 🤖 Modeling

Several machine learning models were tested and compared.

### Regression Models

- Linear Regression
- Regression Tree
- K-Nearest Neighbors

### Classification Models

- Decision Tree Classifier
- Logistic Regression
- K-Nearest Neighbors Classifier
- Random Forest Classifier

The final selected model was the **Random Forest Classifier**.

---

## 📈 Results

The Random Forest model achieved an accuracy of approximately:

**0.74**

According to the feature importance analysis, **Season** and **Days Since Last Goal** were among the most influential variables in the model.

The project shows how historical performance patterns and engineered features can be used to explore and predict different scoring outcomes.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook
- Power BI

---

## 🚀 Future Improvements

Some possible improvements for the project include:

- Including matches where Messi did not score
- Expanding the dataset with additional match-level information
- Applying the analysis to other players
- Testing additional machine learning models
- Exploring new contextual features related to match performance

---

## 👤 Author

**Flor Guindo**

Aspiring Data Analyst

[GitHub](https://github.com/FlorGuindo)
