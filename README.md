# 📊 AMCAT AMEO Employment Analysis

## 🧠 Exploratory Data Analysis on Engineering Graduate Employment Outcomes (AMEO 2015)

---

## 📌 Project Overview
This project analyzes the **employment outcomes of engineering graduates** using the **Aspiring Minds Employment Outcome (AMEO) 2015 dataset**.  
The analysis focuses on understanding how **salary, job roles, job locations**, and **standardized skill scores** (cognitive, technical, and personality) influence early career outcomes of graduates.

The goal is to derive **data-driven insights** into salary trends, specialization patterns, and potential biases in engineering employment.

---

## 🎯 Objectives
- Analyze **salary distribution** and variability among engineering graduates  
- Study the impact of **job roles, specialization, and college tier** on salary  
- Validate real-world claims about **fresh graduate salaries (₹2.5–3 LPA)**  
- Explore the relationship between **gender and specialization**  
- Identify meaningful **patterns and trends** using exploratory data analysis (EDA)

---

## 📂 Dataset Overview
- **Source:** Aspiring Minds – AMEO 2015 (AMCAT)  
- **Total Records:** 3,998  
- **Total Features:** 40  

### Key Attributes
- Salary  
- Job Designation & Job Role  
- Job Location (City)  
- Gender & Date of Birth  
- Academic Scores (10th, 12th, College CGPA)  
- Skill Scores (English, Logical, Quantitative, Programming)

---

## 🛠 Tools & Technologies
- **Python**
- **Pandas** – data cleaning and manipulation  
- **Matplotlib** – data visualization  
- **Seaborn** – statistical visualizations  
- **Jupyter Notebook** – analysis environment  

---

## 🔍 Methodology

### 1. Data Cleaning & Preparation
- Checked for missing values and inconsistent data  
- Performed data type corrections and filtering  
- Prepared clean datasets for analysis  

### 2. Univariate Analysis
- Histograms to understand distributions and skewness  
- Box plots to detect salary outliers  
- Count plots for categorical variables such as degree and specialization  

### 3. Bivariate Analysis
- Scatter plots to analyze salary vs skill scores  
- Bar charts to compare salary across gender, college tier, and degree  
- Stacked bar plots to study gender vs specialization trends  

### 4. Claim Validation
- Tested the claim that fresh graduates earn **₹2.5–3 LPA** for selected engineering roles using filtered subsets  

---

## 📈 Key Insights & Findings
- **Salary Distribution:**  
  Salary is highly skewed with multiple outliers, especially among Tier-2 college graduates.

- **Claim Validation:**  
  Graduates working in **CSE-related roles** such as *Software Engineer, Programming Analyst,* and *Associate Engineer* generally earn around **₹2.5–3 LPA**, validating the claim.

- **Gender vs Specialization:**  
  Male candidates dominate most specializations, while female representation is comparatively lower in technical streams.

- **College Tier Impact:**  
  Tier-1 college graduates tend to earn higher salaries, while Tier-2 colleges show greater salary variability.

---

## 📊 Visualizations
The project includes:
- Histograms for numerical feature distributions  
- Box plots for salary outlier detection  
- Count plots for degree, specialization, and job locations  
- Scatter plots for salary vs skill scores  
- Stacked bar charts for gender-specialization analysis  

These visualizations help convert raw data into **clear, interpretable insights**.

---

## 💼 Business & Practical Impact
- Provides **salary benchmarks** for fresh engineering graduates  
- Highlights **gender and specialization disparities** in employment outcomes  
- Helps recruiters and educators understand **skill-based hiring trends**  
- Supports data-driven **career guidance and workforce planning**

---

## ⚠️ Challenges Faced
- Handling extreme salary outliers  
- Managing high class imbalance in categorical variables  
- Avoiding overgeneralization while interpreting trends  

---

## 🧾 Conclusion
This project presents a comprehensive analysis of **engineering graduate employment outcomes in India**.  
Through EDA and claim validation, it demonstrates how data can uncover **salary patterns, specialization preferences, and systemic trends** in early-career employment.

---

## 🔮 Future Improvements
- Apply **statistical hypothesis testing** for stronger validation  
- Build **predictive models** for salary estimation  
- Develop an **interactive dashboard** using Power BI or Tableau  
- Extend analysis using more recent employment datasets  

---

## ▶️ How to Run the Project
```bash
# Clone the repository
git clone <repository-url>

# Open the notebook
jupyter notebook amcat_ameo.ipynb
