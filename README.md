# 🛒 E-Commerce Customer Behavior and Purchase Intention Analysis

## 📌 Project Overview

This project analyses e-commerce browsing session data to understand customer behaviour and identify patterns associated with purchase intention.

Using Python, the project explores how visitor type, browsing activity, page visits, browsing duration, and monthly trends relate to purchase outcomes.

## 🎯 Objectives

* Understand customer browsing and purchasing behaviour.
* Identify patterns associated with successful purchases.
* Compare purchase percentages across visitor types and months.
* Examine relationships between page visits, browsing duration, and purchase outcomes.
* Present findings through visualizations and recommendations.

## 📂 Dataset

**Dataset:** [Online Shoppers Purchasing Intention Dataset](https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention)

The original dataset contains 12,330 browsing sessions and 18 columns.

After removing 125 duplicate records, the cleaned dataset contained **12,205 sessions**.

## 🛠️ Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly Express
* Jupyter Notebook

## 🔍 Project Workflow

### 1. Data Preprocessing

* Checked missing values, data types, and duplicate records.
* Removed duplicate records.
* Standardized column names and month values.
* Created features for total pages visited, browsing activity, and total page duration.

### 2. Exploratory Data Analysis (EDA)

* Analysed purchase and non-purchase sessions.
* Compared purchase behaviour across visitor types.
* Examined monthly and weekend purchase patterns.
* Explored browsing activity and page duration.
* Investigated correlations between numerical variables.

### 3. Data Visualization

Created 13 visualizations using Matplotlib, Seaborn, and Plotly.

The visualizations include bar charts, line charts, histograms, box plots, scatter plots, a correlation heatmap, a pie chart, violin plots, and a swarm plot.

### 4. Insight Generation and Reporting

Summarized the key findings, prepared a conclusion, and suggested potential ways to improve purchase conversion.

## 📊 Key Findings

* **Purchase Rate:** 15.63% of browsing sessions resulted in a purchase, while 84.37% did not.
* **Visitor Type:** New visitors had the highest purchase percentage at 24.93%, compared with 14.09% for returning visitors.
* **Monthly Trends:** November had the highest purchase percentage at 25.49% among the recorded months.
* **Browsing Activity:** High-activity sessions had a purchase percentage of 23.99%, compared with 5.81% for low-activity sessions.
* **Browsing Behaviour:** Total pages visited and total page duration showed a strong positive correlation.
* **Correlation Analysis:** Bounce rates and exit rates had a strong positive correlation of approximately 0.90.

These findings describe patterns in the dataset and do not establish cause-and-effect relationships.

## 💡 Recommendations

* Investigate why many browsing sessions do not result in purchases.
* Explore ways to engage new visitors and encourage purchases.
* Improve website navigation and product discovery.
* Investigate differences in purchase behaviour across months.
* Conduct further analysis to understand factors associated with purchase conversion.

## 📁 Project Files

* `E-Commerce_Customer_Behavior_Analysis.ipynb` — Jupyter Notebook containing the analysis and visualizations.
* `online_shoppers_intention.csv` — Dataset used for the analysis.
* `Project_SRS_ECommerce_Customer_Behavior_Purchase_Intention.docx` — Project Software Requirements Specification document.

## 📌 Conclusion

This project demonstrates the use of Python for data preprocessing, exploratory data analysis, visualization, and insight generation. The findings provide an understanding of e-commerce browsing behaviour and purchase patterns and identify areas for further investigation.
