Global Superstore Profit Driver Analysis
Project Overview

This project analyzes the Global Superstore dataset to identify the key factors that influence profitability and to provide practical, data-driven recommendations for improving business performance. The main objective of this analysis is to understand what drives profit and how the company can increase profitability while reducing losses.

To achieve this, the project combines Excel, Tableau, and Python to perform dashboard analysis, visual exploration, statistical validation, and machine learning modeling.

Problem Statement

The primary question addressed in this project is:

What factors drive profit, and how can the business improve profitability through operational improvements?

The analysis focuses on understanding the impact of discount strategy, shipping cost, customer behavior, product category performance, and regional differences on overall profit.

Dataset Description

The Global Superstore dataset contains transactional sales data, including:

Sales

Profit

Discount

Shipping Cost

Shipping Mode

Customer Segment

Product Category

Region and State

Order-level information

Additional calculated variables were created during analysis, including profit margin, discount bands, shipping days, and loss indicators.

Tools and Technologies Used

Microsoft Excel was used to build an interactive operational dashboard and analyze profitability at different levels.

Tableau was used to create visual dashboards for trend analysis, regional performance, and state-level comparison.

Python was used for statistical analysis, hypothesis testing, correlation analysis, and machine learning modeling. Key libraries used include Pandas, NumPy, Matplotlib, SciPy, and Scikit-learn.

Excel Dashboard Analysis

The Excel dashboard provides a detailed operational view of the business.

Key performance indicators show total sales of approximately 12.6 million dollars and total profit of 1.46 million dollars, resulting in a profit margin of 11.61 percent.

The discount analysis reveals that profit decreases significantly as discount increases. Discounts above 20 percent frequently lead to losses, indicating that excessive discounting directly reduces profitability.

Shipping mode analysis shows that Standard Class shipping generates the highest profit because it minimizes operational cost. Faster shipping options reduce margin due to higher logistics expenses.

Customer-level analysis indicates that some customers generate significantly higher profit than others. Retaining high-profit customers through improved service and personalized engagement is more effective than offering large discounts.

Category analysis shows that Technology products generate the highest profit, while Furniture generates comparatively lower margins.

Tableau Dashboard Analysis

The Tableau dashboard provides a broader business overview, including:

Sales and profit trends over time

Regional and state-level profitability

Identification of top and bottom performing states

Trend analysis helps identify seasonal performance patterns and supports better inventory planning. Regional analysis highlights high-profit areas for expansion and low-profit areas that require operational adjustments.

Python Statistical and Machine Learning Analysis

Python was used to validate insights obtained from dashboard analysis.

A scatter plot of discount versus profit margin showed a strong negative relationship, confirming that higher discounts reduce profit margin.

A statistical hypothesis test produced a p-value of 0.0, confirming that the impact of discount on profit is statistically significant.

A Random Forest regression model was applied to determine the most important factors affecting profit. The results show that sales volume has the strongest influence, followed by discount and shipping cost. This confirms that increasing profitable sales, controlling discount levels, and managing shipping costs are critical to improving profitability.

Key Findings

Profitability is primarily driven by sales performance, discount strategy, and shipping cost management.

Excessive discounting directly leads to reduced profit and frequent losses.

Cost-efficient shipping methods improve margin stability.

High-margin product categories should receive greater marketing focus.

Customer-level analysis reveals the importance of retaining high-profit customers through service improvements rather than price reductions.

Business Recommendations

To increase profitability, the company should implement controlled and targeted discount strategies rather than universal discounting.

Shipping policies should prioritize cost-efficient options, with express shipping offered only for high-value orders.

Marketing efforts should focus on high-margin product categories such as Technology.

Customer retention strategies should emphasize service quality and personalization instead of aggressive price reduction.

Operational decisions should be guided by data analysis rather than intuition.

Repository Structure

This repository includes:

Excel dashboard file

Tableau dashboard file

Python Jupyter Notebook containing full analysis

Presentation materials

Project documentation

Conclusion

This project demonstrates how combining Excel dashboards, Tableau visualizations, and Python statistical modeling can transform raw transactional data into actionable business insights.

The analysis confirms that profitability is strongly influenced by sales volume, discount control, and shipping cost management. By implementing data-driven operational improvements, the company can increase profit margin, reduce losses, and improve overall business performance in a sustainable manner.
