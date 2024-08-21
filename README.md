# Analysis-of-Food-Item-Prices-in-Malaysia-for-the-Year-2022
This project aims to analyze the trends and fluctuations in the prices of various food items across Malaysia throughout the year 2022. The data is segmented by month and covers a wide range of food categories, providing insights into price movements influenced by factors such as seasonality, supply chain issues, and economic conditions. 

The dataset used in this analysis comprises monthly records of food item prices across Malaysia for the year 2022. Each month's data is stored in a separate file, and there is an additional dataset that contains food codes used for categorization.

### Files in the Repository

- **data**
  - `pricecatcher_2022-01.csv` - Food prices for January 2022.
  - `pricecatcher_2022-02.csv` - Food prices for February 2022.
  - `pricecatcher_2022-03.csv` - Food prices for March 2022.
  - `pricecatcher_2022-04.csv` - Food prices for April 2022.
  - `pricecatcher_2022-05.csv` - Food prices for May 2022.
  - `pricecatcher_2022-06.csv` - Food prices for June 2022.
  - `pricecatcher_2022-07.csv` - Food prices for July 2022.
  - `pricecatcher_2022-08.csv` - Food prices for August 2022.
  - `pricecatcher_2022-09.csv` - Food prices for September 2022.
  - `pricecatcher_2022-10.csv` - Food prices for October 2022.
  - `pricecatcher_2022-11.csv` - Food prices for November 2022.
  - `pricecatcher_2022-12.csv` - Food prices for December 2022.
  - `lookup_item.csv` - A reference file containing food item codes and their corresponding descriptions.
 
- **report**
  - `foodpricefullyear2.pbix` - Power BI report file containing the visual analysis of the data.

## Power BI Report Features

### Interactive Line Chart by Food Item

One of the key features of the Power BI report is an interactive line chart that allows you to view the price trend of individual food items over the year 2022. Here's how you can use this feature:

1. **Selecting a Food Item:**
   - On the report page containing the line chart, you'll find a **dropdown list** on the left side. This list includes all the food items available in the dataset.
   - Click on the dropdown and select the food item you are interested in.

2. **Viewing the Line Chart:**
   - Once you select a food item, the line chart will automatically update to display the price trend for that specific item across all months in 2022.
   - The X-axis represents the months (from January to December), and the Y-axis represents the price of the selected item.
   - You are also able to pick the timeline of your choice (e.g viewing the first quantile months : January to March)

3. **Interactivity:**
   - The chart is fully interactive, meaning you can hover over the line to see exact price values for each month.
   - You can switch between different food items at any time by selecting a different item from the list, and the chart will update accordingly.

This feature allows for easy comparison and analysis of price trends for individual food items, helping to identify patterns, spikes, or drops in prices throughout the year.
