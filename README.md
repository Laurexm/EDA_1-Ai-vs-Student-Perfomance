<div align="center">

# 🎓 AI vs Student Performance
### Exploring the Impact of Generative AI on Academic Performance using Exploratory Data Analysis

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/Matplotlib-ffffff?style=for-the-badge">
<img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge">
<img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">

**Understanding how AI-assisted learning influences academic performance, study habits, dependency, anxiety, and skill retention.**

</div>

---

# 📖 Overview

Generative AI tools such as **ChatGPT**, **Gemini**, and **Claude** are transforming education by helping students study faster and solve problems more efficiently.

But an important question remains:

> **Does increased AI usage improve academic performance, or does it simply replace traditional learning and create dependency?**

This project performs an **Exploratory Data Analysis (EDA)** on a Kaggle dataset to uncover meaningful relationships between AI usage, study habits, GPA, anxiety, and skill retention.

---

# 🎯 Objectives

- Analyze how students use Generative AI.
- Compare AI-assisted learning with traditional studying.
- Measure the relationship between AI usage and GPA improvement.
- Identify patterns of AI dependency.
- Explore the impact of AI on anxiety and skill retention.

---

# 📂 Dataset

**Source:** Kaggle

### Features

- Pre Semester GPA
- Post Semester GPA
- Weekly GenAI Hours
- Traditional Study Hours
- Tool Diversity
- AI Dependency
- Skill Retention Score
- Anxiety During Exams
- Burnout Risk
- Prompt Engineering Skill
- Institutional Policy
- Primary AI Use Case
- Major Category
- Paid Subscription

---

# 🛠 Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Programming |
| Pandas | Data Cleaning & Manipulation |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |

---

# 🔄 EDA Workflow

```
Load Dataset
      │
      ▼
Inspect Dataset
      │
      ▼
Check Missing Values
      │
      ▼
Check Duplicates
      │
      ▼
Feature Engineering
      │
      ▼
Data Transformation
      │
      ▼
Outlier Detection
      │
      ▼
Distribution Analysis
      │
      ▼
Categorical Analysis
      │
      ▼
Correlation Analysis
      │
      ▼
Insights
```

---

# 🧹 Data Cleaning

✔ Checked missing values

✔ Checked duplicate records

✔ Inspected data types

✔ Generated descriptive statistics

---

# ⚙ Feature Engineering

A new feature was created to measure academic improvement.

```python
Difference_in_GPA = Post_Semester_GPA - Pre_Semester_GPA
```

---

# 📊 Visualizations

The project contains:

- 📦 Boxplots
- 📉 Outlier Comparison (Before vs After)
- 📈 Histograms with KDE
- 📊 Count Plots
- 🔥 Correlation Heatmap




## Graphs

📊 [View all graphs](https://github.com/Laurexm/EDA_1-Ai-vs-Student-Perfomance/tree/main/images)


---

# 🔍 Interesting Observation

While exploring the **Post Semester GPA**, an unusual spike appeared.

Almost **4,804 students** had a perfect **4.0 GPA**, while neighboring GPA values contained only **20–30 observations**.

This indicates the dataset contains a **capping artifact**, where GPA values are artificially limited to a maximum value.

---

# 📈 Key Insights

### 📚 Academic Performance

- Strong correlation between Pre and Post Semester GPA (**0.93**)
- Students who had higher GPA in pre sem tend to have scored more in post sem too.

---

### 🤖 AI Usage

- Weekly GenAI usage strongly correlated with AI Dependency (**0.67**)
- Increased GenAI usage directly contributes to be more dependent on AI.

---

### 🧠 Skill Retention

- Greater AI Tool Diversity showed slightly better Skill Retention.
- Students who used a diverse AI toolset tend to have better Skill Retention. Presumably because of knowing which AI toolset to use for which specific purpose.

---

### 😰 Anxiety

- Higher AI Dependency correlated with higher Exam Anxiety (**0.31**).
- Students who have high AI dependency tend to be more anxious during exams.

---

### 🎯 Main Finding

Students who balanced **Generative AI with Traditional Studying** generally demonstrated stronger academic improvement than students relying heavily on AI alone.

---

# 📁 Project Structure

```
AI-Student-Performance-EDA
│
├── ai_student_impact_dataset.csv
├── ai_stu_per.py
├── README.md
│
├── images

```

---

# 🚀 Future Improvements

- Statistical hypothesis testing
- Predictive Machine Learning models
- Streamlit Dashboard
- Power BI Dashboard
- Feature importance analysis
- Interactive visualizations

---

# 💡 What I Learned

Through this project I gained hands-on experience in:

- Understand the domain of the dataset to analyse better
- Exploratory Data Analysis Process
- Data Cleaning without losing core data
- Outlier Detection using IQR
- Correlation Analysis through Heatmap
- Basic Feature Engineering
- Choosing the appropriate Data Visualization specific to the Columns
- Deriving insights from visualizations

---

# 👨‍💻 Author

### Zidane

**Final Year Data Science Student**

Python • Exploratory Data Analysis • Data Visualization 

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a star!

</div>
