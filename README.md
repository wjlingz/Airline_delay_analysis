# Airline_delay_analysis
A project for data management course in UKM master's degree course (Assignment_2)
<br></br>
![image](https://github.com/user-attachments/assets/ffe5b4bd-6b7f-4987-a963-79a501d8b9cc)
[image_source](https://www.flightglobal.com/analysis/airline-coronavirus-recovery-tracker-september-2021-update/145447.article)

Airplane as a form of transportation is prone to variance in schedule, causing delayed arrivals or cancelled flights. These disruptions can have significant impacts on passengers and airline operations. These delays can result from a variety of factors such as weather conditions, technical issues, or air traffic congestion. Without a clear understanding of these patterns, it becomes difficult to implement effective solutions and minimize disruptions. Therefore, there is a critical need to analyze delay patterns in airlines to identify underlying causes, improve scheduling accuracy, and enhance overall efficiency in air travel.

### Aim of the analysis
The aim is to identify the reasons that cause the delays and cancellations in the U.S airline companies, and possibly suggest improvements that can be considered to tackle the problem.   
To achieve the aim, we use a dataset from Kaggle [(Data Expo 2009: Airline On Time Data)](https://www.kaggle.com/datasets/wenxingdi/data-expo-2009-airline-on-time-data/data?select=2007.csv) to perform analysis and search for answers to the following questions:
1. Delay Patterns:
- What times of day (morning/afternoon/evening) have the lowest average delays?
- Which days of the week show better on-time performance?
- During which months or seasons are flights most likely to be on time?
2. Delay Factors:
- Identify and rank the top 3-5 factors contributing to flight delays, based on the delay categories provided in the dataset.
- Quantify the impact of each factor (in minutes of delay and percentage of total delays).
3. Cancellation Analysis:
- Identify the primary reasons for flight cancellations as categorized in the dataset.
- Determine if cancellations correlate with specific airlines, airports, or time periods.
4. Problematic Routes:
- Identify specific routes (origin-destination pairs), carriers, or flight numbers that show consistently poor performance.
- Analyse the reasons these particular flights are prone to delays or cancellation.


### Conclusion
We have analyzed the airline performance in several area such as the delay pattern, delay factors, cancellation analysis, and problematic routes etc., and the results have been shown in graph for an easy overview. For customers, they should use this information to select the airlines and best schedules to plan for their vacation / work travel. For airline companies, they should recognize how much have these factors contributed to the performance degradation of their flights. The analyses should provide a good starting direction as to where to investigate and tackle the problems presented.

From a scheduling perspective, it can be adjusted to balance loads to improve overall performance. For airlines, the operational efficiency should be investigated to reduce each and every causes that contribute to delays under "carrier reason". For airports, the facilities should be improved to make departure process smoother, more consistent, and more resistant to weather conditions. The location of the airport should also be considered in terms of traffic and routes when doing scheduling and rerouting.

One limitation of the current analysis is the lack of modeling for the interconnectivity and flow dynamics of flight routes. Future improvements could incorporate a network-based approach, such as graph theory or complex network analysis, to capture route centrality, hub connectivity, and propagation of delays across the network. This would enable a more comprehensive understanding of systemic vulnerabilities in the airline route structure.

Overall, this analysis aims to drive data-informed decisions that improve customer satisfaction and operational efficiency across the airline industry.

