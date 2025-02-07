# ONLINE-RETAIL-STORE-ANALYSIS
This project utilizes Power BI to analyze transactional data from an online retail store, providing insights into sales trends, customer behavior, and regional demand.
After importing the dataset into Power BI, data cleaning and transformation were performed using Power Query. This involved handling missing values, correcting date formats, removing duplicates, and standardizing fields to ensure data consistency.

##  Project  Objectives:
The business has been performing well and the management wants to analyse what the major contributing factors are to the revenue so they can strategically plan for next year.
The leadership is interested in viewing the metrics from both an operations and marketing perspective. Management also intends to expand the business and is interested in seeking guidance into areas that are performing well so they can keep a clear focus on what’s working. They would also like to view different metrics based on the demographic information that is available in the data.

## Data Used
-	<a href="https://www.theforage.com/virtual-experience/MyXvBcppsW2FkNYCX/tata-group/data-visualisation-p5xo/creating-effective-visuals">Dataset</a>

##  Key Problems & Questions
1 **Revenue Trends** : How does revenue fluctuate monthly, and why do seasonal trends occur (especially in 2011)? 
 
2 **Top Countries by Revenue** : Which 10 countries generate the highest revenue, excluding the UK? How does revenue compare to the quantity sold? 

3 **Top 10 Customers** : Who are the top 10 revenue-generating customers, ranked from highest to lowest? 

##  Data Cleaning & Transformation
- **Data Validation:** Ensured that **Quantity is not less than 1** and **Price is not less than 0**.
- 
- **Data Formatting:** Standardized **data types** and **text format** for consistency.
- 
- **New Column (Revenue):** Created using **DAX calculations** in Power BI (**Revenue = Quantity × Unit Price**).


4 **Regional Demand Analysis** : Which countries (excluding the UK) have the highest demand, supporting business expansion opportunities? 
