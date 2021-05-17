# Tableau: Citi Bike Data Analytics

## Tableau Public Dashboards and Story

This project required that I take on the role of an entry level data analyst for the New York Citi Bike progam.  My resposability was to generate a regular report for city officials that looked at user data to see where imporvements in the program could be made. I utilized Citi Bikes infrastructure for collecting data and took Citi Bike user data from 2014. I wanted to look at the difference between Summer and Winter seasons so I used the months of January, February, March, July, August and September in my report.  There are currently no dashboards or sophisticated reporting processes and I have to generate some starter reports. Since my report is going to be read by city officials, public administrators and heads of New York City departments, I have to make my reports easy to read. 

### Task 1: Aggregate Website Data
For the first task in this project I had to collect sets of data from the Citi Bike website.  The data was not guarenteed to be consitently formatted or the size I needed so I had to do some restructuring of the data to work with it in Tableau.  The steps I took to aggregate the website data to a dataset that I could use in Tableau are as follows.
* Download datasets from Citi Bike website
* Review all datasets header names and colomn arrangements to ensure they were identical
* Reduce size of each months dataset to 20,000 records for bandwidth issues
* Create Jupyter Notebook to import and combine all datasets into one document and export file

<p align="center">
    <img width="700" alt="level1" src="https://github.com/mathewqpmiller/Tableau-CitBikeAnalysis/blob/main/Resources/Images/AggregateData1.JPG?raw=true">
</p>
<p align="center">
    <img width="700" alt="level1" src="https://github.com/mathewqpmiller/Tableau-CitBikeAnalysis/blob/main/Resources/Images/AggregateData2.JPG?raw=true">
</p>

### Task 2: Create Visualizations
Once I had the dataset created I loaded it into Tableau to build some visualizations. Befor I built any visualizations I had to create some additional tables from the dataset to include such thing as trip time in minutes, number of trips, gender type etc. I used such things as calculations and groupings to accomplish these tasks. 
After completing that, I had to create at least two dashboards with a minimum of two visualizations for each Dashboard so I had to make at least four visualizations in total for this project. Although I did not end up using all of my visualizations in the report, I did end up creating 20 visualizations as part of this project. The following are the questions that I answered in the visualization creation portion of this report.
* What were the total trips taken
* What were the total trips taken by demographic age group
* What were the total trips taken by gender group
* How many of each age demographic was included in each gender group
* Did guests or subscribers use the service more
* What was the average trip durration
* What was the average trip durration by demographic age group
* Station usage by gender group
* Station usage by age demographic group
* What is the total volume usage of all start station locations
* What is the total volume usage of all end station locations
* What is the total volume usage by sesaon of start station locations by season
* What are the top ten start stations: named and mapped
* What are the top ten end stations: named and mapped
* What are the bottom ten start stations: named and mapped
* What are the bottom ten end stations: named and mapped

<p align="center">
    <img width="700" alt="level1" src="https://github.com/mathewqpmiller/Tableau-CitBikeAnalysis/blob/main/Resources/Images/VisualizationCreation.JPG?raw=true">
</p>

### Task 3: Create Dashboards
With the visualizations completed, I now had to create a set of Dashboards that could be used in the final Tableau Public report. With the aid of the visualizations, I needed to indentify some phenomena for each Dashboard. In addition to having a visual representation of the phenomena, I also needed to give a written explanation of what was occuring. The steps that I took to create the Dashboards are as follows.
* Create unique headers
* Drag and drop visualizations onto the dashboard
* Arrange visualizations to be coherent, easy to read and visually appealing

<p align="center">
    <img width="700" alt="level1" src="https://github.com/mathewqpmiller/Tableau-CitBikeAnalysis/blob/main/Resources/Images/VisualizationCreation.JPG?raw=true">
</p>

### Task 4: Create Static or Dynamic Map
City officials would also like to see one of the following visualizations:
* Basic: A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey with zip code data overlaid on top.
* Advanced: A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.
* The map you choose should also be accompanied by a write-up unveiling any trends that were noticed during your analysis.

### Task 5: Create Story
Create a Tableau story that brings together the visualizations, requested maps, and dashboards.
This is what will be presented to the officials, so be sure to make it professional, logical, and visually appealing.

https://public.tableau.com/profile/mathew.miller#!/vizhome/TableauChallenge_16211468039140/CitiBikeAnalysisStory

### Submission
Your final submission should include a link to your Tableau Public workbook that includes:

* 4-10 Total "Phenomenon" Visualizations
* 2 Dashboards
* 1 City Official Map
* 1 Story
* A text or markdown file with your analysis on the phenomenons you uncovered from the data.
* Share your work as a .twbx file to Tableau Public. Create an account if you do not have one already.

Once you have created an account and published your work to Tableau Public, go to the visualization in Tableau Public and find the Download button at the bottom right hand corner. Please download the Tableau Public file to your computer and submit it.

### Assessment
Your final product will be assessed on the following metrics:
* Analytic Rigor
* Readability
* Visual Attraction
* Use any and all tools needed
* Analyze datasets thuroughly
* Use appropriate time-sets
* Build visualizations with small datasets
* Have clear answers and don't cram them everything in
* Use colors and themes that match the companies aesthetic tones
* Pay attention to labels
* Keep an eye out for false data
* Consider adding additional supporting information
* Explore Tableau

<p align="center">
UNIVERSITY OF OREGON: Data Analytics Boot Camp - Repository for project 16(Tableau Challenge)
</p>
<p align="center">
Mathew Miller © 2021. All Rights Reserved.
</p>
