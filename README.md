# Сonsulting Сontracts Analysis
## Project Overview
This project focuses on analyzing the financial performance of a consulting services company over the past year. By examining key metrics such as contract revenues, net profit, expense-to-revenue ratio, and the contribution of individual contracts, the goal is to gain insights into the company's operational efficiency, identify top-performing contracts, and assess overall profitability trends. Contracts are just a part of the company's revenue-generating activities; in addition to this, the company also performs other tasks and provides services that contribute to its overall financial results.

## Key Insights:
- **Net income** for the year is **$873,022**. This is a positive result, indicating that the company was able to make a profit for the year. However, net income is less significant compared to income and expenses, so it is important to consider other indicators.

- **Contract Contribution: 30.69%** is the percentage of income that is provided by contracts. That is, only a third of the company's income comes from contracts. This is important because it may indicate the need to increase the share of income from contracts for a more stable financial result.

- **Profit from Contracts: -1,132,600** - the company had a loss from contracts. This suggests that contract activity alone is not enough to cover all of the company's existing expenses. Therefore, this indicator is worth examining in more detail because the company also has other activities.

- **Expense-to-Revenue Ratio: 60%** is the percentage of operational costs to income. This is a fairly high indicator, indicating that more than half of the company's income is spent on operating costs and various expenses. A high Expense-to-Revenue Ratio may be a signal that you need to optimize your expenses to increase your profitability.

- **Cost Optimization:** The company should focus to reduce Expense-to-Revenue Ratio and increase your profitability. This may include reviewing your operating expenses, reducing your miscellaneous expenses.

- **Increase your contract share:** Since the Contract Contribution is only 30.69%, company can work on increasing the contract share, including by attracting more profitable contracts or optimizing existing ones, reducing the execution costs, or increasing the contract profit margin.

## Data Sources
Contracts Data: the primary dataset used for this analysis is the "Contracts.xlsx" containing comprehensive monthly financial details for the one year. This dataset provides a detailed breakdown of the company's contracts and related financial metrics. Each record represents a monthly summary of contract performance with the following key attributes:
- **Contract Amounts:** total value of contracts executed within the month;
- **Revenue:** income generated from the contracts;
- **Operational Expenses:** costs incurred in the fulfillment of contract obligations;
- **Miscellaneous Expenses:** additional expenses not directly related to core operations.

## Tools
- Excel - Calculation & Data Analysis
- Tableau - Calculation & Data Analysis, Data Visualization

## Data Preparation and Quality Improvement
**1. Enhanced Data Quality:** Before analyzing the data, ensured consistency by adjusting column formats to align with the data types, such as standardizing date formats, converting numerical columns to appropriate formats, and ensuring text fields were uniform.

**2. Net Profit:** Calculated by subtracting both operational and miscellaneous expenses from total revenue, providing a clear picture of the company's overall profitability.

**3. Contract Contribution:** Calculated by determining the percentage contribution of each contract’s revenue to the total yearly revenue. It helps to identify the most impactful contracts on overall performance.

**4. Calculated Profit from Contracts:** Calculated by subtracting total expenses (operational and miscellaneous) from revenue of contracts for each month. This metric highlights the net profitability of contracts of each month.

**5. Growth Rate:** Calculated by comparing monthly revenue changes to evaluate the percentage increase or decrease in performance over time. This metric provides insights into revenue trends and business growth dynamics.

**6. Expense-to-Revenue Ratio:** Calculated by dividing operational costs by total revenue, providing insights into the efficiency of the company's spending relative to its earnings.

## Analysis Questions
- Contracts and Revenue Amounts: What is the revenue for contracts of each month?
- Revenue Trends Over Time: How do contract revenues and expenses trend over different months during the year?
- Profitability Trends: How does net profit change over different months?
- Contracts Contribution by Revenue: What is the percentage contribution of contracts each month to the revenue?
- Expense-to-Revenue Ratio: What is the expense-to-revenue ratio for contracts of each months?
- Revenue vs Total Costs: How do the total revenue and total costs compare across different months?
  
## Visualization
**1. Contracts and Revenue Amounts. Revenue Trends Over Time:**

**1.1. Correlation between revenues and contracts.** Analysis of the relationship between revenues and contract amounts indicates a dependence between them. The graph shows that the company receives income not only from contracts. At the same time, the analysis also emphasizes the need to diversify sources of income.

**1.2. Trends in revenues and contracts.** During the year, the company's revenues show significant fluctuations. For example, August and December stand out as months with the highest revenues and contract amounts. In August, the company reached the highest level of revenues ($500), while the amount of concluded contracts amounted to $148,700. In December, although the revenue was slightly lower ($455), the amount of contracts was even higher — $161. Conversely, there are places with insignificant contract amounts in February $25, March $0, July $25.

**1.3. Seasonal and cyclical fluctuations.** The dynamics of revenues and contracts also indicate the presence of seasonal or cyclical fluctuations. For example, every two months the contract amounts are higher, and then two months are followed by smaller amounts and one month of lower revenues, indicating a likely decrease in business activity in attracting new clients.

![image](https://github.com/user-attachments/assets/6236f59c-1b08-472a-9583-069a1d142279)

**2. Profitability Trends:** 
The share of revenues provided by contracts varies significantly by month. This indicates an unevenness of contract activity: from 0% in March to 205.37% in September, with an average value of about 46.53%. In some months (January, February, July, August, October), contracts covered less than 50% of revenues, which indicates dependence on other sources. In June, September and November, contracts provided the majority of revenues, reaching peak values.

![image](https://github.com/user-attachments/assets/3035ced9-5cec-4577-9144-a8ee945db7ae)

**3. Expense-to-Revenue Ratio:**
On average, operational costs exceed revenues (101.92%). In January (106%), March (173%) and September (405%), expenses exceeded revenues, with the largest excess in September. In other months, the company operated profitably, with the best performance recorded in December (16%) and August (36%), when expenses were significantly lower than revenues.
![image](https://github.com/user-attachments/assets/b5671c6f-2903-43ab-85b9-10890ceddc9d)

**4. Revenue vs Total costs:**
Miscellaneous Expenses are also irregular, with expenses ranging from $0 in March, April, June, July, and October to the following amounts in May ($60,100), November ($67,800), and December ($100,000). This may indicate large one-time expenses that are additional to operating expenses.
![image](https://github.com/user-attachments/assets/b3ff7e71-36c6-42a2-84bf-e5c69daa08bd)

