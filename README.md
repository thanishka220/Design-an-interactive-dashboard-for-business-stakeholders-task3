# Sales of Financial Products Dashboard

## Project Overview
This project involves designing an interactive dashboard using Tableau to analyze the sales performance of financial products handled by various agents. The dashboard provides key insights to business stakeholders, enabling data-driven decisions to improve sales strategies and agent productivity.

## Dataset
- **Source:** [Sales of Financial Products Dataset on Kaggle](https://www.kaggle.com/datasets/pyithan/sales-of-financial-products)
- **Key Fields Used:**
  - `Agent_Name`: Name of the sales agent
  - `ProductSold`: Number of products sold
  - `CallID`: Unique identifier for each call
  - `PickedUp`: Indicates if the call was answered
  - `Duration`: Duration of the call in seconds

## Data Preparation
- Cleaned missing and inconsistent values.
- Created a **Dummy Date** field using `CallID` to enable time-series analysis since the dataset did not include a date field.
- Created calculated fields such as **Profit Margin** (if applicable).

## Dashboard Features
- **Bar Chart** displaying total products sold by each agent.
- **KPI Cards** summarizing total products sold.
- **Pie Chart** showing the distribution of products sold by agent.
- **Line Chart** illustrating sales trends over time based on the dummy date field.
- Interactive filters and slicers for dynamic data exploration.
- Consistent color themes applied for better readability.
- Navigation buttons for enhanced user experience.

## Tools and Technologies
- Tableau Desktop / Tableau Public for dashboard creation and visualization.
- Dataset in CSV format from Kaggle.

## How to Use
1. Open the Tableau workbook file (`.twb` or `.twbx`).
2. Explore the dashboard to view sales trends and agent performance.
3. Use filters to analyze specific agents or product categories.
4. Click on visual elements to interact with the data dynamically.

## Insights and Outcomes
- Identified top-performing agents based on product sales.
- Analyzed product sales distribution across agents.
- Observed sales trends over time using the dummy date field.
- Provided actionable insights to guide sales strategy improvements.


## Author
A.Thanishka


