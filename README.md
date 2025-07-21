
# Banking-Analytics-Dashboard

## 📊 Credit Card Market Opportunity Dashboard – Mitron Bank
This project presents a comprehensive end-to-end analysis aimed at identifying key market segments for the successful launch of a new credit card by Mitron Bank. It combines Python-based statistical segmentation with Power BI visualizations to provide deep, actionable insights.

## 📁 Project Structure

| File Name                     | Description |
|------------------------------|-------------|
| `Banking_project.pbix`       | Main Power BI Dashboard that presents the final visuals and KPI insights. Designed for top-level management and product strategy teams. |
| `Banking_project.ipynb`      | Python script used for statistical preprocessing, including calculation of quartile-based segmentation thresholds for customer spending categories. |
| `KPI_Measures_Metadata.xlsx` | Contains a list of DAX measures used in Power BI, their definitions, and business logic. Helps users and analysts understand the KPIs driving insights. |
| `New_Table_Creation.xlsx`    | Explains newly created tables and calculated columns in Power BI, including purpose and transformation logic for better data modeling transparency. |
| `problem_statement.pdf`      | Original project brief provided by Mitron Bank, detailing the goal of the pilot analysis, expectations, and target business questions. |
| `Insight Ideas from Tony.pdf`| Supplementary file with suggested insight ideas and directions provided by Peter’s manager, Tony Sharma, to guide the analytics scope and business relevance. |

## 🎯 Objective
Mitron Bank is exploring the launch of a new credit card product and provided a sample dataset of 4,000 customers. The goal is to:

- Understand customer spending, income, and behavior trends.
- Identify key target segments most likely to adopt a credit card.
- Recommend strategic promotions, offers, and positioning based on customer profiles.

## 🔧 Methodology Overview

### Python (Jupyter Notebook)
- Used to calculate quartile-based spend groupings, since the distribution of spending is right-skewed.
- This ensures robust, data-driven customer segmentation instead of simple range-based bins.
- A summary of these quartile thresholds is used to classify customers in Power BI for deeper visual insights.

### Power BI
- Visual dashboard covering customer demographics, income profiles, spending patterns, and income utilization metrics.
- DAX measures and calculated columns are documented in `KPI_Measures_Metadata.xlsx` and `New_Table_Creation.xlsx`.
- The dashboard is designed for executive-level decision-making and insight exploration.

## 📌 Key Features
- **Spending Category Segmentation:** Customers segmented into spending tiers (e.g., Low, Moderate, High, Top) based on total spend using quartile logic.
- **Occupation Insights:** Identifies which professions dominate high-spending categories.
- **Income Utilization Metric:** Highlights customer reliance on income through average monthly spending divided by income.
- **Promotion Targeting Suggestions:** Data-backed recommendations for occupation, age, and category-specific marketing campaigns.

## 🧩 Dashboard Pages
- **Demographic Overview**
- **Income Analysis**
- **Expenditure Insights**
- **Income Utilization Analysis**
- **Summary Report Page**

## 👨‍💼 Target Users
- Mitron Bank’s Strategy Team
- Product and Marketing Managers
- Data Analysts & BI Developers involved in financial services

## 📬 Notes
- This project was developed independently using a dataset and high-level problem statement provided by Mitron Bank. All data preparation, segmentation strategies, statistical modeling, and dashboard development were designed and implemented from scratch. While the business context was predefined, the analytical approach, logic design, and visualization structure were fully customized to deliver actionable insights.

## Preview

