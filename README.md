# Final-Project-Tableau

## Project/Goals
Leveraging Tableau to transform data into accessible visual insights, creating dashboards for informed decision-making aligned with business inquiries, and effectively conveying these insights through appropriate visualizations.
## Process
### Connect to Tableau
Utilize Tableau to establish a connection with the FAA wildlife strike data.
### Exploratory Data Analysis(EDA)
Used visualizations in the process of EDA to learn as much as possible about the dataset
### Defining Questions
After initially excluding the outlier, I chose to delve deeper into the reasons behind its presence. I embarked on this journey to address various questions and, ultimately, to conclude by contemplating what insights this outlier might offer about the present circumstances.
## Results
(Fill in which Option you chose, either 1 or 2. List the dataset you selected for the project if you selected Option 2. Also, discuss the visualizations you created, and why. For Option 2, also identify what your data question was, and how you went through the prompts.)
I chose to pursue Option 2, and specifically chose the FAA wildlife strike data.
I began by creating line plots for Total Cost by Year, Total Strikes by Year, Total Cost(Out of Comission) by Year, and Indicated Damage by Year. As well as bar charts for Cost by Species, Strikes by Species, Service Cost by Species. And histograms for Impact to Flight, Amount of Damage, Time of Day, Phase of Flight.
These were all created for the purpose of intial data exploration.
- FAA Wildlife strike data
- What caused the cost spike in 2009?
  - Miracle on the Hudson event, Jan 15th, 2009. Caused $41,000,000 in damage.
- Which states have the highest cost?
  - California, New York, Texas
- Which animals caused the greatest damage?
  - Canada Goose has caused the most expensive collisions, even if you take out the 2009 outlier. That even though the amount strikes is relatively low, the size of the bird and size of the flock being between 30 - 100 birds, has the capability to cause extensive damage.
- What has caused the spike in strikes from 2008-2009?
  - speculation = After the Miracle on the Hudson event, the federal government stepped in and told the airlines to start accurately reporting the amount of strikes, to get a more complete picture of the amount of strikes and what could be done to prevent these strikes
- What is the cost of Wildlife Strikes to the airline industry?
  - Between the years of 2000 – 20015 that number is $322,160,887
- Outliers?
  - Yes, Jan 15th, 2009. Miracle on the Hudson event, which caused $41,000,000 in damage.
  - Now with this event included in the data is seems to massively skew the data, so I have removed it to get a better idea of the overall picture of the cost data.
- Which States have the highest costs?
  - Colorado, California, Oregon, Florida.
- What aircraft are in the costliest events?
  - 2 engine Airplane
- What aircraft are in the collisions that cause the most damage?
  - 2 Engine Airplane
- How far from the ground do most of the collisions take place?
  - Under 500 feet, 86.7%
- How far from the airport do the majority /of collisions happen?
  - Within 500 feet
- What time of day do most of the collisions take place?
  - During the day
- What time of day has the most costly collisions?
  - During the day, not night, dawn or dusk
- What animals cause the most damage?
  - Canadian Goose

## Challenges 
(discuss challenges you faced in the project)
- deciding on removing outlier that was drastically affecting the overall trends of the data, and doing analysis with and without the outlier for comparison
## Future Goals
(what would you do if you had more time?)
-connect a database with the number of flights coming out of each airport, to tell which airports have the highest percentage of wildlife strikes