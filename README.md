Tool used: Power BI

### Dashboard Overview

![*Citibike Bike Sharing Analysis Dashboard Main*    ](https://prod-files-secure.s3.us-west-2.amazonaws.com/ca4774d5-012e-4399-93d3-4753256fe9cc/027cd9ce-20ba-4f0c-b57d-2b2d2c798da5/Untitled.png)

*Citibike Bike Sharing Analysis Dashboard Main*    

![*Citibike Bike Sharing Analysis Dashboard - User Analysis*   ](https://prod-files-secure.s3.us-west-2.amazonaws.com/ca4774d5-012e-4399-93d3-4753256fe9cc/26ef3f20-fe96-459b-9bfb-bc0d248c0ebd/Untitled.png)

*Citibike Bike Sharing Analysis Dashboard - User Analysis*   

![*Citibike Bike Sharing Analysis Dashboard – Station/Ride Analysis*](https://prod-files-secure.s3.us-west-2.amazonaws.com/ca4774d5-012e-4399-93d3-4753256fe9cc/209079ba-2fa1-4cab-8dc5-dc3493ef9b60/Untitled.png)

*Citibike Bike Sharing Analysis Dashboard – Station/Ride Analysis*

### **Data Source description**

The dataset used in this assignment is named “New York City Bike Share Dataset” and is provided on “Citibike” for the public and non-commercial purposes. The link for the dataset is as below:

https://citibikenyc.com/system-data

This dataset is from Citibike, launched in May 2013, initially faced delays but quickly expanded across New York City and New Jersey, becoming the largest bike sharing program in the US by 2017. Under Lyft's ownership, the system experienced substantial growth, reaching milestones of 50 million rides by 2017 and 100 million rides by 2020. As of 2023, annual subscribers have grown to 180,000, with record-breaking ridership in August 2023, totaling 4.07 million rides. Monthly ridership exceeded 100,000 for the first time in June 2021, highlighting its increasing popularity and usage over time. Planned expansions aim to extend the service area across boroughs and increase the fleet to 40,000 bikes, indicating continued growth and success for the program.

![Figure 1: Citybike's official website](https://prod-files-secure.s3.us-west-2.amazonaws.com/ca4774d5-012e-4399-93d3-4753256fe9cc/15bfe03d-5448-466f-ba77-c083a28ee640/Untitled.png)

Figure 1: Citybike's official website

Figure 2: Citybike System Data Sharing Page

### Objectives and approach

The objective is to compare riding patterns before and after the onset of the pandemic using December 2019 and December 2020 data. The analysis focuses on addressing the following aspects:

1. Comparative study of riding patterns pre and post-pandemic using December 2019 and 2020 data.
2. Demographic analysis, encompassing age and gender insights into frequent user groups.
3. Examination of user types, specifically the ratio between casual riders and annual subscribers, along with behavior analysis.
4. Analyzing the riding data based on time patterns to uncover insight: Identifying peak days and busiest hours for rides.
5. Evaluation of station popularity and identification of high-traffic stations.

### Scope

This project scope is divided into two main sections. In section 1, our focus lies on preparing the data thoroughly. This involves tasks such as data pre-processing, data cleaning, and data modelling for analysis. Moving to section 2, our primary objective is to generate an analytical report and an interactive dashboard. These deliverables aim to assist in evaluating performance by addressing questions related to comparing riding patterns, understanding user demographics, analyzing user types, and assessing station popularity.

### Rationale

The dataset’s selection stems from two core reasons. Firstly, Power BI emerges as an apt Business Intelligence tool due to its user-friendly nature and cost-effectiveness. Its adaptable visualization and customizable reports suit this project’s analytical needs.

Secondly, the dataset’s substantial size, comprising 1,902,188 records, and intricate data structures closely resemble real-world big data scenarios. This offers an ideal opportunity to apply learned skills in practical settings, preparing for future job requirements.

### Outcomes

At the end of this BI project, the following skills can be demonstrated:

- Data cleaning and data pre-processing skills through Power BI, such as importing data, adding/removing a column, removing NA or errors, changing data types.
- Data modelling by creating and managing relationships.
- Performing a calculation using DAX
- Critically analyzing data using different visualizations.
- Designing and publishing report
- Creating an interactive dashboard from the report

### Data description

Two CSV files, representing December data for 2019 and 2020, share identical column structures. A concise tabular representation of the shared columns is provided below:

| Table | Column | Definition |
| --- | --- | --- |
| citibike-tripdata 15 colunms-1,902,188 rows | tripduration | the time of riding a bicycle(second) |
|  | starttime | riding start station time |
|  | stoptime | riding end station time |
|  | start station id | riding start station ID |
|  | start station name | riding start station name |
|  | start station latitude | riding start station latitude |
|  | start station longitude | riding start station longitude |
|  | end station id | riding end station ID |
|  | end station name | riding end station name |
|  | end station latitude | riding end station latitude |
|  | end station longitude | riding end station longitude |
|  | bikeid | Bicycle ID |
|  | usertype | User's annual subscription status (Customer = 24-hour pass or 3-day pass user; Subscriber = Annual Member) |
|  | birth year | Year of birth of users |
|  | Gender | Gender of users(Zero=unknown; 1=male; 2=female) |

### Finding and Conclusions

A power BI dashboard was set up to address the critical questions in the report.

1. The combined total rides for Citibike’s bicycle sharing in December 2019 and 2020 reached 1,902,188, with a 9.4% increase in December 2020 compared to December 2019, indicating no decline due to the pandemic.
2. The average user age was 38.9, with the most frequent age group being 30 years old. Overall, 74% of users were male, and the remaining 26% were female. the proportion of female users showed a significant positive shift, increasing from 23% in 2019 to 29% in 2020.
3. 73% of the total recorded rides were from annual subscribers, while casual riders accounted for 7.27% of the rides. The percentage of rides attributed to casual users increased from approximately 5.11% in December 2019 to 9.25% in December 2020, showing a 4.14% increase.
4. Tuesday consistently emerged as the busiest day for rides regardless of the year, while peak hours varied — 8 AM in 2019, 3 PM in 2020, and an overall peak at 5 PM considering the two-year dataset.
5. The average daily ride count stood at 29,310. The busiest start station was ‘E 17 St & Broadway’, and the most frequented end station was ‘W 21 St & 6 Ave’.

### Recommendations for improving performance

1. Introduce promotions such as discounts that seamlessly guide first-time Casual users towards becoming annual subscribers. These methods will help casual users, whose rates are increasing in 2020 compared to 2019, naturally transition to annual subscribers.
2. The proportion of Casual users has increased compared to 2019, yet it significantly lags behind the ratio of annual subscribers. assessing potential barriers hindering the influx of Casual users, such as complexities in the bike rental process.
3. Expand marketing efforts targeting the rising demographic of female users, particularly within the 20-30 age bracket, to tap into their potential as a larger user base.
4. Strategize the allocation of more bicycles around high-traffic stations and peak hours.
