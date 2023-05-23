# Revenue Insights Hospitality Domain

Data

The data was picked from Code basics project challenge wherein the dataset was provided and asked to help the revenue team to provide insights to make actionable business decisions.

Introduction

AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of AtliQ Grands wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.

Their revenue management team had decided to hire a 3rd party service provider to provide them with insights from their historical data.

Data Analysis
Steps:

1. Understood the key business terminologies of Hospitality domain.
2. Understood the requirements by going through the requirements document which had details of the key indicators what do they mean and what the revenue team needs in the dasboard. 
3. Loaded the data from CSV files and used power query to load and transform the data.
4. As the Hospitality industry considers Friday and Saturday as weekends created calculated columns for day type (Weekend, Weekday).
5. Created the data model i.e. established the relationship among the tables and the result was a Star Schema.
6. Created measures for all the KPI's using DAX.
7. Designed the dashboard to provide Level 1 analysis. 


Dashboard:

![image](https://github.com/RohiniKonar/RevenueInsightsHospitalityDomain/assets/32761695/e1612743-fc50-4e64-8bea-4a8fad32192f)

Tolltip:

![image](https://github.com/RohiniKonar/RevenueInsightsHospitalityDomain/assets/32761695/ee0867a2-c9ff-4f19-8606-91105b23c7e8)


Insights:
1. Looking at the Trend by Key metrics visual it is clear that the ADR (Average Daily Rate) is not changing which meand AtliQ Grands does not have a dynamic pricing strategy. They sell the rooms at a flat price/fixed price irrespective of the day or city. 
2. The weekend and weekday key metrics table clearly stated that AtliQ Grands has not implemented a weekend/weekday pricing strategy. They are selling rooms for the same price for a weekend and a weekday.
3. There is a correlation between occupancy and rating i.e. we can look at the Property by Key metrics table and understand that if there is a low rating we can observe that occupancy% is also less.
4. Cancellation rate is higher for the hotels that have low rating so there is a relation between the ratings and cancellation rate.
5. AtliQ Grands does not use referencial pricing strategy i.e. they are selling on the highest price (ADR highest) on direct offline.
6. AtliQ Grands can also lower the prices on direct online channel i.e. own website as there is no commission they need to pay.

Actions/Recommendation for Revenue Team:
1. AtliQ Grands should use a dynamic pricing strategy and not run business with flat pricing.
2. AtliQ Grands should implement a weekend/weekday pricing strategy.
3. AtliQ Grands should work on the hotels which have the lowest ratings and look for opportunities or the business model that higest rating hotels use.
4. On improving the services for the hotels with lowest ratings the cancellation rate can also be improved because there is a direct relation between ratings and cancellation.
5. AtliQ Grands should use referencial pricing i.e. they should sell rooms on the lowest price on Direct Online which positively impacts on the revenue.
6. AtliQ Grands should sell thier rooms on comparatively less price on the online platform i.e. by using discount coupons so that the price comparison platform do not impact the choice when a customer performs a search.


Interesting learning:

1. WoW (week on week) change measure is a very useful measure which tells us the change in business week on week basis.
2. Used tooltip with the KPI's to show trends on weekly basis for all the months.
3. How conditional formating can be used to create interactive dashboard (week on week basis increase and decrease in KPI's).
