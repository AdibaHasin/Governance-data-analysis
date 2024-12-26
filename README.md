This project analyses governance trends across various regions and years using a dataset of governance indicators. Key objectives include identifying regional governance trends, exploring variability within regions, and investigating global governance changes over time.

Dataset
-------
Source
-------
The dataset includes governance estimates by country and year. Key columns:
•	countryname: Name of the country.
•	region: Region to which the country belongs (e.g., Asia, Europe).
•	year: Year of observation.
•	estimate: Governance score (positive values indicate better governance, negative values indicate worse governance).
•	GDP: Gross Domestic Product of the country.
•	log_GDP: Log-transformed GDP for scale normalization.

---------------------------------------------
Key Analyses and Insights
---------------------------------------------
Global Governance Trends
   ---------------------------------------------

•	Analysis: Examined average governance estimates globally over the years.
•	Visualization: A time-series plot showed fluctuations in global governance.

•	Key Insight:
----------------
1.	A notable dip in governance around 2005, followed by gradual recovery post-2010.
2.	Stabilization near -0.1 in recent years, indicating limited global progress.
   
Regional Governance Trends
   --------------------------------------

•	Analysis: Investigated governance trends over time for different regions.
•	Visualization: Line plots of governance scores by region.

•	Key Insights:
-----------------------
1.	Europe: Consistently the highest governance scores, with steady improvement.
2.	Asia: Gradual recovery post-2010, but governance remains below global averages.
3.	Africa: Lowest governance scores, with slight improvement over time.
4.	Oceania: Declining governance trend after 2005.
5. 	South America: Decline after 2000, with slight recovery post-2015.
   
   Governance Variability by Region
   ------------------------------------
•	Analysis: Calculated the standard deviation of governance scores within each region.
•	Visualization: Bar chart showing variability.

•	Key Insights:
---------------------
1. Europe: Highest variability, indicating a mix of strong and weak governance across countries.
2.	Africa: Lowest variability, reflecting uniformly low governance scores.
3.	Asia: Moderate variability, consistent with a mix of developing and developed countries.
   
   Top and Worst Performers
   ---------------------------
•	Analysis: Ranked countries by their average governance scores across years.

•	Key Insights:
--------------------

1.	Top Performer: Singapore consistently achieved the highest governance scores globally.
2.	Worst Performer: Somalia consistently had the lowest governance scores globally.
   
   Time-Series Analysis
   ----------------------------
•	Analysis: Investigated governance trends globally and by region over time.
•	Visualization: Line plots with confidence bands for variability.

•	Key Insights:
--------------------

1.	The 2005 dip and post-2010 recovery were driven primarily by trends in Asia and Africa.
2.	Europe’s steady improvement stabilized global governance trends.
   
   Analysis of Governance and GDP
   ----------------------------------
•	Analysis: Merged GDP data with governance scores to explore their relationship.
•	Key Insights:
o	Correlation:
1.	Raw GDP and governance scores showed a very weak correlation, suggesting economic size alone does not explain governance quality.
2.	Log-transformed GDP showed a slight negative correlation with governance scores, indicating that wealthier countries may still face governance challenges.


Visualization:
-----------------
- Scatter plots revealed clustering near lower GDP values, with governance scores spread across the range and no strong linear relationship.

Outliers:
-------------
- Countries with exceptionally high or low governance scores (e.g., Singapore and Somalia) stood out for further investigation.
________________________________________

Next Steps

1.	Deeper Regional Analysis:
-	Investigate specific countries driving trends within regions.
-	Explore governance disparities within Europe and Asia.
  
2.	Event Correlation:
-	Align governance trends with global events (e.g., conflicts, economic crises).
  
3.	Policy Recommendations:
-	Identify successful governance strategies in top-performing regions and countries.
  
4.	Further Data Integration:
-	Include economic indicators (e.g., GDP growth rates) to explore correlations with governance.
________________________________________

