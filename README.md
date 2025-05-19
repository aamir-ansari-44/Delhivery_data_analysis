# Delhivery_data_analysis
**Introduction:**  
Delhivery is the largest and fastest-growing fully integrated player in India by revenue in Fiscal 2021. They aim to build the operating system for commerce, through a combination of worldclass infrastructure, logistics operations of the highest quality, and cutting-edge engineering and technology capabilities.
The Data team builds intelligence and capabilities using this data that helps them to widen the gap between the quality, efficiency, and profitability of their business versus their competitors.

**The Problem Statement**  
The company wants to understand and process the data coming out of data engineering pipelines:
•
Clean, sanitize and manipulate data to get useful features out of raw fields
•
Make sense out of the raw data and help the data science team to build forecasting models onit.

**Conclusion**  
1.
The data set is corresponding to only 2 months, so not much can be concluded about the seasonal or month-over-month or year-over-year patterns.
2.
There is a significant difference between actual_time and segment_actual_time_sum which shows there is discrepancy in data entry.
3.
There is a significant difference between actual_distance_to_destination and osrm_distance which shows that the ML model’s prediction is statistically significantly wrong or the delivery executives are not following the predetermined route.
4.
There is a significant difference between segment_osrm_time_sum and osrm_time which shows that the ML model’s prediction is statistically significantly wrong.
5.
The top 5 states are : maharashtra, karnataka, haryana, tamil nadu, telangana
6.
The top 5 cities are : bengaluru, mumbai, gurgaon, delhi, hyderabad
7.
The day on which most orders are generated is a Wednesday.

**Recomendations**  
•
Should work on imroving the ML model to improve business.
•
Should focus more on those states and cities that provide us with more business by enabling more carries and better infrastructure.
•
Should be ready with more orders on Wednesday by enabling long-shifts and getting more work force.
