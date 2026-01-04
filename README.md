# EDA - Airbnb Listings
The goal of this project is to evaluate pricing, demand, and host activity trends to help a travel startup decide whether to expand services by analysing Airbnb data in Asheville, NC. 
There are three sets of data available for analyses: 

listings.csv → details about each listing (location, host, room type, price, availability).

neighbourhoods.csv → neighborhood codes for listings.

reviews.csv → historical review activity by listing.

## 🎯Objectives
- Identify pricing trends
- Identify which neighborhoods and hosts are most active
- Find out what review activity says about demand

## ⚙️Tools
- Excel
- SQL (MySQL) 

## ✅Skills
- Data Cleaning & Joining Multiple Table
- Aggregation & Grouping
- Outlier Handling (price extremes, minimum nights)
- Trend & Time-Series Analysis
- Visualization & Storytelling

## 🪜Process
### 1. Data Preparation

Inspect each dataset and check for missing values. 

Look for outliers in price. 

Merge reviews.csv with listings.csv to connect review activity to listing details.

### 2. Descriptive Analysis

Calculate the average and median nightly price for all listings.

Show the distribution of room types.

Count the number of active listings per neighborhood.

### 3. Pricing Insights

Compare average price by neighborhood.

Identify the top 5 most expensive neighborhoods.

Check if minimum nights affect average price.

### 4. Review & Demand Analysis

Calculate the total number of reviews per listing and the average reviews per month.

Identify which neighborhoods generate the most guest activity.

Look at trends in reviews.csv → which years/months had spikes in demand?

### 5. Host Analysis

Find the hosts with the most listings.

Compare Superhosts vs. non-Superhosts.

Check whether hosts with multiple listings charge higher or lower average prices.


## 💭Recommendations

Based on the data, suggest whether Asheville is a good expansion market.

Highlight specific neighborhoods or property types with strong opportunity.

Point out risks.
