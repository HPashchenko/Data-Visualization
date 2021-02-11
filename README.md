# Data-Visualization
This database consists of the information of approximately 7M bike riders from 2017-2020 years, including the duration_sec, the trip start/end time, start/end name station, main information as user_type, and additional information as Longitude and Latitude. The dimension of the dataset was reduced, approximately 2M rows were dropped from the analysis due to missing information(NaN)

## Summary of Findings
In this exploration, I found that there are two types of client using the service Ford GoBike System. The first one is customers who use the system on weekends to explore th city, and the numbers of customers are significantly growth from July to November. The second one is subscribers who use the service mainly daily, probably just to commute at work and get back, since hours for sharing 8-9 am and 4-6 pm. Moreover, I was interested of calculated the distance of each trip, so I applied a math formula based on Longitude and Latitude to deduct distance in km. The customers prefer to use the Bikeshare on weekends and for long trip destination, and the subscribers use the service on Monday-Friday just for short destination.

## Key Insights for Presentation
For the presentation, I focused on types of users, subscribers, and customers. Afterward, I introduce each of the types using weekly and monthly preferences. In this case, I selected a heatmap to represent this information. Then I focused on the distance of each type. 
In conclusion, despite the fact that the customers use the service on Weekends and for the long-trip destination, the describers are still more profitable for the company.
