## Overview
This repository contains the `Sale.pbix` Power BI report designed to provide comprehensive insights into sales performance. The report visualizes various metrics to aid in the analysis of sales trends, customer behavior, and product performance over time.

## Features
- **Sales Trends**: Visualizes sales data over time to identify trends and seasonal patterns.
- **Customer Analysis**: Segments customers based on purchasing behavior and demographics.
- **Product Performance**: Tracks product sales to determine high performers and underperformers.
- **Geographic Insights**: Analyzes sales data across different regions to identify geographical strengths and weaknesses.

## Data Sources

The `Sale.pbix` Power BI report utilizes data from the following source:

- **North America Retail Supply Chain Sales Analysis Excel File**: This Excel file contains detailed transactional data related to sales performance across various retail chains in North America. The file is structured into multiple sheets, each providing specific insights:
  - `SalesData`: Includes detailed records of sales transactions, featuring columns such as date, product ID, quantity sold, and total sales amount.
  - `ProductDetails`: Provides information about each product, including product name, category, and price.
  - `CustomerDemographics`: Contains demographic information about customers, such as age, gender, and location.
  - `StoreInformation`: Lists details about each store location, including store ID, address, and region.

### Using the Excel Data in Power BI

To ensure accurate and up-to-date analysis, the Power BI report is directly linked to this Excel file. Changes made to the Excel data can be refreshed in the Power BI report to reflect new insights and trends. Here’s how to connect to and refresh data from the Excel file:

1. **Open the `Sale.pbix` file in Power BI Desktop.**
2. **Navigate to the 'Home' tab and click on 'Transform Data' to open Power Query Editor.**
3. **In the Power Query Editor, you can see the queries pulling data from the Excel file. Ensure the path to the Excel file is correct.**
4. **After verifying or editing the data connections, close the Power Query Editor and click 'Refresh' on the Home tab to update the data in the report.**

This setup allows for dynamic updates and deep dives into the sales performance metrics, helping stakeholders make informed decisions based on the latest data.

## Installation

Ensure you have Power BI Desktop installed on your computer. You can download it from the [official Microsoft website](https://powerbi.microsoft.com/en-us/desktop/). After installation, follow the steps listed in the Usage section to open and interact with the Power BI report.

## Usage

Open the `Sale.pbix` file with Power BI Desktop, and use the 'Refresh' button in the 'Home' tab to ensure all data is up-to-date. Interact with the report's visuals to explore different dimensions of the data, such as sales trends, customer demographics, and product performance.

## Prerequisites
To view and interact with the `Sale.pbix` file, you will need:
- Microsoft Power BI Desktop (latest version recommended)
- Access to the data sources mentioned above

## Installation
1. Download and install Power BI Desktop from the [official Microsoft website](https://powerbi.microsoft.com/en-us/desktop/).
2. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/sales-analysis.git
Navigate to the repository folder and open the Sale.pbix file with Power BI Desktop.
Usage
Upon opening the report in Power BI Desktop, you may need to:

Refresh the Data: Go to the 'Home' tab and click 'Refresh' to load the most recent data from the connected sources.
Interact with the Visuals: Click on different elements in the visuals to drill down into specific metrics or adjust filters to customize the data views.
Contributing
Contributions to enhance this report or add new features are welcome. Please fork the repository, make your changes, and submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Authors
[Hàng Tuấn Kiệt]
