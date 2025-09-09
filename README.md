#customerchurn-Dataanalysis(interactive Dashoard creation using powerbi)
##Project Objectives
The goal is to understand why customers leave (churn) and provide insights to help the business improve retention strategies and reduce churn rate
## Dataset used
-<a href= "https://www.kaggle.com/datasets/blastchar/telco-customer-churn">DataSet</a>


##  Qustions(KPIS)    
-What is the overall churn rate?
-Do customers with shorter tenure churn more than long-term customers?
-Which contract type has the highest churn (month-to-month vs 1-year vs 2-years)?
-Which payment methods are associated with higher churn?
-Are customers with higher monthly charges more likely to churn?
-Churn by gender, age group, region.

-dahsboard Interaction  <a href= "https://github.com/lopnaelsadany/customer-churn-dashboard/blob/main/scrn-churn.png"> view dashboard</a>

 ## Process
 -Data Cleaning (Power Query/Excel)
Checked for missing values and handled nulls.
-Data Transformation (Power Query)
Grouped customers into categories (e.g., Low / Medium / High charges).
Standardized categorical fields (e.g., payment methods).
-Data Modeling (Power Pivot)
Created KPIs and measures using DAX, such as:
Churn Rate = DIVIDE(Churned Customers, Total Customers)
Avg Tenure = AVERAGE(Tenure)
-Visualization (Power BI)
Designed an interactive dashboard with visuals like:
Bar/column charts for churn by contract, payment method, and tenure.
Line charts for churn trend over time.
-Dashboard Delivery
Created a clean, professional layout.
Highlighted key insights with KPIs.

 ## dashboard 
 - <a href= "https://github.com/lopnaelsadany/customer-churn-dashboard/blob/main/scrn-churn.png"> screenshot</a>
## Project Insights
Overall Churn Rate
The churn rate is ~26%, meaning more than 1 out of 4 customers discontinued the service.
Tenure & Churn
Customers who churned stayed for an average of 18 months.
Non-churners stayed longer, with an average tenure of 38 months.
Highest churn happens in the first year of subscription.
Contract Type
Month-to-month contracts have the highest churn (~42%).
1-year contracts show moderate churn (~11%).
2-year contracts retain customers best (~3%).
Payment Method
Customers using Electronic Check had the highest churn (~45%).
Other payment methods (Credit Card, Bank Transfer, Automatic Payments) had significantly lower churn rates.
Monthly Charges
Customers paying higher monthly charges (> $70) are more likely to churn (~40%).
Customers with lower charges have higher retention.
Services & Add-ons
Customers without additional services (like online security or tech support) are more likely to churn.
Bundled services improve retention.
# Conclusion
Encourage customers to switch from month-to-month to long-term contracts by offering discounts or promotions.
Improve service quality for high-paying customers to justify higher monthly charges.
Promote automatic payment methods to reduce churn associated with electronic checks.
Offer bundled packages (internet + phone + security) to increase stickiness.
Focus customer support on new customers within their first year, as they are the most at risk.


                                                                                    



