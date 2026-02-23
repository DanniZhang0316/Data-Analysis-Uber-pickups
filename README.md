# Uber Pickups in New York City – Data Analysis

This analysis is based on the [Uber Pickups in New York City Dataset (Kaggle)](https://www.kaggle.com/datasets/fivethirtyeight/uber-pickups-in-new-york-city/data). The dataset contains six monthly Uber trip record files covering April to September. Each record includes four attributes:
- Pickup date/time  
- Pickup latitude  
- Pickup longitude  
- TLC (Taxi & Limousine Commission) base company code  

After merging all files, the final dataset contains approximately **4.5 million trip records**.

## Project Objective

The objective of this project is to analyze Uber usage patterns across New York City's boroughs. The analysis focuses on identifying temporal trends (peak hours, weekday vs. weekend differences) and spatial demand patterns.

The project aims to:
- Reveal travel behavior patterns across different time periods  
- Identify high-demand pickup areas  
- Provide data support for optimizing vehicle dispatch  
- Improve service efficiency and user experience  

## Key Findings

### 1. Monthly Trends
- Overall demand shows steady growth.  
- **September** reaches the highest trip volume.  
- A noticeable spike occurs in late April, which may require further investigation to determine whether it is an anomaly.

### 2. Weekly Patterns
- **Thursday and Friday** have the highest demand.  
- **Sunday** has the lowest demand.  
- Average weekday (Monday–Friday) demand is **19.6% higher** than weekend (Saturday–Sunday) demand.

### 3. Hourly Distribution
- The **evening peak (16:00–19:00)** is the busiest period.  
- Other peak periods include:
  - Morning commute (6:00–9:00)  
  - Late evening (22:00–24:00)

### 4. Weekday vs. Weekend Differences
- Weekend morning peaks are not obvious due to reduced commuting.  
- Late-night trips (0:00–2:00) are significantly higher on weekends than on weekdays.

### 5. Monday Characteristics
- Monday has the lowest demand among weekdays, about **20% below** the weekday average.  
- Morning usage (7:00–8:00) is about 90% of the weekday average.  
- Evening peak (16:00–18:00) is only 79% of the weekday average.

### 6. Geographic Heatmap Insights
- **High-demand hotspots:** New York City core areas, New Brunswick, Stamford.  
- **Low-demand areas:** Springs, Milford, Peekskill and other small towns.  
- **Potential outliers:** Locations such as Southbridge appear disconnected from the main service area and require further validation.

## Conclusion

The analysis reveals clear temporal and spatial demand patterns in Uber usage. These findings can support better fleet management, dispatch optimization, and overall service improvement.
