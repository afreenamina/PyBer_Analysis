# PyBer_Analysis

# Overview of the analysis :
This analysis is done for PyBer - a ride-sharing app, to showcase the relationship between the type of city, number of drivers, riders, and total fare. The analysis and visualization will help PyBer improve access to ride-sharing services and determine affordability for an underserved neighborhood

Below are the new analysis added for PyBer
* Summary of Ride Sharing data by city type - calculating the total number of rides, total Drivers, total fares. With these data, we get the average fare per ride and average fare per driver, which will help us to compare the data by city type - Urban, Suburban, and Rural.

* Multi-line graph for total weekly fares for each city type - Weekly total fare data from Jan to Apr is been used for comparing data based on the city type.

# Result :

###  Summary of Ride Sharing data by city type -
To get the summary of ride-sharing data by city type,below are the code used to obtain data from the dataframe(city and ride data file)

* Groupby function and sum() has been used to get the total number of rides for each city type
![1](https://user-images.githubusercontent.com/92698873/143844284-52ba0e89-b87f-4156-a19f-0d4a25e6bb73.png)

* Groupby function and sum() has been used to get the total number of drivers for each city type
![2](https://user-images.githubusercontent.com/92698873/143844303-f5dfbc87-98da-42df-88d2-93078edebbad.png)

* Groupby function and sum() has been used to get the total fare for each city type
![3](https://user-images.githubusercontent.com/92698873/143844339-45716467-3994-40bd-86bf-52dbdc790dc6.png)

* Groupby function and mean() has been used to get the average fare for each city type
![4](https://user-images.githubusercontent.com/92698873/143844359-58007549-9eea-40f4-854c-33b097e922a4.png)

* Groupby function and mean() has been used to get the average fare per driver for each city type
![5](https://user-images.githubusercontent.com/92698873/143844365-e634e98c-8439-4352-b197-badfe3c886b6.png)

Below is the summary of the ride-sharing data

![6](https://user-images.githubusercontent.com/92698873/143844388-77a3c3f7-96a2-40be-966f-339a1885f485.png)

* From the above table, we notice that total rides and total Drivers for the Rural is less than Suburban and Urban.
* The market size of Urban is close to 70% which generates the highest revenue of 62% of the average total fare, whereas Suburban and Rural generate 30% and 6% respectively.
* Even though the market size of Urban type is huge, the average fare per ride is 27% less than Suburban and Rural.
* The average fare per Driver in Rural gets 50% more than Suburban and Urban.

### Multi-line graph for total weekly fares for each city type 
* We use line charts to show total weekly fares for each city type as they are best in comparing values, showing trends over time, and establishing the relationship between variables in datasets.
* For getting data by weekly fares - we used pivot() and resample() functions from Jan to Apr.

![9](https://user-images.githubusercontent.com/92698873/143847383-0c5b86e0-2b77-43cd-8fd1-bb8171c11913.png)
![8](https://user-images.githubusercontent.com/92698873/143847411-6c7ea765-5228-4a34-96a3-93eaeb4d87d8.png)

* Below is the line chart potted for the sum of fares based on weeks by city type from Jan to Apr
![PyBer_fare_summary](https://user-images.githubusercontent.com/92698873/143847553-8908d6f6-bd07-4644-a47f-4ed2f0bb3252.png)

* Looking at the line chart - it is clear that Urban is the top Market for PyBer, the next revenue is from Suburban.
* City type - Rural, Suburban, and Urban reach their peak on the last week of February with $416, $1412, and $2466 of the sum of fares respectively.
* The maximum and minimum range for Sum of fare for each city type -
  * Rural - $67 is the minimum and $500 is the maximum sum of fares based on weeks.
  * Suburban - $720 is the minimum and $1400 is the maximum sum of fares based on weeks.
  * Urban - $1660 is the minimum and $2470 is the maximum sum of fares based on weeks.

# Summary :
Based on the above analysis below are suggestions - 

* Urban - Planning time ahead, there may be an increase in the total rides in Urban areas as more people tend to move for studies and work, so we may need more drivers. And to attract more drivers to join PyBer average fare for drivers should be increased.
* Suburban - Total rides in Suburban is 625 and we have 490 drivers, we may need to recruit more drivers to get more people to use PyBer as it is a potential place to increase business.
* Rural -  Total Drivers in Rural can be increased so that more people in rural areas can travel by PyBer.

