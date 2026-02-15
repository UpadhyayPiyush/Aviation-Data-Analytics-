# Aviation Data Analytics 

## Project Overview 
This project analyzes operational and passenger performance of a fictional airline High Cloud Airlines using real-world airline industry KPIs. The goal was to build an end-to-end analytics solution — from SQL data validation to interactive dashboards — that helps stakeholders monitor airline efficiency, passenger demand, and network performance.  

The analysis was performed using MySQL for KPI computation, Excel for exploratory analysis, and Power BI for interactive visualization and decision-support dashboards.  

The final output includes dynamic dashboards showing flight activity, passenger volume, route demand, and aircraft capacity utilization.  

## Business Problem 
Airlines operate on very thin profit margins. Even small inefficiencies like empty seats, wrong routes, or poor scheduling can lead to significant revenue loss.  
High Cloud Airlines needed answers to key operational questions:  
- Are aircraft seats being utilized efficiently?
- Which routes have the highest passenger demand?
- Which carriers perform best operationally?
- Is demand driven by business travel or leisure travel?
- How should fleet allocation and scheduling be optimized?

Without a centralized analytics system, management relied on manual reporting, making it difficult to quickly detect inefficiencies or take timely decisions.

## Objective 
The primary objective of this project was to evaluate airline operational performance and support strategic decision-making by analyzing key airline KPIs.  

Key goals:  
- Calculate and analyze Load Factor % (Passengers / Available Seats)
- Identify Top performing carriers
- Detect high-demand routes
- Compare Weekend vs Weekday travel patterns
- Analyze distance-based flight distribution
- Track performance trends across year, quarter, and month
- Build an interactive dashboard for stakeholders

## Dataset Overview
The dataset contains airline operational data including flight schedules, passenger counts, and aircraft capacity.  

Key data fields:  
- Year, Month, Day (used to create date dimension)
- Carrier Name
- Origin City & Destination City
- Distance Group
- Available Seats
- Transported Passengers
- Flight Airtime

From these fields, a complete date calendar table was created:  
- Year
- Month Number & Month Name
- Quarter
- Year-Month
- Weekday Number & Name
- Financial Month & Financial Quarter

The dataset covers:  
- 110,000+ flights
- 187M+ passengers
- 82M+ miles flown
- 27M+ airtime hours

## Tools & Technologies 
- MySQL – Data validation, KPI calculations, and aggregations
- Power BI – Interactive dashboards and visualization
- Microsoft Excel – Exploratory analysis and secondary dashboard
- Power Query – Data cleaning and transformation
- DAX (Power BI) – Load factor calculations and measures

  
