# A/A/B-Experiment-Analysis-Sales-Funnel-Exploration

![Project](https://img.shields.io/badge/Project-Type%3A%20Case%20Study-blue)
![Data](https://img.shields.io/badge/Data%20Source-logs_exp_us.csv-orange)
![Difficulty](https://img.shields.io/badge/Difficulty-Intermediate-yellowgreen)
![Focus](https://img.shields.io/badge/Focus-Experiment%20Design%20%26%20Funnel%20Analysis-lightgrey)

---

## 🧭 Project Overview

I work as a data analyst for a food product startup. My mission is to investigate **user behavior within the mobile app**, explore the **sales funnel**, and assess the impact of **UI font changes** through an **A/A/B experiment**.

---

## 🧪 Objective

- Study the **conversion funnel** and identify user drop-off points.  
- Determine whether a **new font style** affects user behavior.  
- Ensure that **control groups (A/A)** behave similarly before comparing to the test group (B).  
- Detect **statistically significant differences** between user groups.

---

## 📁 Data Description

Each record is a user event:

| Column          | Description                                                        |
|-----------------|--------------------------------------------------------------------|
| `EventName`     | Type of user action or event                                      |
| `DeviceIDHash`  | Unique user identifier                                            |
| `EventTimestamp`| Timestamp of the event                                            |
| `ExpId`         | Experiment group ID: `246` and `247` (control), `248` (test)      |

📂 **File Path:** `*/datasets/logs_exp_us.csv*`

---

## 📊 Project Workflow

### Step 1 – Data Inspection
- Load and explore the dataset.
- Check data types, missing values, and column names.
- Add new date and datetime features.

### Step 2 – Data Cleaning
- Identify data coverage period.
- Discard incomplete data ranges.
- Confirm balanced group representation.

### Step 3 – Funnel Analysis
- Identify and rank all user events.
- Measure step-by-step conversion rates.
- Determine funnel drop-off points.
- Calculate overall conversion from first event to purchase.

### Step 4 – A/A/B Test Evaluation
- Compare event frequency across all groups.
- Check consistency between control groups (A/A).
- Measure the impact of new font (Group B) on each event.
- Perform statistical hypothesis testing (Z-tests, proportion tests).
- Apply multiple testing corrections as needed.

---

## 🧠 Key Questions

- Where are users dropping off in the conversion funnel?
- Are Groups A and A (246 & 247) statistically similar?
- Does Group B behave differently than the controls?
- Is the font redesign beneficial, neutral, or detrimental?

---

## ✅ Skills Demonstrated

- Funnel and conversion analysis  
- A/A/B experiment validation  
- Hypothesis testing (Z-tests, significance levels)  
- Outlier handling and data cleaning  
- Event-based behavioral insights  

---

## 🚀 Final Deliverables

- Clean, well-documented Jupyter Notebook  
- Visualizations of funnel steps and test results  
- Executive summary with data-driven recommendations  
- Clearly explained statistical decisions and thresholds  

---

## 🧰 Tools Used

- Python (pandas, numpy, matplotlib, seaborn, scipy, statsmodels)  
- Jupyter Notebook  
- A/B Testing Best Practices  

---

## 🏁 Good luck with your analysis!
