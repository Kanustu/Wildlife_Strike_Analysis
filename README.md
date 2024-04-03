# WildLife Strike Analysis

## Project/Goals
Leveraging Tableau to transform data into accessible visual insights, creating dashboards for informed decision-making aligned with business inquiries, and effectively conveying these insights through appropriate visualizations.

## Process
### Connect to Tableau
Utilize Tableau to establish a connection with the FAA wildlife strike data.

### Exploratory Data Analysis(EDA)
Used visualizations in the process of EDA to learn as much as possible about the dataset.

### Defining Questions
After initially excluding the outlier, I chose to delve deeper into the reasons behind its presence. I embarked on this journey to address various questions and, ultimately, to conclude by contemplating what insights this outlier might offer about the present circumstances.

## Results
My initial exploratory data analysis involved generating line plots for Total Cost by Year, Total Strikes by Year, Total Cost (Out of Commission) by Year, and Indicated Damage by Year. Additionally, I created bar charts to visualize Cost by Species, Strikes by Species, and Service Cost by Species, along with histograms for Impact to Flight, Amount of Damage, Time of Day, and Phase of Flight, all aimed at facilitating initial data exploration.

After that I found that the year of 2009 was an extreme outlier compared to the rest of the years, and intially considered excluding it from the analysis but instead decided to hyper focus on that year to try and find exactly why it was on outlier and then how that knowledge could be used in the current climate.

Following that, I began crafting the necessary visualizations to address the questions essential for uncovering the details of the events in 2009:

- Developed a colored map chart pinpointing the top three states with the highest costs in 2009, shedding light on the primary cost centers.
- Formulated a calculated field to determine the average cost per collision by state in 2009, pinpointing the state with the highest average cost per collision.
- Constructed a butterfly chart comparing the number of strikes and the total cost per state in 2009, highlighting the state with the highest costs relative to the number of strikes.

Having identified New York as the top state with significantly elevated costs, I proceeded to investigate which animals were responsible for the most damage and when these incidents occurred:

- Produced another butterfly chart, juxtaposing strikes against total cost by species to identify the animal causing the most damage in 2009.
- Generated a bar chart to identify the month with the highest costs in 2009.

Upon pinpointing January as the month of interest, I delved deeper to identify the specific date:

- Utilized a bar chart to determine the day with the highest costs in January 2009.
  
The answer was January 15th, 2009, famously known as 'The Miracle on the Hudson,' an incident that incurred over 40 million dollars in damages.

I conducted further research into this incident, concluding that even though wildlife safety protocols have improved, complacency can set in over time. Repeating an incident like the one on January 15th, 2009, would have severe implications for operating costs and consumer trust.

To gain insights into future trends regarding the number of strikes and the associated damage:

- Created a line chart with a forecast to project the number of strikes beyond the available data.
- Developed another line chart with a forecast to predict the amount of damage caused by collisions extending into 2015.

While both strikes and indicated damage increased, the majority of the damage remained classified as "none." Nonetheless, maintaining vigilance in safety protocols remains a prudent course of action.

## Future Goals
If I had more time I would want to connect a database with the number of flights coming out of each airport, to tell which airports have the highest percentage of wildlife strikes.

