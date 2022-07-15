Challenge 5
# Analysis on Ride-sharing Services

## 1. Overview of Analysis
The purpose of the project was to perform an exploratory analysis on data regarding PyBer’s ride-sharing services. By showcasing the relationship between the type of city and the number of drivers or rides as well as the average fares per drivers and rides by type of city, the analysis is expected to help PyBer improve access to ride-sharing services and determine affordability for underserved areas.

## 2. Results
### Data to Be Analyzed
Data was obtained in two csv files. One contained driver counts in each city with designation of type of city (city_data.csv). The other was a summary of 2,375 rides during the period from January 1, 2019 through May 8, 2019. Each ride record included ride ID, date, fare, and city (ride_data.csv).

### Procedures of Analysis
Two files were combined based on city for further analysis. Then, the data was summarized by type of city as follows:

![](https://github.com/Ryoichi2022/PyBer_Analysis/blob/main/PyBer_summary_table.PNG)

In addition, using the four-month data from January 1, 2019 to April 28, 2019, a line chart was depicted for the fare total on a weekly basis in each type of city as shown below.

![](https://github.com/Ryoichi2022/PyBer_Analysis/blob/main/PyBer_fare_summary.png)

### Results of Analysis
The total rides and the total drivers are by far largest in the urban cities. Naturally, the urban drivers earned more, or $39,854 in total, than those in suburban ($19,356) or those in rural cities ($4,328). However, both the average fare per ride and average fare per driver are highest in rural cities of all city types. Especially, a significant disparity exists in the average fare per driver. Drivers in rural cities earned three times more than those in urban cities.

In addition, the line chart demonstrated similar ups and downs in total fare among three city types regardless of the total fare level.

## 3. Summary – Business recommendations
Based on the analysis, the following recommendations would be presented.

### Shift of Drivers to Rural Cities
Some drivers could be moved from the urban cities to the rural or suburban cities. Based on a closer review of the data, it was found that the total rides were only 1,625 while there were 2,405 drivers in the urban cities. The drivers may not have operated fully.

### Reconsideration of Fares
The fare in the urban cities could be reconsidered so that the gaps in the average fare per ride and average fare per driver will be lowered. In urban areas, rides may tend to be shorter than in suburban and rural areas. If extra fare could be charged to those passengers who are going to move very short distance, the average fare will improve in the urban cities.

### Data for Further Analysis
In the provided files, ride data did not include distance, which is expected to affect the fare for rides. By obtaining distance data, fare per mile can be compared among type of city and will be useful to determine whether the fares are reasonable in each city.
