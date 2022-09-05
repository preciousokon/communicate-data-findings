# Communicate-data-findings

This project is aim at testing my Data Exploration/visualizations skills as well as my skills on communicating a Findings gotten from anlysis to the end users

The dataset I'm using is from Bay wheels (previously known as Ford GoBike) is a regional public bike sharing system in the San Francisco Bay Area, California. Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States with nearly 500,000 rides since the launch in 2017 and had about 10,000 annual subscribers as of January 2018. The dataset used for this exploratory analysis consists of monthly individual trip data from January 2018 to December 2018 in CSV format covering the greater San Francisco Bay area, also available here.

Some Data wrangling process:

I changed multiple columns that are not in the correct dtype, i.e. start_time, end_time should be datetime type, user_type and member_gender should be categorical data type, etc

Added New Columns: start_day, start month, start hour, end day, end month and end hour 

Change Datatype for the new columns to categorical data type

## Summary of Findings
* The Data provided entails information for only the month of February and March

* There were more male users than female users

* Most users started their ride on the 8th, 9th which indicate morning rush to work and the ended their rides on 17th and 18th
  hour which indicate rushing hours home from work
  
* The user type 'Subcribers' took the most ride than Customers

* More Subscribers shared their bike and no customer was allowed to shared their ride

* They were more rides on Tuesday and Thursdays which are weekdays

* The Gender category 'Other' prefer going on ride during weekends especially on Sunday and they usually have ride duration of 
  over 1800 per seconds during weekends
  
* Other gender has long duration when the start their ride at the 2nd or 3rd hour and they also had longer ride duration than
  male and female user
  
* Male alway start rides earlier than female and other gender

* There is a positive relationship between start day, end day as regard duration. As start day increases, end day tends to 
  decrease and vice versa.
  
## Key Insights After Visualization
My major in this analysis was to find out the duration each gender takes on rides and which particular day each gender like going on rides. The gender type 'order' had longer ride durations during the weekends than male and female gender. Subscribers embarked on more ride during workdays i.e monday-friday, customers made more rides during the weekends.


