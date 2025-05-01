# Task 1 - Data Cleaning & Preprocessing (AI & ML Internship)

## ✅ Objective
Clean and prepare the Titanic dataset for machine learning.

## 🧰 Tools Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

## 📁 Dataset
Original dataset used: `Titanic_dataset_new.csv`  
Source (if needed): [Titanic Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

## ⚙️ Steps Performed
1. Loaded the dataset with Pandas
2. Checked data shape and missing values
3. Filled missing values in `Age` and `Fare`
4. Dropped rows with missing `Embarked`
5. Encoded categorical columns:
   - Label encoded `Sex`
   - One-hot encoded `Embarked`
6. Standardized `Age` and `Fare` using `StandardScaler`
7. Visualized outliers using boxplots
8. Saved cleaned data to `titanic_cleaned.csv`

## ▶️ How to Run

### 1. Install dependencies:
```bash
pip install pandas numpy seaborn matplotlib scikit-learn
✅ Dataset Loaded Successfully!
   PassengerId  Survived  ...  Cabin Embarked
0            1         0  ...    NaN        S
1            2         1  ...    C85        C
2            3         1  ...    NaN        S
3            4         1  ...   C123        S
4            5         0  ...    NaN        S

[5 rows x 12 columns]

🔍 Missing values before cleaning:
PassengerId      0
Survived         0
Pclass           0
Name             0
Sex              0
Age            177
SibSp            0
Parch            0
Ticket           0
Fare             0
Cabin          687
Embarked         2
dtype: int64
