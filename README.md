# Sales-Analysis-Insight-Dashboard-With-Microsoft-Excel
--------------------------------------------------------

## Project Overview
The Sales Insights Dashboard is a comprehensive analytical tool created using Microsoft Excel. It is designed to offer an in-depth visualization of sales data across various segments, products, and time periods. This dashboard enables stakeholders to quickly grasp key metrics and trends, facilitating informed and strategic decision-making processes.

The Sales Insights Dashboard is an Excel tool that visualizes key sales metrics through interactive charts, including Product vs. Profit, Sales Per Segment, Monthly Sales Trend, and Total Units Sold Per Segment. Filters for country, discount band, and year help stakeholders identify trends and make data-driven decisions.
The workbook "Sales Analysis Insights" consists of four spreadsheets: "Original Data," "Data," "Pivot Table," and "Dashboard." Below is the detailed readme for each spreadsheet, including methods used for data cleaning.

## Sales Analysis Insights

### Spreadsheet: Original Data
#### Description:
The "Original Data" sheet contains raw sales data collected from various sources. This data is unprocessed and may include inconsistencies or errors that must be addressed before analysis.

#### Data Cleaning Methods:
1. **Removing Duplicates**: Identified and removed any duplicate rows to ensure that each sales transaction is unique.
2. **Handling Missing Values**: Checked for missing values in essential columns such as Product, Segment, and Sales. Imputed missing values where appropriate or removed incomplete rows.
3. **Standardizing Formats**: Ensured consistency in date formats, numerical values, and text fields. For example, converted all date entries to a uniform format and ensured numerical fields like Sales and Profit were correctly formatted.
4. **Correcting Errors**: Identified and corrected any obvious data entry errors, such as incorrect product names or segment classifications.

### Spreadsheet: Data
#### Description:
The "Data" sheet contains cleaned and processed sales data, ready for analysis. This sheet is derived from the "Original Data" sheet after applying data cleaning methods.

#### Data Cleaning Methods:
1. **Normalization**: Standardized data entries to ensure uniformity across the dataset. This includes ensuring consistent naming conventions for products and segments.
2. **Filtering**: Removed irrelevant or outlier data that could skew the analysis. For example, sales records with zero or negative values were filtered out.
3. **Transformation**: Converted categorical data into appropriate formats for analysis. For instance, segment names were standardized, and date fields were split into Year, Month, and Day for easier analysis.
4. **Aggregation**: Summarized sales data where necessary, such as calculating total sales and profit by product and segment.

Here is the Cleaned data
![Cleaned sales data](https://drive.google.com/uc?id=1wJxIRKIC2v0RYyqU7c_95nWi8e6Uba_M)

## Data Cleaning Summary:
1. **Removing Duplicates**: Ensured uniqueness of sales transactions.
2. **Handling Missing Values**: Addressed incomplete data entries.
3. **Standardizing Formats**: Ensured consistency in data representation.
4. **Correcting Errors**: Fixed obvious data entry mistakes.
5. **Normalization**: Standardized data entries for uniformity.
6. **Filtering**: Removed irrelevant or outlier data.
7. **Transformation**: Converted data into appropriate formats for analysis.
8. **Aggregation**: Summarized data for easier analysis and visualization.

This comprehensive approach to data cleaning and preparation ensures that the sales data is accurate, consistent, and ready for in-depth analysis and visualization.

### Spreadsheet: Pivot Table

Here is the Pivot Table
![Pivot Table](https://drive.google.com/uc?id=1cHhg6OAN8GcCor37HLooGShRhzMakFuC)

The "Pivot Table" sheet contains various pivot tables created from the cleaned data. These tables provide a summarized view of the sales data, breaking it down by different dimensions such as product, segment, and time period.

#### Key Features:
1. **Sales by Product**: A pivot table showing total sales and profit for each product.
2. **Sales by Segment**: A pivot table summarizing sales and profit across different market segments.
3. **Monthly Sales Trend**: A pivot table displaying sales trends over each month, enabling analysis of seasonal patterns.
4. **Segment-wise Product Performance**: A pivot table detailing the performance of each product within different segments.


# Sales Insights Dashboard 

Here is the Sales insight dashboard:

![Dashboard Image](https://drive.google.com/uc?id=1_PDxIf7qAr2_bts44x03BbpycZhrSLod)

PDF Format
[Download Dashboard PDF](https://drive.google.com/uc?id=1JxqqpFiuY6GfLOCB0Fk1kC-AwRm7Lgos&export=download)

## Dashboard Components

### 1. Product vs. Profit Chart
- **Description**: The Product vs. Profit Chart is a bar graph that delineates the profit generated by each product. This visual representation helps in identifying the most and least profitable products within the portfolio.
- **Products Included**: The chart encompasses a range of products including Paseo, VTT, Amarilla, Velo, Montana, and Carretera.
- **Profit Metric**: The metric used is the sum of profit for each product.
- **Usage**: This chart is instrumental in strategic planning, allowing stakeholders to focus on high-profit products and reconsider strategies for less profitable ones.

### 2. Sales Per Segments Pie Chart
- **Description**: The Sales Per Segments Pie Chart provides a visual breakdown of sales distribution across different market segments. Each segment’s share of total sales is represented as a percentage of the whole.
- **Segments Included**: The segments covered in this chart are Channel Partners, Enterprise, Government, Midmarket, and Small Business.
- **Percentage Distribution**:
  - Channel Partners: 1%
  - Enterprise: 17%
  - Government: 44%
  - Midmarket: 2%
  - Small Business: 36%
- **Usage**: This pie chart is useful for quickly identifying the dominant market segments and assessing the market penetration of each segment.

### 3. Monthly Sales Trend Line Chart
- **Description**: The Monthly Sales Trend Line Chart tracks the sales performance over each month of the year, providing a clear visualization of sales trends and patterns.
- **Time Period**: The chart covers a complete year, from January to December.
- **Sales Metric**: It displays the total sales for each month.
- **Usage**: This chart is essential for recognizing seasonal trends, peak sales periods, and any anomalies in monthly sales performance. It aids in forecasting and seasonal strategy planning.

### 4. Total Units Sold Per Segment Bar Chart
- **Description**: This bar chart presents the total number of units sold per segment for different products. It offers a segmented view of product performance.
- **Segments Included**: The chart covers Channel Partners, Enterprise, Government, Midmarket, and Small Business segments.
- **Products Included**: Products displayed include Amarilla, Carretera, Montana, Paseo, Velo, and VTT.
- **Usage**: This visualization is helpful in analyzing the sales volume of each product within various market segments, facilitating targeted marketing and sales strategies.

## Additional Filters
To enhance data analysis and provide more specific insights, the dashboard includes the following filters:
- **Country**: Allows filtering sales data by geographical region.
- **Discount Band**: High, Medium, Low, None - to analyze the impact of discount strategies on sales.
- **Year**: 2018 and 2019 - to compare yearly performance.
- **Segment**: Channel Partners, Enterprise, Government, Midmarket, Small Business - for segment-specific analysis.

## Usage Instructions

1. **Opening the Dashboard**: Access the Excel file containing the dashboard to utilize all visualizations and filters.
2. **Interacting with Charts**: Engage with different segments of the charts by clicking on them to filter and delve deeper into specific data points.
3. **Using Filters**: Apply the provided filters to narrow down the data based on specific criteria such as country, discount band, and year.
4. **Analyzing Trends**: Use the visualizations to identify trends, patterns, and anomalies in the sales data, which will aid in strategic decision-making and optimization of sales strategies.

## Conclusion
The Sales Insights Dashboard is a powerful and versatile tool for visualizing and analyzing sales performance. By leveraging the different charts and filters available, users can derive valuable insights from their sales data. This enables strategic decisions and helps optimize sales approaches, ensuring a data-driven path to achieving business objectives.

For any further assistance or inquiries, please refer to the accompanying documentation 
