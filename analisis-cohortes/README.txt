# Business Intelligence: Cohort and User Behavior Analysis for Entretainment Company
Showz's 2017-2018 visit and sales records will be explored to gain insights that will help understand customer behavior and optimize marketing spending based on sales and profit margins.

## Objectives
Describe how customers use the service and when they begin making purchases.
Describe customer behavior and the revenue they bring to the company.
Analyze customer acquisition costs and the revenue that justifies them.

## Technologies Used
- **Python**: Pandas, Matplotlib, Scipy, Seaborn, Numpy
- **Jupyter Notebook**: Interactive environment for analysis.
- **CSV Files**: Contain visits to the online store, costs and order records.

## Key Steps
1. **Exploratory Analysis**:
- Assessed the quality of the dataset and summarized its structure, correct and clean data of duplicates, nulls and incorrect data types.

2. **Reports**:
-SITE VISITS REPORT:
  -On average, there are 907 active users daily, and 23,228 active users weekly and monthly. The weekly engagement rate is 16%, and the monthly engagement rate is 4%. This indicates that 16% of weekly users are active daily on the platform, while 4% of monthly active users are active daily. As this is an event ticketing company, this does not represent a very significant metric, as some users may only use it when there is an event that interests them.
  - Daily visits average 987 per day, taking into account that a user can access the site multiple times. The values ​​were sorted to see the lowest number of visits per day. It is observed that on March 31, 2018, there is only one record, and the day with the most visits was November 24, 2017, with 4,042 visits.

-SALES REPORT:
   -After sorting out the sales by cohorts, it was found that the conversion rate per cohort was highest in the June 2017 group, while it was lowest in April 2018. In the two graphs in the file, we can see a spike in total revenue and LTV in June and September. A deeper analysis is needed to determine what actions may have led to the increase in ticket sales during these months.
  - The heat map shows that cohort retention is always strongest in the first month, i.e., the month of registration, and from there, retention drops significantly. This could be due to the type of events and ticket availability.

- MARKETING REPORT:
  - The graphs show that the highest cost per customer is by far strategy 3. Later, we must calculate this ROMI to determine if the investment has resulted in a good marketing strategy that increases sales. Data on visits, orders, and marketing costs must be combined to align revenue and costs by source. It's also important to analyze the CAC by cohort to better understand the data and customer behavior.
  - Graphs made in the project show the ROMI and CAC comparisons.

## Results
The analysis confirms that:
-In conclusion, considering the analyzed data and graphs, the recommendation would be to invest primarily in strategies 1 and 2, as they generate more revenue at a lower cost, making them more profitable for the company. In this case, as this is a ticket sales platform, there may be customers who only visit the site once or twice to purchase tickets to a specific event they are interested in. An analysis could also be conducted to recommend events that customers would like based on what they have previously viewed or purchased tickets, encouraging them to visit the site more frequently. However, as this is not a site that is monetized by the amount of time a user spends on the page, but rather by completed sales, it is more important to consider sales and marketing conversion metrics in order to close more sales and obtain greater profits.
