# IndiGo-US-OTAR-Analysis
A data analysis project for IndiGo Airlines' entry into the US market. This project identifies key factors influencing On-Time Arrival Rate (OTAR) using 2015 US flight data, providing data-driven strategies to maximize operational efficiency and punctuality.


1. Project Title / Headline
✈️ IndiGo OnTime Performance Dashboard: Maximizing Punctuality in the U.S. Market
A comprehensive data analysis project that identifies key drivers of flight delays and provides actionable, databacked strategies to maximize the OnTime Arrival Rate (OTAR) for IndiGo's new U.S. operations.

2. Short Description / Purpose
This project analyzes a massive dataset of over 5.8 million U.S. domestic flights from 2015 to uncover the root causes of delays and provide IndiGo with a clear roadmap for improving punctuality. The goal is to help IndiGo establish itself as a reliable and efficient airline in the highly competitive U.S. domestic market by focusing on operational excellence.

3. Tech Stack
The analysis was built using a standard data science workflow:
 🐍 Python – The primary programming language for data manipulation and statistical analysis.
 📊 Pandas & NumPy – Core libraries for data cleaning, transformation, and numerical computations.
 📈 Matplotlib & Seaborn – Libraries used for creating insightful visualizations and charts.
 📉 Scipy.stats – Used for performing statistical tests (like Ttests) to validate hypotheses.
 🛠️ Google Colab – The cloudbased environment used for running the analysis code.

 4. Data Source
 Source: U.S. Department of Transportation, Bureau of Transportation Statistics (2015 Flight Data).
 Dataset: `Flights_Dataset` containing 5.8 million records of U.S. domestic flights with 31 columns detailing schedules, delays, airports, and cancellation reasons.

 5. Features / Highlights

 Business Problem
  IndiGo is entering the competitive U.S. aviation market, where factors like cascading delays, weather, and airport congestion can severely impact customer trust and operational reliability. To succeed, they must identify what causes delays and proactively fix them.

 Goal of the Analysis
  To pinpoint the most significant factors affecting flight punctuality (OTAR) and provide a clear, datadriven action plan for IndiGo to minimize delays, improve efficiency, and build a reputation for reliability.

 Walkthrough of Key Insights & Visuals

   Cascading Delays are Critical: A powerful scatter plot and Ttest proved that flights with a departure delay of 15+ minutes almost always lead to significant arrival delays. This is the single biggest lever for improving OTAR.
   Winter is the Biggest Weather Challenge: A boxplot and bar chart clearly showed that weatherrelated delays are significantly longer and more variable in winter compared to summer.
   Turnaround Efficiency Matters: Correlation analysis revealed that longer taxiout times and late aircraft from previous flights have a strong negative impact on whether a flight arrives on time.
   DayofWeek Patterns: A simple bar chart identified that Saturdays are the most punctual day, while Thursdays are the worst, highlighting opportunities for schedule optimization.
   Route Performance: An analysis of specific airport routes identified topperforming airports (like Dane County Regional and LaGuardia) that can serve as models for operational excellence.

 Business Impact & Insights
   Immediate Action: By focusing on minimizing departure delays, IndiGo can prevent over 37% of arrival delays from ever happening.
   Seasonal Planning: Proactive scheduling and resource allocation during winter months can mitigate the severe impact of weather.
   Ground Operations Focus: Optimizing taxi times and aircraft turnaround processes on the ground directly translates to better punctuality in the air.
   Strategic Scheduling: Adjusting schedules and resources based on daily and seasonal patterns can maximize efficiency across the entire network.

 6. Screenshots / Demos
[Note: This is where you would insert key charts from your PDF, such as the scatter plot of Departure vs. Arrival Delay, the boxplot of Weather Delays by Season, or the bar chart of OTAR by Day of Week.]

Alt Text Example: "A scatter plot showing a strong positive relationship between flight departure delays and arrival delays, confirming the cascade effect."

