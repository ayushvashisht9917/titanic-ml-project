# Titanic Survival Prediction – My First Data Analysis Project

This is one of my first hands-on projects as I’m learning data analysis and machine learning.  
I chose the Titanic dataset from Kaggle because it’s beginner-friendly and a great way to practice the full workflow—from cleaning data to building a simple prediction model.

---

## What This Project Is About
The goal is to predict whether a passenger survived the Titanic disaster based on features like age, gender, ticket class, etc.

I used this project to practice:
- Understanding a dataset
- Cleaning missing values
- Doing some basic visualizations
- Creating simple new features
- Building and testing a machine learning model
- Making a Kaggle submission

---

## What I Did Step-by-Step

### 1. Exploratory Data Analysis (EDA)
I started by looking at the data to understand:
- Age distribution  
- Who survived more: males or females  
- How class (Pclass) affected survival  
- Family size patterns  
- Which columns had missing values  

This helped me see which features were important.

---

### 2. Data Cleaning
Here’s how I prepared the data:
- Filled missing **Age** values with the median  
- Filled missing **Embarked** values  
- Dropped the **Cabin** column (too many missing values)  
- Converted **Sex** to numbers (male = 0, female = 1)  
- Created new helpful features like:
  - FamilySize
  - IsAlone

---

### 3. Model Building
I used a **Random Forest** model to make predictions.  
This was my first attempt at using a classifier for a real dataset.

Finally, I generated predictions for the test data and submitted them on Kaggle.

---

##  My Kaggle Score
**Score: 0.76794**

This was my first ever Kaggle submission, and I’m happy with where I started.  
I’m planning to improve this score by trying other models and tuning parameters.

---

## 🧰 Tools I Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-Learn  
- Jupyter Notebook  

---

## Project Structure

titanic-ml-project/

├── titanic.ipynb # My notebook with all analysis and modeling
├── submission.csv # File I submitted to Kaggle
├── README.md # This file
└── (dataset files)

yaml
Copy code

---

##  What I Learned
Working on this project taught me:
- How to clean and explore data
- How to prepare features for a model
- How to build and test a simple ML model
- How to submit predictions on Kaggle
- How to present a project professionally on GitHub

This project boosted my confidence as an aspiring data analyst.

---

## ✨ About Me
Hi, I’m **Ayush**, an aspiring Data Analyst who loves working with data, uncovering patterns, and building projects to learn new things.
