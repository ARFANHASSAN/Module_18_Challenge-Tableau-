# Module_18_Challenge-Tableau-

# Citi Bike Analysis with Tableau
----------------------------------------------------------------------------
## Deployment
https://public.tableau.com/app/profile/arfan.hassan/viz/Module_18_ChallengeTableau/Totaltrips?publish=yes

## Background
Congratulations on your new job! As the new lead analyst for the New York Citi Bike program, you are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike Data webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers.

## Instructions

Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.

* Design 2–5 visualizations for each discovered phenomenon (4–10 total). You may work with a timespan of your choosing. Optionally, you can also merge multiple datasets from different periods.

* Use your visualizations (not necessarily all of them) to design a dashboard for each phenomenon. The dashboards should be accompanied by an analysis explaining why the phenomenon may be occurring.

* Create one of the following visualizations for city officials:

#### Basic: A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top.

#### Advanced: A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.

The map you choose should also be accompanied by a write-up describing any trends that were noticed during your analysis.

* Create your final presentation:

Create a Tableau story that brings together the visualizations, requested maps, and dashboards.

Ensure your presentation is professional, logical, and visually appealing.

## Data Source:

The project commenced by obtaining monthly CSV files for January 2019 and July 2019 from the Citi Bike Data webpage. These files were then renamed. It's important to note that the data under analysis specifically relates to the New York City region.

Following this, I created a Jupyter Notebook file titled "citibike-data." The purpose of this file was to methodically clean and merge all the monthly CSV files into a unified CSV file, getting them ready for importation into Tableau.

## Dashboards
--------------------------------------------------------------
Utilizing the Citi Bike data, we developed a homepage along with three corresponding dashboards. These dashboards aim to deliver a thorough analysis and visualization of the dataset.

## Homepage


The project's homepage functions as an introductory hub, offering a brief overview of its objectives and contents. It effectively encapsulates the main insights and discoveries from each dashboard, facilitating swift and straightforward navigation.

![Homepage]("C:\Users\bella\Desktop\Module_18_Challenge-Tableau-\images\Home Dashboard.png")

## User Analysis
The dashboard offers an in-depth analysis of Citi Bike trips, considering diverse factors such as user type, gender, and age. Furthermore, it conducts a thorough exploration of trip patterns concerning the hour of the day and day of the week, alongside presenting the total number of trips per month.
![User Analysis]("C:\Users\bella\Desktop\Module_18_Challenge-Tableau-\images\User Dashboard.png")

## Station Analysis

The dashboard centers around analyzing trips in connection with bike stations. It contrasts trip patterns between weekdays and weekends, offering insights into the average duration of trips for each month.

![Station Analysis]("C:\Users\bella\Desktop\Module_18_Challenge-Tableau-\images\Trip comparison between weekdays and weekend.png")

## Geographic Analysis
The third dashboard includes two maps displaying the geographic positions of both starting and ending stations. Marker size and color are utilized to depict the total number of trips originating or concluding at each station, offering a visual representation of trip patterns and frequency.

![Geographic Analysis]("C:\Users\bella\Desktop\Module_18_Challenge-Tableau-\images\Map Dashboard.png")
