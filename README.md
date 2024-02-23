# SWIGGY Sales Data Analysis

### Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [KPIs Considered](#kpis-considered)
- [Data Cleaning](#data-cleaning)
- [Data Querying](#data-querying)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)

### Project Overview
This is a data analysis project that aims to provide insights into the sales data of a SWIGGY Online Food delivery company. By analysing various aspects of the sales data , we seek to identify trends, gain a deeper understanding of the data and make data-driven recommendations to enhance the company's performance in terms of growth, efficiency and customer satisfaction .

### Data Sources
The primary dataset used for this analysis are the 'Swiggy Sales Data' excel data , containg detailed information about the sales made by the company.

### Tools
1. **Microsoft Excel** - For Data cleaning and transformation
2. **MySQL** -  For querying the data to get insights

### KPIs Considered
- Cost per cuisine
- Menu Category
- Sales Item
- Price per Item
- Item Category (Veg or Non-Veg)
- Restaurant Name
- Restaurant Rating
- City
    
### Data Cleaning
1. Data loading and inspection.
2. Checking for correct data type and formating.
3. Removing blank rows and duplicates from the data.

### Data Querying
Used MySQL (Subqueries, CTEs) to query sales data across restaurants, cities etc to answer EDA questions and gain insights. 

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
- There are **13 restaurants that have rating more than 4.5**. 
- **Bangalore** has the highest number of restaurants.
- **North Indian, Chinese** is the most common cuisine among the restaurants.
- **Average rating** of restaurants in **Bangalore is 4.1** and in **Ahmedabad is 4**.
- Following are the **Top 5 restaurants providing highest number of categories** : 
  **Imperial Restaurant, Asha Sweet Center, Hotel Empire, Udupi Palace, Angat 22 - The Restaurant & Banquet**

### Recommendations
Inorder to improve “SuperStore” Sales & Profits :
- **More offers can be rolled out on the 13 restaurants that have rating more than 4.5** in order to increase sales.
- Since **Bangalore** has the highest number of restaurants, **more delivery bikes will be needed in the city** in order to cater to the higher order values.
 

