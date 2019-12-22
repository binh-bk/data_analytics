# Communicate Data Findings: Ford GoBike in San Francisco

## Binh Nguyen
## December 21, 2019

# Introduction:

- Ford GoBike is a system that rent tradition bike with recent added ebike for metropolitan residers and visistors for short travels. By the end October 2019, The Bay Wheels, renamed of Ford GoBike after acquired by Lyft in July 2017, operated with 2600 bikes and 260 stations. For Bay Area, there mains servering regions are Downtown San Franciso, East Bay, and San Jose.

- We will download and use the Python libraries (mostly pandas, Matplotlib, Seborn) in Jupyter Notebook to explore and gather some insights about this system. The dataset after cleaning contains about 4.5 million rows and 13 columns. The columns tracked the duration, bike, station, and user type. Subscribers are who paid monthly rate ($15) and Customers paid as their ride ($2 per first 45 minutes). 

# Summary of Findings:

## Loading during the year

- Bike was used more in the summers and less in the winters in the same year. The highest loading was about 70 rides per bike per month in October 2018. In the winter of 2019, the loading was 40-50 rides per bike per month.
- Summer of 2019, the loading was lower than 2018, about 60 rides per bike per month
- This pattern would explain the effects of weather to the users in which the winter is colder and windy. The summers are a better time for using bike either for commute or for pleasure

## Riding duration, distance and speed
 
- On average, Subsribers use bikes for 11 minutes/trip with 50% of riders use bikes for less than 9 minutes, an average riding distance is 1.7km/trip with an average speed of 10km/h
- On average, Customers use bikes for 30 minutes/trip with 50% of riders use bikes for less than 15 minutes. They traveled an average distance of 1.9km/trip and 7.3 km/h.
- The Subscribers used bikes more during 8-10AM, 5-6PM during the weekdays which suggests the bikes were used for short commute
- The Customers used bikes more during the weekends around afternoon, and durng 4-6PM during weekdays. This suggests the Customers used bike for pleasure and visiting.

## Ridership

- Most the riders are subscribers who paid for a montly membership. By Oct 2019, the total users about 240K, and the Subscribers are about 4/5. The accumulated daily average of the Subscribers are about 4M seconds and for Customers are about 2M seconds.

## Frequent stations in Downtown San Francisco

- We will look at the freqent use station in the Downtown. There are two main serving areas in San Francisco is the East Bay and in San Jose.
- Most visited stations located on Market St., where there is an Metro line operated. Some frequent stations located near the shoreline of the Bay. These characters confirm two main uses of the bike are for short commute and visiting.
- The end stations are more spread out implied that the riders stoped the ride unplanned or swith to other transportation.
