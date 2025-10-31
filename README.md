# IndiGo-US-OTAR-Analysis
A data analysis project for IndiGo Airlines' entry into the US market. This project identifies key factors influencing On-Time Arrival Rate (OTAR) using 2015 US flight data, providing data-driven strategies to maximize operational efficiency and punctuality.

This project was built to help IndiGo Airlines optimize its On-Time Arrival Rate (OTAR) as it entered the U.S. domestic aviation market. It analyzes U.S. domestic flight operations data of the year 2015. 
The team needed clarity on what factors were driving late arrivals—whether it was departure delays, turnaround inefficiencies, or seasonal weather—and how to improve OTAR to build customer trust and operational reliability.

The goal was to analyze this data using Python to identify the key drivers of OTAR. 
The flow of the analysis done on Python was: Data import → Data cleaning & missing value handling → Outlier capping → OTAR calculation → Exploratory Data Analysis (EDA) → Hypothesis testing (cascade delays, seasonal weather, turnaround efficiency, weekday patterns) → Route-level analysis → Strategic recommendations.
This included examining delay types, flight schedules, airport performance, and turnaround metrics—so IndiGo could make data-driven decisions to improve punctuality.
I discovered that departure delays had a strong cascading effect on arrival delays, with a correlation coefficient of 0.86. Flights delayed by more than 15 minutes at departure had an average arrival delay of nearly 38 minutes. Winter months showed significantly higher weather-related delays, and longer turnaround times (taxi-in, taxi-out, and late aircraft delays) were linked to lower OTAR. Saturdays had the highest punctuality, while Thursdays lagged behind.

The following insights were recommended:
Prioritize gate and crew management to reduce departure delays
Optimize turnaround processes to improve efficiency
Adjust scheduling and resource allocation based on day-of-week and seasonal patterns
Focus on high-performing routes and airports to maintain reliability
By implementing these strategies, IndiGo can enhance its reputation as a dependable carrier and scale efficiently in the U.S. market.
