# Zomato analysis

## Project Overview

Zomato is a popular online platform that provides restaurant reviews, ratings, menus, and other dining-related information. Initially founded in India, Zomato has grown into a global company offering services across several countries. Users can search for restaurants by location, cuisine, and price range while also viewing ratings and reviews from other diners. 

Apart from helping users discover new dining options, Zomato also offers online table reservations and food delivery services. The platform connects users with restaurants, making it a one-stop solution for food discovery and convenience. For businesses, Zomato provides valuable data insights, customer feedback, and advertising options.

Overall, Zomato has become a vital tool in the food and restaurant industry, enhancing the dining experience for users while offering a robust platform for businesses.


## Tech stacks

- SQL
- PowerBi Desktop
- Excel
- DAX language
- DAX studio (for optimizing the report)
- Tableau

## PowerBI techniques Learnt

- What are all the questions should be asked before staring the project
- Creating calculated columns
- creating measure using DAX language
- Data modeling
- Using Bookmarks to switch between two visuals
- Page navigation with buttons
- Using divide function to prevent zero division errors
- creating date table using m language
- Dynamic titles based on the applied filters
- Using KPI indicators
- Conditional formatting the values in visuals using icons or background color
- Data validation techniques
- PowerBi services
- Publishing reports to PowerBi services
- Setting up personal gateway to set up the auto refresh of data
- PowerBi App creation
- Collaboration, workspace, access permissions in PowerBi services
- And more

## GitHub 

- Uploading Large size files using GitHub LFS
- Tracking the particular type of file extensions for LFS

## Business related terms KPI'S to work on
1.Build a country Map Table
2. Build a Calendar Table using the Column Datekey
  Add all the below Columns in the Calendar Table using the Formulas.
   A.Year
   B.Monthno
   C.Monthfullname
   D.Quarter(Q1,Q2,Q3,Q4)
   E. YearMonth ( YYYY-MMM)
   F. Weekdayno
   G.Weekdayname
   H.FinancialMOnth ( April = FM1, May= FM2  …. March = FM12)
   I. Financial Quarter ( Quarters based on Financial Month)
3.Find the Numbers of Resturants based on City and Country.
4.Numbers of Resturants opening based on Year , Quarter , Month
5. Count of Resturants based on Average Ratings
6. Create buckets based on Average Price of reasonable size and find out how many resturants falls in each buckets
7.Percentage of Resturants based on "Has_Table_booking"
8.Percentage of Resturants based on "Has_Online_delivery"
9. Develop Charts based on Cusines, City, Ratings


### Questions to ask before starting with dashboard

- What is the objective of building this PowerBi dashboard?
- In what terms the success of this project will be measured?
- What will be time dead-line of the project?
- do the stakeholders expecting pre-view before the actual release?
- What are all the hopes stakeholders have out of this project?
- what are all fears the stakeholder have in terms of building this dashboard?
- Who are all will be using this dashboard and for what purpose?
- what are all expectation the stakeholders have, by the completion of this project?
- What can go wrong while building this project?
- what are all the resources/ data needed to build this dashboard?
- is there any inputs from stakeholders in terms of design and views of the dashboard?

After the project kick off meetings, the data engineering team has given the data as per the request of data analytics team, let’s explore them.

### Dataset **Understanding.**

Understanding what data is available will be more helpful while doing analysis. before jumping on to the analysis get good understanding of what are data available.

Dimension table : It will have the static data like details of customer and products

Fact table : It will have the data about the transactions  

    - Restaurants
        - cities (ex New Delhi,Bangalore)
        - Restaurant ID's distinct throughout the data
        - Restaurant Names
        - Cuisines 
        - Currency
        -Has_table_bookings
        -Has_online_deliveries
        
    - dim_country 
        -Country Id
        - Country Name 
Understanding and cleaning the data by removing all the null values and blank cells is the initial process.so the data will be ready for the visualisations.
