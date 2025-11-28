# 📊 Task 02 – Exploratory Data Analysis (EDA)

### SkillCraft Technology Internship

---

## 📌 **Objective**

Perform **data cleaning** and **exploratory data analysis (EDA)** on a dataset of your choice.
For this task, the **Titanic dataset from Kaggle** is used to explore relationships between variables and uncover meaningful patterns and trends.

---

## 📁 **Dataset**

**Titanic Dataset – Kaggle**
You can download it from here:
🔗 [https://www.kaggle.com/c/titanic/data](https://www.kaggle.com/c/titanic/data)

**Files included:**

* `train.csv`
* `test.csv`
* `gender_submission.csv`

---

## 🛠 **Steps Performed**

### **1. Data Loading**

* Loaded dataset using Pandas
* Displayed basic information (shape, column names, data types)

### **2. Data Cleaning**

* Checked and handled missing values
* Converted categorical variables into numerical labels
* Removed duplicates
* Handled outliers (if any)

### **3. Exploratory Data Analysis**

#### Univariate Analysis

* Age distribution
* Passenger class distribution
* Survival count

#### Bivariate Analysis

* Survival rate vs Gender
* Survival rate vs Passenger Class (Pclass)
* Survival rate vs Age group

#### Multivariate Analysis

* Heatmap to identify correlations
* Pairplots for deeper insight

---

## 📈 **Visualizations Included**

* Bar charts
* Histograms
* Count plots
* Box plots
* Heatmap (correlation matrix)

---

## 🧪 **Technologies Used**

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

---

## 📦 **Project Structure**

```
├── data/
│   ├── train.csv
│   └── test.csv
├── notebooks/
│   └── EDA_Titanic.ipynb
├── images/
│   ├── age_distribution.png
│   ├── correlation_heatmap.png
│   └── survival_by_gender.png
└── README.md
```

---

## 📝 **Key Insights**

* Females had a significantly higher survival rate than males
* Passengers in **1st class** had the highest survival rate
* Children (age < 12) were more likely to survive
* Strong correlation between **Pclass** and **Fare**

---

## 🚀 **Conclusion**

This EDA helped in understanding the patterns and relationships in the Titanic dataset.
It forms a strong foundation for further steps such as **feature engineering** and **Machine Learning model building**.

