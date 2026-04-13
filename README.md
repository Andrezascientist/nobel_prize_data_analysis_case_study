# 🏆 Nobel Prize Data Analysis Case Study

**Author:** Andreza Eufrasio

**Stack:** Python, pandas, NumPy, matplotlib

**Notebook:** `nobel_prize_data_analysis_case_study.ipynb`

---

## 📌 Project Overview

This project explores historical Nobel Prize data to uncover patterns in **gender representation**, **award distribution**, and **repeat winners**.

The analysis is structured as a case study answering eight key business-style questions, transforming a guided exercise into a **complete exploratory data analysis (EDA) project** with clear insights and visualizations.

---

## 🎯 Objectives

The main goals of this project are:

- Analyze trends in Nobel Prize awards over time  
- Investigate gender disparities across categories  
- Identify individuals who have won multiple Nobel Prizes  
- Explore how female representation has evolved historically  
- Communicate findings through clear visualizations and insights  

---

## 📊 Dataset

- **File:** `data/nobel.csv`
- **Source:** Adapted from DataCamp (based on Nobel Prize public data)
- **Unit of analysis:** Each row represents **one Nobel Prize award assigned to a laureate**
  
---

## 📊 Data Dictionary

### Key Variables

* `year` → Year the Nobel Prize was awarded
* `category` → Nobel Prize category (e.g., Physics, Chemistry, Peace)
* `sex` → Gender of the laureate
* `birth_country` → Country where the laureate was born
* `full_name` → Full name of the laureate

---

### Additional Variables

* `prize` → Full name/description of the Nobel Prize awarded

* `motivation` → Official reason for the award

* `prize_share` → Fraction of the prize received (e.g., 1/2, 1/3)

* `laureate_id` → Unique identifier for each laureate

* `laureate_type` → Type of laureate (individual or organization)

* `birth_date` → Date of birth

* `birth_city` → City of birth

* `organization_name` → Affiliated organization (if applicable)

* `organization_city` → City of affiliated organization

* `organization_country` → Country of affiliated organization

* `death_date` → Date of death (if applicable)

* `death_city` → City of death

* `death_country` → Country of death

---

### Notes

* Missing values are present in some columns (e.g., `death_date`, `organization_name`)
* Each row represents **one Nobel Prize award assigned to a laureate**
* Some prizes are shared among multiple laureates, reflected in `prize_share`

---

## 🔍 Key Questions

This analysis answers the following:

1. What is the most commonly awarded gender among Nobel Prize winners?
2. Which country has produced the most Nobel laureates?
3. Which decade had the highest proportion of US-born winners?
4. Which decade and Nobel Prize category had the highest proportion of female laureates?
5. Who was the first woman to receive a Nobel Prize and in which category?
6. Which individuals have won multiple Nobel Prizes?
7. How has female representation among Nobel Prize winners evolved over time?
8. Which Nobel Prize categories show the largest gender disparities

---

## 📈 Key Findings

* **Male laureates dominate Nobel Prize history**, with female representation remaining low for most of the 20th century
* The **United States emerges as the leading country** in terms of Nobel Prize winners
* The **2000s show the highest proportion of U.S.-born laureates**, indicating growing dominance in recent decades
* **Marie Curie** was the first female Nobel Prize winner and remains one of the few multiple-time winners
* Only a **small group of individuals have won multiple Nobel Prizes**, highlighting exceptional contributions
* Female representation **increases significantly after the 1990s**, although it remains uneven
* **Peace and Literature** show the highest female participation
* **Physics, Economics, and Chemistry** exhibit the **largest gender disparities**, with very low female representation

---

## 🛠️ Methods & Techniques

This project demonstrates:

- Data cleaning and preprocessing in **pandas**  
- Feature engineering (e.g., decade creation, gender indicators)  
- Groupby analysis and aggregation  
- Data visualization using **matplotlib** and **seaborn**  
- Comparative analysis (counts vs proportions)  
- Structured analytical storytelling  

---

## 📂 Project Structure

```
nobel-prize-analysis/
│
├── nobel_prize_data_analysis_case_study.ipynb
├── README.md
├── data/
│   └── nobel.csv
```

---

## 🚀 How to Run the Notebook

1. Clone or download this repository.
2. Make sure the dataset file is placed at `data/nobel.csv` or update the notebook path if needed.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn notebook
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Run `nobel_prize_data_analysis_case_study.ipyn` from top to bottom.

6. See answers under sections Q1–Q8, with insights and recommendations.

--- 

## 💡 Skills Demonstrated

- Data cleaning and preprocessing (pandas)
- Exploratory Data Analysis (EDA)  
- Data wrangling and preprocessing  
- Data visualization and storytelling  
- Analytical thinking and insight generation  
- Structuring a project for a professional portfolio  

---

## 📌 Notes

- The notebook includes an **Appendix section** with alternative methods and visualizations  
- Focus is placed on **clarity, reproducibility, and insight communication**  
