# 📊 Superstore Sales & Profitability Analysis
### End-to-End Exploratory Data Analysis (EDA) in Python

## 📖 Project Overview
This repository contains a comprehensive data analysis project focused on the **Global Superstore Dataset**. The objective was to move beyond simple data manipulation and uncover the "why" behind the numbers—identifying growth drivers, hidden losses, and regional performance disparities.

Through **8 specialized tasks**, this project demonstrates proficiency in data cleaning, feature engineering, relational data modeling, and advanced visualization.



<img width="3840" height="2160" alt="image" src="https://github.com/user-attachments/assets/02db7f15-ce9c-467a-b6cc-549fbea07d6b" />



---

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Matplotlib
* **Environment:** Google Colab / Jupyter Notebook

---

## 🔍 Key Analysis Modules

### 1. Data Cleaning & Integrity (Task 2)
* **Zero-Null Validation:** Confirmed a 100% complete dataset (9,994 records), ensuring statistical reliability.
* **Temporal Standardization:** Converted string-based dates to `datetime64` for accurate time-series operations.

### 2. Feature Engineering (Task 3)
* **Time-Aware Dimensions:** Extracted Year/Month to identify seasonal cycles.
* **Profit Margin Logic:** Created normalized efficiency metrics to compare different product scales.

### 3. Business Intelligence & Aggregation (Tasks 4 & 5)
* **Category Dominance:** Analyzed revenue concentration across Technology, Office Supplies, and Furniture.
* **Regional Efficiency:** Identified the **West Region** as the primary profit engine, contributing 3x more profit than the Central region.
* **Segment Growth:** Unearthed a **77% growth rate** in the Home Office segment, signaling a shift in customer behavior.

### 4. Relational Data Modeling (Task 6)
* **Database Simulation:** Demonstrated schema normalization by splitting and merging transaction and product tables, identifying "Join Explosion" risks with non-unique keys.

### 5. Data Visualization (Task 7)
* **Sales Trends:** Multi-year line charts showcasing cyclical Q4 peaks.
* **Profitability Mix:** Bar and Pie charts illustrating geographic and segment-based revenue distribution.

<img width="1157" height="529" alt="image" src="https://github.com/user-attachments/assets/fabd427f-4b56-4480-86ae-0c81dccb8db4" />

---

## 💡 Strategic Insights (Task 8)

| Metric | Finding | Strategic Recommendation |
| :--- | :--- | :--- |
| **Most Profitable** | **Technology** | Prioritize inventory for high-margin tech items over heavy furniture. |
| **Weakest Link** | **Central Region** | Audit logistics and discounting strategies to fix the "Profit Leak." |
| **Hidden Loser** | **Tables Sub-Category** | Re-evaluate shipping fees or discontinue loss-leading furniture items. |
| **Future Trend** | **Home Office Surge** | Capitalize on the 77% growth in remote-work equipment. |

---

## 📊 Visualizations Summary
* **Line Chart:** Monthly Sales Trends (2014-2017)
* **Bar Charts:** Category Revenue & Regional Profitability
* **Pie Chart:** Customer Segment Distribution (Consumer dominance at 50.6%)



---

## 🚀 How to Use
1. **Clone the repo:** `git clone [https://github.com/VICO-27/Superstore-EDA.](https://github.com/VICO-27/CSEC-ASTU-Data-Science-Bootcamp.git`
2. **Dataset:** Ensure `Sample - Superstore.csv` is in the root directory.
3. **Execution:** Open the `.ipynb` file in Colab or Jupyter and run all cells to reproduce the findings.

---

**Developed by:** Ashenafi Deresa  
*Aspiring Data Scientist | CSE Student @ ASTU*
