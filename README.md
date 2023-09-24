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

I opted for Option 2, with a focus on the FAA wildlife strike data. My initial exploratory data analysis involved generating line plots for Total Cost by Year, Total Strikes by Year, Total Cost (Out of Commission) by Year, and Indicated Damage by Year. Additionally, I created bar charts to visualize Cost by Species, Strikes by Species, and Service Cost by Species, along with histograms for Impact to Flight, Amount of Damage, Time of Day, and Phase of Flight, all aimed at facilitating initial data exploration.

After that I found that the year of 2009 was an extreme outlier compared to the rest of the years, and intially considered excluding it from the analysis but instead decided to hyper focus on that year to try and find exactly why it was on outlier and then how that knowledge could be used in the current climate.

So from there I started creating the visualizations i would need to start to answer the questions i would need to ask to find out the details of what happened in 2009:
- A colored map chart of the top three states with the highest costs in 2009, to see where most of the costs in 2009 were
- Created a calculated field to find out the average cost per collision by state in 2009, to see which state had the highest average per collision
- Created a butterfly chart of number of strikes and the total cost per state in 2009, to see which state has the highest costs compared to strikes
- created another butterfly chart, to compare strikes vs. total cost by species, to see which animal caused the most damage in 2009
- created a bar chart to see which month had the highest cost in 2009
- created a bar chart to see which day had the highest cost in January, 2009
- created a line chart with a forecast to see the amount of strikes going beyond the data 
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