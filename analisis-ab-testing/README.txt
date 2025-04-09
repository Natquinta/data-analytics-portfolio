# Data-Driven Desicions: Online Store A/B Test Analysis
In this project an A/B test analysis will be used with a Mann Whitney U-test to conclude if the results from the test show significant difference between the groups. We will consider an alpha value of 5%.

## Objectives
1. Prioritize the given hypothesis according to ICE and RICE frameworks to increase revenue.
2. Analyze the results of the A/B test by revenue, number of orders by user and order size to determine the difference between both test groups.
3. Determine the significance of the results of the test to assess weather it is necessary to continue with it or stop it.

## Technologies Used
- **Python**: Pandas, Matplotlib, Scipy, Seaborn, Numpy
- **Jupyter Notebook**: Interactive environment for analysis.
- **CSV Files**: Contain user orders, hypothesis and visits to the online store.

## Key Steps
1. **Exploratory Analysis**:
   - Assessed the quality of the dataset and summarized its structure, correct and clean data of duplicates, nulls and incorrect data types.
2. **Hypothesis Priorization**:
   - Calculate the ICE and RICE score according to the frameworks in order to assess which hypothesis have more relevance.
3. **Statistical Testing**:
   - Calculate cumulative metrics for number of orders and order size for each group in the A/B test. Plot the different metrics for both groups to make a comparison.Filter abnormal users and calculate the statistical difference between both groups.

## Results
The analysis confirms that:
-The raw data showed significant differences between the groups' order counts. However, filtering the data revealed significant differences, and the anomalies changed their behavior. Regarding profits, in both cases (raw data and filtered data), no significant differences were found between the groups.
