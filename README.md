# Analysis of Citi Bike Data using Tableau

See Tableau Story ->>> [Link to Dashboard](https://public.tableau.com/app/profile/brett.bertoni/viz/NYCCitiBike_16573945235420/NYCStory?publish=yes)

![first](./Images/first.png)

## Overview

Using bike sharing data to determine how to successfully implement a bike sharing service in Des Moine, Iowa. Data was provided in CSV format. Tableau was used to create visualizations to make the data more meaningful and draw conclusions which help create a successful business plan. In the process, data cleaning was needed so the CSV file was read in to a dataframe where some work was done. The dataframe was then exported back to CSV format and then re-loaded in to Tableau. Please see the full story (link above).

## Results

![peak hours](./Images/peak%20hours.png)

The most popular times for bike rentals are during commute times (approx. 7am-9am & 4pm-7pm). Generally speaking, day time (9am-4pm), is also active.

![trips by hour](./Images/trips%20by%20hour.png)

This heatmap reinforces what the previous chart shows (peak hours tend to be commuting times). It also shows which days of the week tend to have the most rentals. Weekdays tend to have very busy rental times around commuting times whereas weekends are generally active from 9am-6pm.

![bike use](./Images/bike%20use.png)

This heatmap shows every bike (represented as bike id) and the amount it is used. The darker and larger the marker, the more the bike is used. This is important to note as the bikes which get used heavily will generally need more maintenance/repairs. Certain times (not peak hours) should be set aside for such work. 

![checkout by gender](./Images/checkout%20times%20by%20gender.png)

The number of bikes rented vs the number minutes the bike is rented for. The most popular rental durations are a very short amount of time (5-6 minutes). It also important to note that gender does not seem to make a difference. Although there are a high number of males who use the service overall, both males and females tend to have similar tendencies.

![subscribers](./Images/subscribers.png)

First, a look at subscriber vs customer. A subscriber is a user who is subscribed to the bike sharing service whereas a customer may be a one time user or a user who has not subscribed. Subscribers outnumber customers each and every day of the week. This is true for both male and female users.

## Summary
