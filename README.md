 📊 Netflix Data Analysis Project

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a Netflix dataset using Python.  
The goal is to understand the structure, quality, and patterns in Netflix content such as movies and TV shows by cleaning the data and extracting meaningful insights.

This project demonstrates **real-world data analysis workflow**, including:
- Data loading
- Data cleaning
- Handling missing values
- Basic exploration and visualization

---

## 📂 Dataset Information
- **File name:** `netflix1.csv`
- **Source:** Netflix dataset (CSV format)
- **Rows & Columns:** Displayed and verified in the notebook
- **Data Type:** Mixed (categorical + numerical)

Key columns include:
- `title`
- `type`
- `director`
- `cast`
- `country`
- `release_year`
- `rating`
- `duration`
- `listed_in`
- `description`

---

## 🛠️ Technologies Used
- **Python**
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Matplotlib** – data visualization
- **Seaborn** – statistical visualization
- **Jupyter Notebook**

---

## 🔍 Project Workflow

### 1️⃣ Importing Libraries
Essential Python libraries are imported for data analysis and visualization.

### 2️⃣ Loading the Dataset
The CSV file is loaded using Pandas and initial rows are inspected to understand the structure.

### 3️⃣ Data Quality Check
- Dataset shape is checked
- Column data types are reviewed
- Missing values are identified
- Duplicate records are detected

### 4️⃣ Data Cleaning
- Column names are cleaned (lowercase, spaces removed)
- Missing values in important columns like `director` and `cast` are filled with `"Not Given"`
- Dataset is made analysis-ready

### 5️⃣ Exploratory Data Analysis (EDA)
- Distribution of content types (Movies vs TV Shows)
- Country-wise and year-wise content trends
- Ratings and duration analysis
- Visualization using Matplotlib and Seaborn

---

## 📈 Key Insights (Example)
- Netflix has more **movies than TV shows**
- Most content is added after 2015
- Certain countries dominate Netflix content production
- Many records lack director or cast information, which required cleaning

*(Exact insights depend on visual outputs in the notebook)*

---

## ▶️ How to Run the Project

1. Clone or download the repository
2. Ensure Python is installed
3. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn