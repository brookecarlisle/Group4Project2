# Group 4 MIST 4610 Group project 2

## Team Name: 
21482 Group 4

## Team Members:
1. Ryan Overbeck https://github.com/rjo82443
2. Minwoo Park https://github.com/Haroom02
3. Brooke Carlisle https://github.com/brookecarlisle
4. Mathias Flanagan https://github.com/mf727
5. Connor Walker https://github.com/connorwalker33

## DataSet: https://catalog.data.gov/dataset/water-quality-data-41c5e
We did not have to make any changes to or manipulate the dataset in any way.


## Features of Data Set:

Columns feature: (Water Quality Data)
1. Site_Id: Identifier for the sampling site.
2. Unit_Id: Identifier for the sampling unit or device.
3. Read_Date: The date on which the sample was taken.
4. Salinity (ppt): Salinity concentration measured in parts per thousand.
5. Dissolved Oxygen (mg/L): The concentration of oxygen dissolved in the water measured in milligrams per liter.
6. pH (standard units): The pH level of the water.
7. Secchi Depth (m): The clarity of water measured in meters using a Secchi disk.
8. Water Depth (m): The depth of the water measured in meters.
9. Water Temp (°C): The temperature of the water measured in degrees Celsius.
10. Air Temp-Celsius: The temperature of the air measured in degrees Celsius.
11. Air Temp (°F): The temperature of the air measured in degrees Fahrenheit.
12. Time (24:00): The time at which sampling was done in a 24-hour format.
13. Field_Tech: Identifier or name of the field technician.
14. DateVerified: The date on which the data was verified.
15. WhoVerified: The identifier or name of the person who verified the data.
16. AirTemp (C): The air temperature in degrees Celsius, which seems to be recorded again and might be a redundancy.
17. Year: The year in which the sampling was done.

## Importance of Data Set:
We chose to analyze a dataset portraying water quality across diverse water sites at the Back Bay National Wildlife Refuge spanning from 1889 to 2019. Delving into this dataset allows us to discern trends and fluctuations in water quality over the decades. This analysis carries significance in understanding the correlation between water quality and the survival of fish species. By surveying changes in water quality over time, we can under its direct influence on the habitat and ecosystem health crucial for sustaining fish populations.

## Question 1:
From the year 1990-2010, we want to discover when there are optimal living conditions for a Largemouth bass using the metrics of PH level, dissolved oxygen level, and the salinity level. For a largemouth, their optimal numbers are: 7.5-8.5 for PH level, salinity > 0.5ppt, and dissolved oxygen between 8MG/L - 12MG/L.

<img width="633" alt="Screenshot 2024-04-29 at 11 29 52 AM" src="https://github.com/brookecarlisle/Group4Project2/assets/163200089/6701a2da-6370-459f-bbc2-1dca44b681a7">

We utilized the data to pinpoint the precise conditions essential for the survival of fish species like the largemouth bass. This information proves invaluable for understanding the environmental parameters conducive to their existence. Specifically, we focused on factors such as dissolved oxygen levels, salinity, and pH, all of which must fall within certain ranges for the largemouth bass to thrive. The graph presented here illustrates data from the years 1990 to 2010 within the Bay area, showcasing only those years where all three criteria were met.

From our analysis, it becomes evident that the largemouth bass population faced challenges beyond 2002 as their habitat conditions shifted unfavorably. Consequently, they were compelled to seek alternative environments conducive to sustaining their livelihoods elsewhere in the water system.



## Question 2:
Healthy aquatic ecosystems rely on the stability of various factors to support thriving aquatic life. We aim to explore the relationship between Dissolved Oxygen levels and Air Temperature to grasp their combined impact on water body conditions. What data can we extract from the correlation between Dissolved Oxygen and Air Temperature? Moreover, how does the trend line portray the relationship between these variables and what significance does it carry for evaluating the health of ecosystems?

<img width="628" alt="Screenshot 2024-04-29 at 11 29 57 AM" src="https://github.com/brookecarlisle/Group4Project2/assets/163200089/437e5160-5f14-4188-8904-3faa8e142506">

Understanding the correlation between Dissolved oxygen levels and Air Temperature in aquatic ecosystems is crucial for assessing the survivability of fish and overall ecosystem health. As air temperature increases, the solubility of oxygen in water decreases, leading to lower Dissolved Oxygen levels. This decline in Dissolved Oxygen can stress fish populations and other aquatic organisms, potentially impacting their survival. The R-squared value of 0.165 suggests a weak correlation between dissolved oxygen and air temperature, indicating that while there is a relationship, other factors, such as salinity, water depth, and water temperature, may also influence Dissolved Oxygen levels. Monitoring and managing these variables can help maintain stable aquatic ecosystems and support thriving aquatic life.


