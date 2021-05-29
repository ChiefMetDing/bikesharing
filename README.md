# Citi Bike 2019 August Bike Sharing Analysis

(Please find graphs and charts in the following link. No graphs or charts is provided in this document. 
[link to dashboard](https://public.tableau.com/app/profile/ding.zhang/viz/M14Challenge/HowtoRideBikesElegantly "link to dashboard"))

## Overview
The analysis processed Citi Bike's bike sharing data obtained in August 2019 in New York City. The purpose of the analysis is to convince investors that a bike-sharing program in Des Moines is a solid business proposal, giving the fact that both cities are similar in the following ways:

- Are on the planet Earth;
- Have citizens know how to ride a bike;
- Have roads and streets.

## Results
### Starting and Ending Locations
It is interesting to see that during weekday’s peak hours, the ending locations in the afternoons are very close to the starting locations in the mornings. Same way, the ending locations in the mornings are very close to the starting locations in the afternoons. This suggests that the OPEX spent on relocating bikes during weekdays is low, because people tend to ride to work and ride back from work.

However, the starting and ending locations over weekends are in a completely different pattern to the weekdays'. This means it may require more bikes relocation moving between weekdays and weekends, to better serve the community.

### Number Trips by Weekday Hours
The analysis shows that the peak hours from Monday to Friday are 6 ~ 10 am and 4 ~ 8 pm. Over the weekend, the number of rides starts rising up at 9am and going down at 6 pm. The heat map plotted by genders shows the same pattern between male and female.

Different from the instruction, the analysis used Starttime on the x-axis instead of Stoptime. Reason being is that the purpose of this analysis is to show number of rides happen in different hours in different weekdays. Choosing Stoptime on x-axis shows number of rides start in different hours but end in different weekdays.

### Checkout Times Distribution
The graph shows that most of rides last around 5 mins. This conclusion applies to both male and female. The percentage passing minute plots show that less than 2% of the rides last longer than 1 hour. 50% of rides are less than 13 minutes. Moreover, the rides on weekdays tend to be shorter than rides on weekends. Female riders ride longer than Male riders do, no matter on weekdays or weekends.

### User Trips by Gender by Weekdays
The analysis shows both female and male subscribers ride more during weekdays, except for Wednesdays. However, non-subscribers tend to ride over weekends.

## Summary
In terms of bikes relocation, manpower required is higher when shifts between weekdays and weekends, which is Sunday night/Monday morning, Friday night/Saturday morning. Trips by weekday hours analysis suggests daytime maintenance should be scheduled between 10 am and 4 pm during weekdays. Checkout times statistics suggests that majority of rides are short time and probably short distance during weekdays. The rides are slightly longer during weekends.

There are two more additional visualizations suggested for future analysis:

- Popularity of stations. This will determine which station requires more maintenance and more investment.
- Bikes utilization by dates. This will help maintenance planning on individual bikes.

Conclusion: bike sharing business is highly recommended in Des Moines, because there are hours, weekdays, weekends, males, females, roads and streets in the city.
