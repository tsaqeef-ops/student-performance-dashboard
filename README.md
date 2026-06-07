# 📊 Academic Performance KPI Analytics Dashboard

This project analyzes student academic performance data to identify which factors influence exam scores. The workflow includes data cleaning in Excel, exploratory analysis using pivot tables, and visualization through an interactive Power BI dashboard.

The goal is to move beyond assumptions and determine what actually correlates with student performance.

---

## 🧩 Problem Statement

Student performance is affected by multiple academic, behavioral, and environmental factors. However, it is unclear which variables have meaningful impact on exam scores.

---

## 💡 Solution

This project builds an end-to-end analytics pipeline using Excel and Power BI to transform raw student data into actionable insights.

This project explores:
- Which factors correlate with exam performance?
- Do behavioral factors (study hours, attendance) matter more than background factors?
- Are commonly assumed variables (motivation, internet access) actually influential?

---

## 🛠 Tools Used

- Microsoft Excel (Data Cleaning & Preparation)
- Power BI (Data Modeling & Dashboard Development)

---

## 📂 Dataset Features

Source: Kaggle – Student Academic Performance Dataset

### Numerical Variables
- Study Hours  
- Attendance  
- Sleep Hours  
- Previous Scores  
- Tutoring Sessions  
- Physical Activity  
- Exam Score  

### Categorical Variables
- Motivation Level  
- Parental Involvement  
- Access to Resources  
- Internet Access  
- School Type  
- Family Income  
- Peer Influence  
- Gender  
- And more...

---

## 📊 Data Cleaning (Excel)

Steps performed:

- Replaced missing values in categorical columns with `Unknown`
- Standardized categorical values (removed inconsistencies in labels)
- Removed duplicate rows
- Identified invalid exam scores (>100) and capped them at 100
- Verified correct data types (numeric vs text separation)

---

## 📈 Exploratory Analysis

Pivot tables were used to explore relationships between variables and exam scores.

### Key Analyses

#### Motivation vs Exam Score
- Minimal variation across groups
- Difference between highest and lowest ≈ 0.9 points

#### Attendance vs Exam Score
- Clear positive trend
- Higher attendance consistently corresponds to higher scores

#### Study Hours vs Exam Score
- Strong upward trend overall
- Some irregular outliers at extreme values

#### Internet Access vs Exam Score
- Negligible difference between groups

---

## 📊 Power BI Dashboard

The final dashboard includes:

### Visuals
- Clustered column chart: Motivation vs Exam Score
- Line chart: Attendance vs Exam Score
- Scatter plot: Study Hours vs Exam Score
- Bar chart: Internet Access vs Exam Score

### Filters (Slicers)
- Gender
- School Type
- Family Income

### KPIs
- Average Exam Score
- Average Attendance
- Average Study Hours

---

## 📉 Correlation Analysis

Explores relationships between continuous variables.

- Study Hours vs Exam Score (Scatter Plot)  
- Attendance vs Exam Score  

---

## 🔍 Key Findings

- Attendance shows the strongest and most consistent relationship with exam performance
- Study hours are positively correlated with scores, but contain data noise at extremes
- Motivation level has little measurable effect on exam scores in this dataset
- Internet access shows almost no impact on performance
- Performance is primarily driven by effort-based variables rather than background conditions  

---

## 🎛 Interactive Filters (Slicers)

Users can dynamically explore data using:

- School Type (Public / Private)  
- Gender (Male / Female)  
- Family Income (Low / Medium / High)  

---

## Limitations

- Dataset contains synthetic-like inconsistencies (especially in extreme study hour values)
- Correlation does not imply causation
- Some categorical distributions are uneven

---

# 📌 Project Structure
📁 student-performance-dashboard/
│
├── 📊 Student Academic Performance Dashboard.pbix
├── 📁 data/
│ └── StudentPerformanceFactors.xlsx
├── 📁 screenshots/
│ ├── dashboard_overview.png
│ ├── attendance.png
│ ├── internet_access.png
│ ├── kpi_section.png
│ └── study_hours.png
│ └── motivation.png
└── README.md

---

# 🚀 How to Use

1. Download the dataset or open the Power BI file
2. Open `Student Academic Performance Dashboard.pbix` in Power BI Desktop
3. Explore dashboard using slicers and filters

---

