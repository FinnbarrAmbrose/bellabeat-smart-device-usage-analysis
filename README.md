# 📊 Bellabeat Smart Device Usage Analysis  
*How can a wellness technology company play it smart?*

## 📌 Project Overview

This project analyses smart device usage data to identify behavioural patterns and provide **data-driven recommendations** for Bellabeat, a wellness technology company.

Using activity and sleep data from Fitbit users, the analysis focuses on understanding:
- How users engage with smart devices in daily life
- What behaviours indicate strong or weak engagement
- How Bellabeat can improve product design, messaging, and retention strategies

The project follows a **structured, business-focused analytics workflow**, from data cleaning to strategic recommendations.

---

## 🎯 Business Question

> **How can Bellabeat use smart device usage data to improve customer engagement and support everyday wellness behaviours?**

---

## 🗂️ Dataset

- Source: Kaggle – Fitbit Fitness Tracker Data  
- Participants: ~30 users  
- Time period: ~1 month  
- Granularity:
  - Daily activity & calories
  - Sleep tracking
  - Hourly step counts

Raw data is excluded from the repository to follow best practices.

---

## 🔍 Key Insights

### 1️⃣ Users are primarily wellness-oriented, not performance-focused
- Most users show **light to moderate daily activity**
- Very high activity levels are limited to a small minority

**Implication:** Bellabeat’s core audience aligns more with lifestyle wellness than intense fitness training.

---

### 2️⃣ A small highly active segment exists
- A minority of users are consistently very active
- These users are likely more engaged and retained

**Implication:** This segment is valuable but should not define default product messaging.

---

### 3️⃣ Sleep tracking correlates with higher engagement
- Sleep data is logged inconsistently
- Users who do log sleep tend to engage more regularly overall

**Implication:** Sleep features are a strong opportunity to increase retention.

---

### 4️⃣ Engagement follows predictable daily routines
- Activity peaks during:
  - Morning
  - Midday
  - Early evening

**Implication:** Notifications and nudges should align with existing habits.

---

### 5️⃣ Early disengagement signals are visible
- Very low activity and missing sleep data often occur together

**Implication:** Bellabeat can intervene early with supportive re-engagement strategies.

---

## 📈 Key Visuals

### Activity Level Segmentation
![Activity Segments](reports/activity_segments.png)

### Average Steps by Hour of Day
![Hourly Steps](reports/hourly_steps.png)

### Sleep Logging Frequency
![Sleep Logging](reports/sleep_frequency.png)

*Visuals generated in Notebook 03 and saved for reporting use.*

---

## 💡 Recommendations

Based on the analysis, the following actions are recommended:

- Position Bellabeat as a **daily wellness companion**, not a performance tracker
- Introduce **adaptive, personalised goals** instead of fixed targets
- Use **sleep tracking** as an engagement anchor
- Segment users by activity level and personalise messaging
- Time notifications around **natural daily routines**
- Identify early signals of disengagement and respond supportively
- Reward **consistency and habit formation**, not extremes

These recommendations are detailed in Notebook 04.

---

## 🧪 Project Structure

bellabeat-smart-device-usage-analysis/
│
├── notebooks/
│   ├── 01_load_and_clean.ipynb
│   ├── 02_usage_analysis.ipynb
│   ├── 03_visuals_for_report.ipynb
│   └── 04_recommendations.ipynb
│
├── data_cleaned/
├── data_raw/        (ignored)
├── reports/         (saved visuals)
├── requirements.txt
└── README.md


---

## 🛠️ Tools & Skills Used

- Python
- Pandas & NumPy
- Jupyter Notebooks
- Data cleaning & validation
- Exploratory data analysis
- Data visualisation (Matplotlib / Seaborn)
- Business insight generation
- Git & GitHub

---

## 🚀 Why This Project Matters

This case study demonstrates the ability to:
- Translate raw data into meaningful insights
- Communicate findings clearly to non-technical stakeholders
- Connect analysis to real business decisions
- Follow best practices in project structure and documentation

It reflects how data analysis is applied in **real product and marketing environments**.

---

## 👤 Author

**Finnbarr Ambrose**  
Aspiring Data Analyst | Python • Data Analysis • Business Insight
