# Palmer-Penguins-Dataset-Preparation
Dataset Preparation and Exploratory Data Analysis (EDA) using Python on the Palmer Penguins dataset, including data cleaning, missing value handling, visualization, categorical encoding, and feature scaling.

# 🐧 Palmer Penguins Dataset – Data Preparation & EDA

## 📌 Project Overview

This project focuses on **Dataset Exploration, Data Cleaning, Exploratory Data Analysis (EDA), and Feature Preparation** using the Palmer Penguins Dataset.

The project involves inspecting the dataset, identifying data-quality issues, handling missing values, checking duplicate records, visualizing data, encoding categorical variables, and scaling numerical features.

This project is completed as part of **CIE 2 – Activity 1** under Unit I: Foundations & Data Preparation.

## 🎯 Objectives

- Load and explore a dataset using Pandas.
- Understand dataset structure, dimensions and data types.
- Identify missing values and duplicate records.
- Perform data cleaning and preprocessing.
- Conduct Exploratory Data Analysis (EDA).
- Visualize numerical and categorical features.
- Encode categorical variables using One-Hot Encoding.
- Scale numerical features using StandardScaler.
- Prepare a cleaned dataset for future Machine Learning applications.

## 📂 Dataset Description

**Dataset Name:** Palmer Penguins Dataset

**File Format:** CSV

**Dataset Source:** Palmer Penguins

The dataset contains information about penguin species observed across different islands.

### Dataset Features

| Feature | Description |
|---|---|
| species | Penguin species |
| island | Island where the penguin was observed |
| bill_length_mm | Bill length in millimeters |
| bill_depth_mm | Bill depth in millimeters |
| flipper_length_mm | Flipper length in millimeters |
| body_mass_g | Body mass in grams |
| sex | Penguin sex |
| year | Year of observation |

**Original Dataset Dimensions:**
- Rows: 344
- Columns: 8

**Penguin Species:**
- Adelie
- Gentoo
- Chinstrap

## ⚙️ Methodology

### 1. Data Loading and Exploration
- Imported the required Python libraries.
- Loaded the dataset using Pandas.
- Examined the first and last five records.
- Checked dataset dimensions and information.
- Identified numerical and categorical columns.
- Generated summary statistics.

### 2. Data Quality Assessment
- Identified missing values in each column.
- Calculated missing-value percentages.
- Checked for duplicate records.
- Examined unique categorical values.

### 3. Data Cleaning
- Filled missing numerical values using the median.
- Filled missing categorical values using the mode.
- Checked and handled duplicate records.
- Removed unnecessary leading and trailing spaces from categorical values.

### 4. Exploratory Data Analysis (EDA)

Performed data visualization using Matplotlib and Seaborn.

Visualizations include:
- Distribution of Penguin Body Mass (Histogram).
- Number of Penguins by Species (Count Plot).
- Relationship Between Flipper Length and Body Mass (Scatter Plot).

### 5. Feature Preparation

**Categorical Encoding:**
- Applied One-Hot Encoding to the `island` and `sex` columns.

**Feature Scaling:**
- Applied StandardScaler to numerical measurement features:
  - bill_length_mm
  - bill_depth_mm
  - flipper_length_mm
  - body_mass_g

### 6. Final Dataset Preparation
- Verified missing values after preprocessing.
- Checked duplicate records.
- Verified scaled numerical features.
- Saved the final prepared dataset as a CSV file.

## 📊 Results

### Original Dataset
- Total Records: 344
- Total Features: 8
- Missing values found in numerical and categorical columns.
- Duplicate records: 0

### Missing Value Summary

| Column | Missing Values |
|---|---:|
| bill_length_mm | 2 |
| bill_depth_mm | 2 |
| flipper_length_mm | 2 |
| body_mass_g | 2 |
| sex | 11 |

### Final Prepared Dataset

- Total Records: 344
- Total Columns: 11
- Remaining Missing Values: 0
- Remaining Duplicate Records: 0
- Categorical Encoding: One-Hot Encoding
- Feature Scaling: StandardScaler

**Output File:** `prepared_penguins.csv`

## 🛠️ Technologies & Libraries Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Jupyter Notebook | Development Environment |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | Feature Scaling |

## 📈 Visualizations

The project includes the following visualizations:

1. Penguin Body Mass Distribution
2. Penguin Species Count
3. Flipper Length vs Body Mass

These visualizations help understand the distribution of penguin measurements and relationships between different features.

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone <YOUR_REPOSITORY_URL>
```

### 2. Navigate to the Project Directory

```bash
cd ML-CIE2-Activity1
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Run Jupyter Notebook

```bash
jupyter notebook
```

Open `ML_CIE2_Activity1.ipynb` and execute the cells.

## 📁 Repository Structure

```text
ML-CIE2-Activity1/
│
├── README.md
│
├── ML_CIE2_Activity1.ipynb
│
├── palmerpenguins_original.csv
│
└── prepared_penguins.csv
```

## 🎓 Learning Outcomes

Through this activity, I learned:

- How to explore and understand a real-world dataset.
- How to identify and handle missing values.
- How to check and manage duplicate records.
- How to perform Exploratory Data Analysis.
- How to visualize numerical and categorical data.
- How to encode categorical features.
- How to scale numerical features.
- How to prepare a cleaned dataset for Machine Learning applications.

## 👨‍💻 Academic Information

| Details | Information |
|---|---|
| Activity | CIE 2 – Activity 1 |
| Subject | Machine Learning |
| Unit | Unit I – Foundations & Data Preparation |
| Course | B.Tech |
| Branch | Artificial Intelligence & Data Science |
| Academic Year | 2026–27 |

---

⭐ **This project was developed as part of academic coursework to gain practical experience in Data Exploration, Data Cleaning, EDA, and Feature Preparation.**
