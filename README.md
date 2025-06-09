#  Titanic Dataset – Exploratory Data Analysis (EDA)

This project performs Exploratory Data Analysis on the **Titanic dataset** using Python. It focuses on understanding survival patterns, visualizing distributions, identifying missing values, and examining relationships between key features.

---

##  Dataset

- **Source**: `train.csv` (Titanic dataset from Kaggle)
---

##  Technologies Used

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook 

---

##  Analysis Steps

### 1.  Importing Libraries
- `pandas`, `matplotlib.pyplot`, `seaborn`
- Set style for consistent plotting

### 2.  Data Loading
- Loaded dataset using `pd.read_csv()`
- Displayed the first 5 rows

### 3.  Basic Exploration
- `.info()`, `.describe()`, `.value_counts()` for structure and summary
- Missing value detection

### 4.  Data Cleaning
- Imputed missing `Age` (median) and `Embarked` (mode)
- Dropped `Cabin` due to high missingness
- Dropped non-essential columns: `PassengerId`, `Name`, `Ticket`

---

## Visualizations

### Univariate Analysis:
- Survival Distribution (Countplot)
- Gender and Passenger Class distribution
- Age and Fare histograms

### Bivariate Analysis:
- Survival by Gender (Hue in Countplot)
- Age vs Survival (Boxplot)

### Multivariate Analysis:
- Heatmap of feature correlations (after encoding categorical variables)
- Pairplot of selected features: `Survived`, `Age`, `Fare`, `Pclass`, `Sex_male`

---

##  How to Run

1. Clone this repository or copy the code into a `.ipynb` or `.py` file.
2. Make sure your Titanic dataset file (`train.csv`) is placed at the correct path.
3. Run the code in Jupyter Notebook or your preferred Python environment.

---


