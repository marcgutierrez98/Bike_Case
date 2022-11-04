# Bike_Case

How Does a Bike-Share Navigate Speedy Success?

ASK

Prepare to answer the question of 

“How do annual members and casual riders use Cyclistic bikes differently?”

  •	Identify trends for annual members

  •	Identify trends for casual riders

  •	Compare them and outline key differences

Key Stakeholders
  
  •	Director of Marketing
  
  •	Cyclistic Marketing Analytics Team
  
  •	Cyclistic Executive Team

Prepare


Data is first party and was taken from a certified company “Lyft Bikes and Scooters, LLC.”

Licensing can be found here https://ride.divvybikes.com/data-license-agreement

Data can be found here https://divvy-tripdata.s3.amazonaws.com/index.html

The goal of this case is to identify trends and outline key differences between the two types of customers, and this data allows us to solve the problem in hand so we can conclude that we can rely on this data.

This data is from January 2022 to March 2022. Data is recent and relevant.

Process

Data Cleaning Documentation


Cleaning is to be done using Google Sheets

Began by ensuring that there are no duplicates within the data

Added new column (Column N) named “ride_length”

Column was created by subtracting Columns C and D (“ended_at” – “started_at”)

Added new column (Column O) named “day_of_week”

Column was created by taking the day of which the ride began (Column C) which was the column named “started_at”

Found two entries where the ride length was negative and proceeded to delete these entries resulting in two less rows.

Analyze

Upon analyzing the data there were some discoveries made.

First, we have more members than we do casual riders.
	Total Members: 373,603
	Total Casual Riders: 129,816
	Grand Total: 503,419

Docked bikes were only used by casual riders and had the least amount of use. Both classic and electric bikes were more favored by both types of riders.

Monday, Tuesday, and Wednesday were the most popular day for members.

Saturday and Sunday were the most popular for casual riders.

Friday was the least popular day for both members and casual riders.

Overall the median ride length was greater for members than it was for casual riders.

The lowest median for members would be on Friday, meanwhile the lowest median for casual riders would be on Thursday.

Act

Being able to reward riders for using certain bikes (preferably docked bikes) can lead to casual riders that enjoy using these bikes into becoming annual members.

We noticed that casual riders enjoy using Cyclistic bikes on the weekend more, thus the company can offer an incentive for weekend riders.

Anomalies to Consider

There were instances of several rides that would last days or maybe a week, which then skewed some of the data. 

Therefore, some of the analysis was taken using the median ride length rather than the total sum or the average ride length.
