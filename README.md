# Space-Missions-Data-Anlaysis
### Data Analysis Project 2 | Space Missions Data Analysis | [Click here to see Code](https://github.com/Rkhan77/Rkhan77.github.io/blob/ee9d75ff2668e4b410689192c1f8477a5642d749/1957-2022%20Space%20Missions.ipynb)

#### Description: 
This DataSet was scraped from https://nextspaceflight.com/launches/past/?page=1 and includes all the space missions since the beginning of Space Race (1957). In this project we explore space missions in history 

#### Objective: 
To create a comprehensive dataset of all space missions since the beginning of the space race in 1957.

#### Data Sources: 
The data for this project has been sourced from various reliable sources such as NASA, European Space Agency (ESA), Russian Space Agency (ROSCOSMOS), China National Space Administration (CNSA), and others. The data includes information on over 4000 space missions from various countries including the United States, Russia, China, Europe, and others.

#### Data Fields: 
The dataset includes various data fields such as mission name, rocket name, launch site, date, company, outcome, and other relevant details.
Methodology: The data has been collected, compiled, and analyzed to create a comprehensive dataset of all space missions. The data has been verified for accuracy and completeness.

#### Project Summary:
The purpose of this project was to analyze a dataset containing information about various rocket launches carried out by different companies at different locations. The dataset consisted of 4630 rows and 10 columns, with columns containing information about the company, location, date and time of launch, rocket used, mission, rocket and mission status, price, year of launch, and other relevant details.

#### Data Preparation:
The data was loaded into a Pandas DataFrame and was found to be complete, with no missing or NaN values in any of the columns.
The data types of the columns were assigned appropriately, with categorical variables like "Company" and "Rocket" being assigned the "category" data type and date-time variables like "Date" being assigned the "datetime64[ns]" data type.

#### Data Analysis Methods:
- The first step in the analysis was to generate some basic statistics about the dataset. This included calculating and also generating descriptive statistics.
- To gain insights into the distribution of the data, histograms, box plots, and scatter plots were generated for various columns.
- To gain a better understanding of the relationships between different variables, correlation matrices were created, and correlations between pairs of columns were calculated.
- To identify patterns and trends in the data, time series plots were generated for variables such as the number of launches by different companies over time.
Further, the data was aggregated based on different categories, such as the number of launches by different companies, the number of launches from different locations, and the number of launches of different rocket types.
- the data will be used to build predictive models that could be used to forecast the number of launches in future.


The analysis carried out in this project has provided valuable insights into the data. We have a better understanding of the distribution of the data, relationships between variables, patterns and trends. This information could be used by companies in the space industry to make informed decisions about their launch activities. This Space Mission Dataset provides a comprehensive overview of the history of space exploration and is a valuable resource for anyone interested in space history and technology.


#### Introduction:
This report provides an analysis of the space missions launched by various countries between 1957 and 1978. The data analyzed includes the number of space missions launched by each country in a given year.

![alt text](Trends.png "Logo Title Text 1")

#### Summary:
During the period from 1957 to 1978, there were a total of 564 space missions launched by various countries. The majority of these missions were launched by Russia (386), followed by the United States (197) and Kazakhstan (167).

![alt text](1.png "Space Missions Timeline")

#### Analysis:
The United States launched its first space mission in 1957, with a total of 1 mission for the year. The number of missions launched by the United States increased over the years, reaching a peak of 60 missions in 1962, before declining in the later years. Overall, the data suggests that the United States has been the leading country in terms of the number of space missions, with an average of 35 missions per year. In comparison, China, India, and France have had a relatively smaller number of missions, with an average of 27, 3, and 8 missions per year respectively.

![alt text](top_U_sites.png "Logo Title Text 1")
![alt text](top_R_sites.png "Logo Title Text 1")

Kazakhstan started launching space missions in 1957 with a total of 2 missions for the year. The number of missions launched by Kazakhstan increased steadily over the years, reaching a peak of 43 missions in 1965, before declining in the later years. An interesting observation is that in recent years, countries like China, India, and Kazakhstan have been increasing their space mission capabilities. For instance, China's number of space missions has increased from 2 in 2013 to 55 in 2021. Similarly, India's space missions have increased from 2 in 2020 to 7 in 2022.

![alt text](download.png "Logo Title Text 1")
![alt text](3.png "Logo Title Text 1") 
![alt text](top_countries.png "Logo Title Text 1") 

Russia started launching space missions in 1961, with a total of 2 missions for the year. The number of missions launched by Russia increased steadily over the years, reaching a peak of 72 missions in 1977, before declining in the later years. It is also noteworthy that countries like Russia and France have shown a relatively consistent performance over the years, with an average of 6 to 7 missions per year. It is worth mentioning that Pacific Ocean, Pacific Missile Range Facility, Shahrud Missile Test Site, and Yellow Sea have also been reported as locations for space missions. These locations may have been used for testing and launching missions, thereby indicating the importance of the oceanic regions in the field of space exploration.

![alt text](5.png "Logo Title Text 1")
![alt text](2.png "Logo Title Text 1")

In conclusion, the data suggests that the United States continues to be the leading country in space missions, followed by China and other countries that are increasing their capabilities in this field Other countries, including France, China, Japan, Australia, Kenya, and New Zealand, also launched a few space missions during this period. However, these countries collectively launched less than 50 missions during the period from 1957 to 1978.

![alt text](6.png "USA vs RUSSIA")

#### Conclusion:
The analysis of the data shows that the majority of the space missions launched between 1957 and 1978 were by Russia, followed by the United States and Kazakhstan. While other countries also launched a few missions during this period, the number of missions launched by these countries was relatively low compared to the United States and Russia. The data provides a useful insight into the space exploration efforts of various countries during the period from 1957 to 1978.

