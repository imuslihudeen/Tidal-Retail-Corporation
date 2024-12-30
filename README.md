# Tidal-Retail-Corporation
## Problem Statement

This dashboard helps Tidal, a leading retail corporation specializing in office supplies, to optimize its operations and investment strategies across four regions in the United States. The dashboard assist the company  to use data-driven decision making for Product Category Prioritization: Identify the top two product categories in each region to prioritize for further investment, ensuring continued revenue growth and alignment with regional preferences and Regional Viability: Determining whether any region should be discontinued or restructured due to underperformance or other strategic factors


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : In the report view, under the view tab, theme was selected.
- Step 5 : Multi card visuals were added to the canvas, representing Sales, projected sales, profi and projected profit.
        
           Although, by default, while calculating average, blank values are ignored.

 Step 6 : New measure was created to find projected sales and projected profit.

       % Projected Sales = SUM(DIVIDFacts[Sales])1.40

         % Projected Profit = SUM(DIVIDFacts[Profit])1.20


Following DAX expression was written for the same,
        
A Multi card visual was used to represent count of customers.

![Tidal Corporation Projected Values](https://github.com/user-attachments/assets/b0951a14-8893-44d9-91cd-72aefb59d879)

- Step 7 : A bar chart was also added to the report design area representing the top profit.

![Top Profit](https://github.com/user-attachments/assets/9f513b97-4d52-48f7-8353-7eae2b22648c)

- Step 8 : A bar chart was also added to the report design area representing the top sales.

![Top Sales](https://github.com/user-attachments/assets/0279f373-3a98-45a4-82f0-578292b6de10)

- Step 9 : A bar chart and a donut chart was also added to the report design area representing the top subcategory and ship mode.

![Top_subcategory_and_ship_mode](https://github.com/user-attachments/assets/7319337a-5141-4e69-a94d-d39bf79bc0d8)


- Step 10 : A bar chart  and donut chart was also added to the report design area representing profit by category segment and ship mode.

![Top_subcategory_and_ship_mode](https://github.com/user-attachments/assets/49c4b2a9-04eb-4ea7-985a-dadb74c35d19)


- Step 11 : A bar chart was also added to the report design area representing the profit and sales by category.

![Profit_and_sales_by_by_category](https://github.com/user-attachments/assets/29edfae7-3dac-4569-8d34-445e58dbbdc9)
 

# Snapshot of Dashboard (Power BI Service)

![Snapshot of Dashboard](https://github.com/user-attachments/assets/a8cf9e9e-593a-49a1-8c77-b40d30652d96)
 

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following recommendations can be drawn from the dashboard;


1. The top two product categories to further invest in by Tidal should be Technology and Office supplies since they have amassed the largest profits for the company overtime.

2. The Southern region recorded the  lowest sales for product categories amongst the regions as such sales in the region should be shutdown pending further feasibility studies by the sales team.

3. Incentives/Gift should given to Top customers who have been consistent with their patronage.
