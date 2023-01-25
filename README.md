# Google-Data-Analytics-Capstone
Google Data Analytics Capstone project files
Questions to Answer:

How do annual members and casual riders use Cyclistic bikes differently
Why would casual riders buy Cyclistic annual memberships?
How can Cyclistic use digital media to influence casual riders to become members?


You will produce a report with the following deliverables: 


1. A clear statement of the business task 
2. A description of all data sources used 
3. Documentation of any cleaning or manipulation of data 
4. A summary of your analysis 
5. Supporting visualizations and key findings 
6. Your top three recommendations based on your analysis

Business task:
The task at hand is to analyze 12 months worth of Cyclistic data to find what ways casual riders and annual members use Cyclistic bikes differently. From these findings, suggestions will be made to key stakeholders on how to move forward in converting casual riders to annual members.

Data sources used:
Data provided by Motivate International Inc. under license.

Cleaning and manipulation of data:
Find ride length by by subtracting the end time from the start time
Remove all rides less than 0:01:00 by creating a filter in the new “ride_length” column and selecting all data points below 1 minute.
Find the ride length of each ride and convert length to standard timing conventions
Find most popular day of the week for all riders
Find average ride length for all populations
Find longest ride amongst all trips

Create pivot tables for the following:
Average length of rides
Average ride lengths per day
Total rides per day for each casual/member

Create new database with excel:
Total rides per month
Average ride length per month
Mode day of the week per month
Average ride length on mode day per month (Convert to average duration as it is difficult to visualize using the time set up provided in case study)

Visualizations: Created with Tableau

Findings:
In general Member riders take more trips, however their average ride length is significantly shorter. The most popular day of the week for Member riders is on Thursday, as opposed to Saturday for casual riders. This could indicate that members are utilizing the services for shorter commutes, possibly to and from their places of employment. Casual riders tend to have longer trips and on weekends, indicating they use the services for leisure. Both type of users see increases in the use starting in the Spring (March) while peaking in Summer (July) then a decrease into the Fall (October). Weather and climate certainly impact the usage of the bikes for both types of users. Casual riders' most used bike is the electric bike, whereas member users' most used style was the classic bike.

Recommendations:
1. Showcase the cost efficiency of becoming a member to casual riders, as they may be spending more to take longer rides by utilizing single rides at a singular price point, whereas if they become members, they could save money and still enjoy the same number and length of rides.
2. Offer casual users a reduced cost start up membership in the Spring, they can use the services at a lesser cost, at a more optimal time of the year for better weather and entice them to continue using the services on a more regular basis.
3. Move away from the availability of docked bikes, as both users use other modes far more often and member users don’t use them at all. 
