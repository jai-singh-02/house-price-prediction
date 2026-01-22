# House Price Prediction

This project predicts house prices using Machine Learning models in Python.  
The main goal is to build a model that can accurately predict the sale price of houses based on various features such as lot size, building type, overall condition, and year built.

---

## 🗂 Dataset Features

Some of the key features used in this project:

- **Id** – Unique identifier for each record  
- **MSSubClass** – Type of dwelling involved in the sale  
- **MSZoning** – General zoning classification of the property  
- **LotArea** – Lot size in square feet  
- **LotConfig** – Configuration of the lot  
- **BldgType** – Type of dwelling (e.g., townhouse, single-family)  
- **OverallCond** – Overall condition rating of the house  
- **YearBuilt** – Original construction year  
- **YearRemodAdd** – Remodel year (same as construction year if no remodeling)  
- **Exterior1st** – Exterior covering of the house  
- **BsmtFinSF2** – Type 2 finished square feet of the basement  
- **TotalBsmtSF** – Total basement area in square feet  
- **SalePrice** – Target variable to predict

---

## 🛠 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🧰 Methodology

1. **Data Loading & Preprocessing**
   - Loaded dataset from CSV
   - Handled missing values
   - Encoded categorical features
   - Scaled numerical features where required

2. **Exploratory Data Analysis (EDA)**
   - Analyzed correlations between features and target
   - Visualized distributions and relationships using Matplotlib and Seaborn

3. **Model Training**
   - Trained multiple Machine Learning models:
     - **Linear Regression**
     - **Random Forest Regressor**
     - **Support Vector Regressor (SVM)**
   - Split data into training and test sets

4. **Evaluation**
   - Evaluated models using metrics like:
     - **MAE (Mean Absolue Error)**
     - **R² Score**
   - Compared performance of all models to select the best one

---

## 📊 Results
- **Linear Regression** gave the best performance based on **R² Score**, indicating it captured the overall trends in house prices most effectively.
- **Random Forest Regressor** and **Support Vector Regressor (SVM)** were also trained for comparison, but their R² scores were slightly lower.
- This shows that for this dataset, a Linear Regression model was sufficient to model the relationship between features and target.

---

## 💡 Key Learnings
- Importance of data preprocessing and feature selection in improving model accuracy  
- Comparison of different ML models for regression problems  
- Visualizing data to understand trends and correlations  
- Understanding overfitting and how ensemble methods like Random Forest help reduce it  

---

## 🔗 GitHub Repository
[House Price Prediction](https://github.com/jai-singh-02/house-price-prediction)


---

### 📝 Note
This project is implemented for learning purposes. All models and analyses are based on the dataset provided.  
