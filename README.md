# DASHBOARD-DEVELOPMENT

COMPANY: CODTECH IT SOLUTIONS

NAME: PRISCILLA M

INTERN ID: CT04DN1650

DOMAIN: DATA ANALYSIS

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH

*DASHBOARD ON INDIAN ACCIDENT ANALYSIS*

The dataset includes a variety of accident-related parameters collected across multiple Indian states during 2022 and 2023. It encompasses details such as accident severity, weather conditions, location, time, driver and casualty demographics, vehicle information, and environmental factors.

The goal of the dashboard is to uncover meaningful insights from the data by identifying accident hotspots, patterns across weekdays and times, weather and light condition impacts, and the influence of vehicle and driver demographics.

** Dataset Summary
The dataset used for this task contains 1,000 records with 29 columns. Key columns include:

Num_Acc: Unique accident ID

inverse_data: Date of the accident

hrmn: Time of the accident (converted into proper time format and categorized by time of day)

state, location, week_day: Geographical and temporal context

severity, casualty_severity: Accident and injury severity

weather, lum: Environmental conditions

vehicle_type, vehicle_model, engine_size: Vehicle-related data

driver_age, driver_sex, casualty_age, casualty_sex: Demographic information

To improve readability and analytics, a number of transformations were applied using Power Query including time formatting (hrmn → Accident_Time) and time-of-day bucketing (Morning, Afternoon, Evening, Night).

** Dashboard Highlights
The Power BI dashboard consists of multiple interactive visuals grouped into relevant sections:

1. KPI Cards
Total number of accidents

Total fatal accidents

Severe accident count

Total casualties

These KPIs provide a quick summary of the overall situation.

2. Time Series Analysis
   
A line chart shows the trend of accidents over time.

4. Location-Based Insights
   
A bar chart highlights the top 10 most accident-prone locations.

Slicer filters allow users to view accidents state-wise gender wise

4. Demographic Distribution
   
Casualty and driver gender breakdown

Time of day impact on accident occurrences

5. Environmental Conditions
   
Weather condition and light condition (lum) breakdowns using pie/donut charts

Severity distribution across different conditions for comparative analysis

6. Interactivity and Slicers

To allow flexible filtering and deeper insight, slicers were added for:

State

Driver Sex

These slicers help users dynamically control the data displayed across all visuals and tailor analysis to specific dimensions.

** Key Insights
Accidents are more frequent during the evening and late-night hours.

Severe and fatal accidents are most common during poor weather or nighttime.

Car and motorcycle accidents dominate the dataset.

Some states and locations consistently show higher accident rates, indicating potential hotspots needing targeted attention.

** Tools and Technologies
Power BI Desktop – Data transformation, visualization, and dashboard creation

Power Query Editor – Data cleaning, formatting, and calculated column creation

*Output*

