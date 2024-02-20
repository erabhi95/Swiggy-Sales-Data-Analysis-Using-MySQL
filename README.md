# SWIGGY Sales Data Analysis

### Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [KPIs Considered](#kpis-considered)
- [Data Cleaning](#data-cleaning)
- [Data Transformation](data-transformation)
- [Data Visualisation](#data-visualisation)
- [Results](#results)
- [Recommendations](#recommendations)

### Project Overview
This is a data analysis project that aims to provide insights into the sales data of a SWIGGY Online Food delivery company. By analysing various aspects of the sales data , we seek to identify trends, make data-driven recommendations, and gain a deeper understanding to enhance the company's performance in terms of growth, efficiency and customer satisfaction.

### Data Sources
The primary dataset used for this analysis are the 'Swiggy Sales Data' excel data , containg detailed information about the sales made by the company.

### Tools
1. Microsoft Excel - For Data cleaning and transformation
2. MySQL -  For querying the data to get insights

### KPIs Considered
- Sales Amount
- Profit Amount
- Order Count
- Category
- Sub-Category
- Ship Mode
- Region
- Segment
- Payment Mode
- State
    
### Data Cleaning
1. Data loading and inspection.
2. Checking for correct data type and formating.
3. Removing blank rows and duplicates from the data.

### Data Transformation
1. Created new columns and measures using DAX queries to get more insights out of the available data which are further used during dashboard creation.
   
### Data Visualisation
1. Created an interactive dashboard using sales data that gives real time information about the sales records as per user's choice.
2. Performed forecasting for next 15 days based on the historic data using Power BI.

### Exploratory Data Analysis
EDA is performed on the Sales data to answer some key questions, such as:
- HOW MANY RESTAURANTS HAVE A RATING GREATER THAN 4.5?
- WHICH IS THE TOP 1 CITY WITH THE HIGHEST NUMBER OF RESTAURANTS?
- HOW MANY RESTAURANTS SELL( HAVE WORD "PIZZA" IN THEIR NAME)?
- WHAT IS THE MOST COMMON CUISINE AMONG THE RESTAURANTS IN THE DATASET?
- WHAT IS THE AVERAGE RATING OF RESTAURANTS IN EACH CITY?
- WHAT IS THE HIGHEST PRICE OF ITEM UNDER THE 'RECOMMENDED' MENU CATEGORY FOR EACH RESTAURANT?
- FIND THE TOP 5 MOST EXPENSIVE RESTAURANTS THAT OFFER CUISINE OTHER THAN INDIAN CUISINE. 
- FIND THE RESTAURANTS THAT HAVE AN AVERAGE COST WHICH IS HIGHER THAN THE TOTAL AVERAGE COST OF ALL    
   RESTAURANTS TOGETHER.
- RETRIEVE THE DETAILS OF RESTAURANTS THAT HAVE THE SAME NAME BUT ARE LOCATED IN DIFFERENT CITIES.
- WHICH RESTAURANT OFFERS THE MOST NUMBER OF ITEMS IN THE 'MAIN COURSE' CATEGORY?
- LIST THE NAMES OF RESTAURANTS THAT ARE 100% VEGEATARIAN IN ALPHABETICAL ORDER OF RESTAURANT NAME
- WHICH IS THE RESTAURANT PROVIDING THE LOWEST AVERAGE PRICE FOR ALL ITEMS?
- WHICH TOP 5 RESTAURANT OFFERS HIGHEST NUMBER OF CATEGORIES?
- WHICH RESTAURANT PROVIDES THE HIGHEST PERCENTAGE OF NON-VEGEATARIAN FOOD?
- Determine the Most Expensive and Least Expensive Cities for Dining:
- Calculate the Rating Rank for Each Restaurant Within Its City

  
### Results
- Majority sales comes from the **Western & Eastern states(~60%)**.
- In west, **California** is the majorily contributing state with **more than 60% of total sales and more than 70% of total profit**.
- In east, **New York** is the majorily contributing state with **more than 40% of total sales and more than 75% of total profit**.
- Normal **Consumers** are the majority contributors to the **sales(~50%) and profit(~45%)** followed by **Corporates** with **sales(~30%) and profit(~30%)**.
- Majority sales happen via **COD and Online payment modes**.
- In **2019, October has the highest profit** despite average annual sales.
- In **2020, March has the highest profit** despite December having highest sales.
- In terms of Category, **Office Supplies and Technology contribute to majority sales(~70%) and profit(~95%)**.
- Top 5 Sub-categories of products in terms of sales are Phones, Chairs, Binders, Storage and Accessories.
- **Standard Class** is the most preferred Shipment Mode **contributing to majority sales(~60%) and profits(~55%)**.
- **Next 15 days sales** values has been forecasted with **confidence interval of 95%** depicts the sales values ranging between **2.2K to 9.4K** vales.

### Recommendations
Inorder to improve “SuperStore” Sales & Profits :
- **California in west and New York in east US should be analysed** specifically to look what's driving the higher sales in these states and the same should be used to revive sales in the Northern and Southern states of the country.
- In terms of payment modes, major spending should be done in **maintaining the Online & Cash On Delivery customers like more cash back schemes,sales offs on transactions** etc can be given.
- **Year end (specially December) is witnessing higher sales, so more offers should be rolled off** during that period of the year. Also, further analysis should be done to generate more profit from the increased sales during that period.
- **Office Supplies & Technologies inventories should always be maintained** properly as they the majority contributors to sales and profits. Also more schemes should be provided to their buyers. In addition to this, **feeback form can be rolled out to the customers of 'Furniture' to see their pain point** and plan further strategies accordingly.
- Since more customers are using **Shipment mode as Standard Class**, if possible, **try to reduce the delivery time period** which is currently 6 days.
- **As per the forecasted values, stocks should be maintained in advance** specially for demanding item categories like Office Supplies & Technologies.

