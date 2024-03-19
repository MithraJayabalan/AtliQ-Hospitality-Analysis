# AtliQ-Hospitality-Analysis
## Project Overview
AtliQ Grands owns multiple 5 star hotels across india. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of AtliQ Grands wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.
## Objective
As a data analyst, the objective was to create dashboards for the revenue management team of AtliQ Grands hotels to provide insights on revenue trend.
## Data Information
 The dataset for this analysis was taken from the codebasics website from resume project challenge number 1
 The dataset comprises the following csv files:
* dim_date  - data includes date, month year, week no and daytype
* dim_hotels - this has information about the hotels like property_id, name, category and city
* dim_rooms - this file includes room_id and room class
* fact_aggregated_bookings - this file includes aggregated data on the bookings like property_id, checkin date, room category, successful bookings and category.
* fact_bookings - this includes booking_id, property_id, booking date, checkin date, checkout date, no of guests, category, revenue realized and revenue generated
#### Tools used - Power bi
#### Database - Excel files
## Process includes the following:
* Extracting the data
* Cleaning and transforming the data 
* Data modelling
* Creating dax measures 
* Validating the data
* Creating visualizations
## Domain Knowledge
* Average Daily Rate(ADR) - The ADR is useful to measure a property’s financial performance, as well as to compare the hotel’s performance to its competitors.
* Revenue Per Available Room(Revpar) - RevPAR represents the success the hotel is having at filling its rooms. Increasing RevPAR means either that rates or Occupancy Rate are rising, or both.
* Occupancy% - Occupancy rate in hotels is an important KPI for hotel revenue management in order to understand how many of the available rooms are actually being used.
* Daily Sellable Room Nights(DSRN) - The metric serves as a guide to understanding a hotel's dominance and demand in the marketplace.
* Daily Utilized Room Nights(DURN) - Daily utilized room nights are important in the hospitality industry as they directly impact revenue generation, occupancy rates, and overall profitability of a hotel or lodging establishment.
* Daily Booked Room Nights(DBRN) - Daily booked room nights are crucial in hospitality for revenue, occupancy rates, and business performance, guiding pricing strategies and maximizing profitability.
  ### Insights
* Total Revenue for 3months from all the hotels is $1.71 billion and overall average rating is 3.62.
* Revpar fluctuates over the weeks, ranging from a low of 6450.75 to a high of 8311.06.
* ADR also varies throughout the weeks, with values ranging from 12602 to 12753
* Occupancy percentages fluctuate between 50.96% and 65.31%.. There are noticeable variations in occupancy rates across the weeks.
* There is a relatively small difference in the realization percentages among the platforms, with the direct offline platform having the highest realization percentage at 80.83%, followed closely by logtrip and others.
* In terms of ADR, the platforms have similar rates, with tripster having the highest ADR at 12,779.52 and direct offline having the lowest at 12,791.17.
* Luxury generates higher revenue compared to the business category when analyzed.
* Delhi leads with the highest average rating of 3.8, followed closely by Hyderabad and Mumbai at 3.6, and Bangalore at 3.4.
* The Elite room class generates the highest revenue, followed by Premium, Presidential, and Standard rooms, indicating varying levels of demand and pricing strategies.
* The Presidential room class receives the highest average rating, indicating that customers perceive it as offering exceptional quality or service.
* "Others" booking platform dominates with the highest revenue, potentially indicating diverse sources or multiple booking platforms aggregated under this category.
* When we see the revenue based on the cities Mumbai generates the maximum revenue of 669 M
* Out of all bookings 70% was successful checkouts, 24% were cancelled and 5% were no shows
* AtliQ exotica yields the highest revenue 320M which belongs to luxury category, followed by AtliQ palace & AtliQ city which belongs to business category with the revenue of 304 M & 285 M respectively. Then follows AtliQ Blu, Atliq bay and AtliQ grands. AtliQ seasons has the lowest revenue.
* When we see the average rating AtliQ Blu has the highest rating  of 3.96  AtliQ seasons has low rating.
* AtliQ Exotica has the highest DSRN at 445, indicating it might be the best-performing property in terms of daily sales revenue. Atliq Grands also has the lowest DBRN and DURN, indicating potentially lower booking rates and lower daily utilization compared to other properties. AtliQ Seasons has the lowest values across all metrics, suggesting it might be the least performing property among those listed.
* Atliq hotels in Mumbai  city has the highest bookings of  43k in 3 months followed by Hyderabad, Bangalore and Delhi.








