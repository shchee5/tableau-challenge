# Citi Bike Tableau Challenge

## Background
We have been tasked to create a dashboard that reports on Citi bike usage data and provide an analysis on couple of findings from the dashboard.

## Dataset
This analysis uses Citi bike data from August 2020 and contains information including trip duration, station name, bike ID, user type, gender, year of birth, and more.

## Analysis

What days of the week and hours of the day do people use Citi bike the most?

- A large number of Citi bike usage occurred on Saturdays, accounting for more than 18% of all rides that took place in August 2020.
- While the number of rides that took place on Saturdays is higher than Sundays, the avg. trip duration is very similar at roughly 26 minutes (compared to avg. trip duration of roughly 21 to 22 minutes during weekdays).
- Most trips in August 2020 took place around 6PM (ET) while the highest avg. trip duration was at 2AM (ET). It makes sense that most trips would take place near 6PM as it is close to commuting (after work) and dinner times. Selecting on just weekdays will show a small peak in number of trips around 8AM (ET), which also aligns with commuting time to work.

Where is the most popular stations for Citi bike?

- The most popular stations to start riding from tend to be near the pier areas or in the middle of the city.
- Many riders return their bike to the same station as where they started while many others ride their bike alongside the coast and return the bike to a location south/north of where they started.
- Riders that start riding from the middle of the city tend to travel less farther than those who start riding near one of the piers.

What does the gender breakdown look like for Citi bike users?

- Based on the dataset, males tend to ride the Citi bike much more than females with males having almost 2x total number of trips than females in August 2020.
- Despite the higher number of trips from males, the avg. trip duration is slightly higher for females with females having avg. trip duration of 19 minutes versus males who have avg. trip duration of 17 minutes.
- The avg. age of riders is around 30 for customers and 37 for subscribers (note: customer = 24-hour pass or 3-day pass user versus subscriber = annual member). 
