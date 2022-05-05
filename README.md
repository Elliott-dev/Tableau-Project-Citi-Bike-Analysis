# Tableau-Project--Citi-Bike-Analysis

![citi-bike-station-bikes](https://user-images.githubusercontent.com/94668201/166336200-46cba0a5-94b7-48a8-b818-1da212b0c78b.jpg)
# Tableau Homework - Citi Bike Analytics

### Before You Begin

* This was saved and published to my Tableau Public account: https://public.tableau.com/app/profile/elliotteinstein/viz/Citi_Bike_Analysis_16517287699750/CitiBikeAnalysis.

## Background

As the new lead analyst for the [New York Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) Program, I am now responsible for overseeing the largest bike sharing program in the United States. In this new role, I will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, so your first task on the job is to build a set of data reports to provide the answers to key business needs to drive decision making. 

## Steps

**Designed visualizations for discovered phenomena (4-10 total). I worked with the timespan from Jan-March 2022 and merged those multiple data sets accordingly. 

**The following are some questions I chose to tackle. 

* By what percentage has total ridership grown?
* How has the proportion of short-term customers (casual) and annual subscribers (members) changed?
* What are the peak hours in which bikes are used during winter months? 
* Today, what are the top 10 stations in the city for starting a journey?
* Today, what are the top 10 stations in the city for ending a journey? (Based on data, why?)
* Today, what are the bottom 10 stations in the city for starting a journey?
* Today, what are the bottom 10 stations in the city for ending a journey (Based on data, why?)

**Next, as a chronic over-achiever:**

* I used my visualizations to design a dashboard for each phenomena.
* The dashboards were accompanied with a brief analysis explaining why the phenomena may be occuring. 

**City officials would also like to see one of the following visualizations:**

* **Basic:** A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey with zip code data overlaid on top.*************

* **Advanced:** A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.**************

**Finally, I created my final presentation**
* Created a Tableau story that brings together the visualizations, requested maps, and dashboards

![Citi Bike Analysis](https://user-images.githubusercontent.com/94668201/167020609-41c470bf-877b-458a-9a2b-d50e78c43f50.png)

![Citi Bike Analysis_cnt](https://user-images.githubusercontent.com/94668201/167020626-79e5f477-72b5-48cb-8838-590e6c3693fb.png)


## Considerations

My audience will be city officials, public administrators, and heads of New York City departments. My data and analysis needs to be presented in a way that is focused, concise, easy-to-understand, and visually compelling. My visualizations are colorful enough to be included in press releases, and my analysis should be thoughtful enough for dictating programmatic changes. 

## Problems Encountered

* Data was not consistent and clean throughout the analysis. 
*  **Solved By: ** 
*  Checking for null values, dropping unclean and null values, and cleaning dataframes using python in jupyter notebook. Used concat function to combine all three excel files into a single dataframe. 
* I needed be creative in how you combine each of the CSV files because each file contained 1M+ records. 
* **Solved By: ** 
* I did an ETL process move data file from the jupter notebook in PostGreSQL database((https://www.citibikenyc.com/system-data). I created a connection to PostgreSQL database to read in the large 4M+ record file. I checked for a successful connection to the database and confirmed that the tables had been created, and I also confirmed by querying the database. 

