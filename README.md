# NYC Business Development
- Authors: Eric Chow & Jiahong Yu
- Date created: 9/28/2022
- Class: CIS 9440
 
Project Objective: Follow the Kimball Lifecycle to design and develop a public, cloud-based Data Warehouse with a functioning BI Applications
 
Project Tools:
The tools used to build this Data Warehouse were: 
1. For data integration - Python
2. For data warehousing - Google BigQuery
3. For Business Intelligence - Tableau
 
## Kimball Lifecycle Project Stages


### Project Planning
 
Motivation for project:
We are interested in the trend in frequency, type, and location of newly-created and existing businesses in New York City.


Description of the issues or opportunities the project will address:
Businesses come and go. The opportunity in understanding the trends in the type and location of new and existing businesses in New York City would allow the local government to better direct public resources in promoting commercial growth.
We can also gauge the frequency at which businesses open so that the city government can promptly allocate resources to attract foot traffic to those locations.


Project Business or Organization Value:
Clearly identifying the locations with frequent business openings and the types of businesses would allow the government to better spend on advertising, policing, and other economic incentives to attract customers to those enterprises and help advance the local economy.
The government will benefit from higher tax revenue and increased local employment by indirectly helping these businesses.


Data Sources:
1. Legally Operating Businesses
https://data.cityofnewyork.us/Business/Legally-Operating-Businesses/w7w3-xahh
2. United States census data
https://data.census.gov/table
 
### Business Requirements Definition


List of Data Warehouse KPIs:
1.Number of new business per location
2.Percentage of new business by industry
3.Number of active business per population
4.Active businesses per location
5.Average length of business operation per industry


### Dimensional Model


This project's Dimensional Model consists of two (2) Facts and five (5) Dimensions
 
This project’s Dimensional model:
https://github.com/wchow4/nyc_business_dev_data_warehouse/blob/main/CIS%209440%20-%20Milestone%202%20-%20Dimensional%20Model_20221013%20v3.0.JPG


This project's Kimball Bus Matrix:
https://github.com/wchow4/nyc_business_dev_data_warehouse/blob/main/CIS%209440%20-%20Kimball%20BUS%20Matrix%20Template%20-%20Chow%26Yu_20221013%20v2.0.JPG


### Business Intelligence Design and Development


List of Visualizations for each KPI:
1. Bar Chart for comparison of new businesses per location
2. Treemap for percentage of new businesses by industry
3. Scatter plot for number of new businesses per population to visualize the relationship between population size and the number of new businesses
4. Symbol Maps to show the active businesses per location
5. Horizontal Bar chart to visualize the length of business operations per industry
BI Application Wireframe design:


This project's wireframe designs:
![Alt text](~CIS9440_Fall22_Wireframe_Dashboard_1.JPG)
https://github.com/wchow4/nyc_business_dev_data_warehouse/blob/main/CIS9440_Fall22_Wireframe_Dashboard_1.JPG
https://github.com/wchow4/nyc_business_dev_data_warehouse/blob/main/CIS9440_Fall22_Wireframe_Dashboard_2.JPG
 

This project's final dashboard:
https://github.com/wchow4/nyc_business_dev_data_warehouse/blob/main/CIS9440_Fall22_Dashboard_1_Screenshot.JPG
https://github.com/wchow4/nyc_business_dev_data_warehouse/blob/main/CIS9440_Fall22_Dashboard_2_Screenshot.JPG


### Deployment
 
The project was deployed on Tableau Public: 
https://public.tableau.com/app/profile/jiahong.yu7692/viz/Milestone4_16693278940230/Dashboard2?publish=yes
