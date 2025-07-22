# Smart farming sensor Analysis
*OVERVIEW

This report summarizes a dataset containing 500 rows of sensor and farming data related to crop yield prediction for the year 2024. The data includes information on various farms, identified by farm Id, across different regions such as 'Central USA', 'East Africa', 'North India', 'South India', and 'South USA'. Key features include the crop type (Cotton, Maize, Rice, Soybean, Wheat), soil moisture_%, soil_pH, temperature C, rainfall mm, humidity_%, sunlight hours, irrigation type, fertilizer type, and pesticide usage ml. Temporal aspects are captured through sowing date, harvest date, and timestamp, with total days representing the duration between sowing and harvest. The target variable is yield per hectare, representing crop yield. Location data is provided via latitude and longitude, and crop health is assessed using the NDVI_index and crop disease status.

Based on the first five sample data entries, we can observe variations in farming practices and environmental conditions across different regions. For example, 'North India' uses 'Organic' fertilizer and no irrigation for 'Wheat', while 'South USA' uses 'Inorganic' fertilizer and 'Sprinkler' irrigation for 'Soybean'. The average soil moisture_% is 26.75, with a standard deviation of 10.14, indicating variability in soil moisture levels. The mean soil pH is 6.52, suggesting slightly acidic to neutral soil conditions. The average yield kg per hectare is 4032.93, with a standard deviation of 1173.26, showing considerable yield variation. The NDVI index ranges from 0.30 to 0.90, with a mean of 0.60, reflecting varying levels of vegetation health. The crop disease status indicates the presence of mild to severe diseases in some farms.

*DATA SOURCE 

The data was gotten from kaggle[download here](https://www.kaggle.com/datasets/atharvasoundankar/smart-farming-sensor-data-for-yield-prediction?resource=download)

**TECHNOLOGIES USE FOR THIS PROJECT

Microsoft Excel (for data cleaning, basic statistics and insights)

Power BI (for DAX calculations, creating key performance indicators (KPIs)  power query and visualization).

*DASHBOARD
(<img width="1262" height="709" alt="Screenshot 2025-07-22 001307" src="https://github.com/user-attachments/assets/300066c1-3766-4aa6-99dc-e8d002de91f9" />

*RELEVANT ENQUIRIES FOR THE ANALYSIS

1. Line Chart: Yield Kg per Hectare vs. Harvest Date (Month)
   
•	Insight: Yield increases from April through June, peaking at nearly 728,039.50 Kg/Ha in June, then declines steadily in July and drops sharply in August.

•	Interpretation: This suggests that June is the most productive harvest month, likely due to optimal growing conditions. Post-June, environmental or agronomic factors may reduce crop productivity.


<img width="1267" height="701" alt="Screenshot 2025-07-22 003106" src="https://github.com/user-attachments/assets/b96036b3-081c-4004-927a-7fbb15bb5eb7" />

2. Scatter Plot: Avg Growth Duration vs. Yield Kg per Hectare vs. Crop Type
   
•	Insight:

o	Soybean has the highest yield (~425,000 Kg/Ha) and a growth duration of around 120 days.

o	Wheat also has high yields (~407,000 Kg/Ha) and a slightly longer growth period (~121 days).

o	Maize and Cotton have yields just below 400,000 Kg/Ha with growth durations around 117–119 days.

o	Rice has the lowest yield (~389,600 Kg/Ha) with a growth duration of 119 days.

•	Interpretation: Crops with longer average growth durations (e.g., Wheat and Soybean) tend to produce higher yields, suggesting a potential positive relationship between growth time and productivity.

<img width="1262" height="710" alt="Screenshot 2025-07-22 003600" src="https://github.com/user-attachments/assets/a7280837-c6d3-4ef8-9bd1-1262bc2ffaf5" />

3. Bar Chart: Yield Kg per Hectare vs. Region
   
•	Insight:

o	Central USA and East Africa are the top-performing regions in terms of yield (~400K Kg/Ha).

o	North India follows closely, while South India and South USA have comparatively lower yields (~360K Kg/Ha).

•	Interpretation: Central USA and East Africa might be benefiting from better agro-climatic conditions or more efficient practices. South India and South USA may require interventions to boost productivity.


<img width="1262" height="708" alt="Screenshot 2025-07-22 004058" src="https://github.com/user-attachments/assets/e43bee8f-43a8-4b65-9382-1d658c7d1bfd" />

4. Pie Chart: Yield Kg per Hectare vs. Irrigation Type
   
•	Insight:

o	The highest contribution to total yield comes from no irrigation (595.82K Kg/Ha or 29.5%), suggesting reliance on rainfall.

o	Drip (494.21K, 24.5%) and Manual (480.22K, 23%) follow closely.

o	Sprinkler accounts for the least share (446.16K, 22.1%).

•	Interpretation: Fields without irrigation still yield significantly, indicating rainfed farming can be productive. However, drip irrigation, with its high efficiency, is also contributing substantially, emphasizing the value of modern irrigation technologies.


<img width="1257" height="704" alt="Screenshot 2025-07-22 004348" src="https://github.com/user-attachments/assets/7a1a83e8-13f2-4154-b08e-638a23a25bde" />

5. Table Chart: Crop Type vs. Average Yield per Hectare
Crop Type	Average Yield (Kg/Ha)

Soybean	4,256.81

Wheat	4,077.58

Maize	3,982.55

Cotton	3,925.60

Rice	3,896.18

Total Avg	4,032.93

•	Insight:

o	Soybean has the highest average yield per hectare, followed by Wheat.

o	Rice consistently shows the lowest yield among the crops.

•	Interpretation: Crop selection plays a significant role in productivity. Soybean and wheat are high-performing and should be prioritized or studied further for replication in low-performing regions.


<img width="1257" height="702" alt="Screenshot 2025-07-22 004805" src="https://github.com/user-attachments/assets/fb91f1f5-1c18-4a66-9ee0-448ebd082e3e" />


*✅ Final Conclusion and Recommendations from Smart Farming Sensor Dashboard Analysis

🔍 Final Conclusion:
The analysis of the Smart Farming Sensor Dashboard reveals clear patterns in crop performance, regional productivity, irrigation effectiveness, and growth dynamics:

1.	Yield Performance peaks in June, indicating this month offers optimal harvesting conditions.
   
3.	Soybean and Wheat consistently outperform other crops in terms of average yield per hectare, while Rice yields the lowest.
   
5.	Regions like Central USA and East Africa achieve the highest productivity, potentially due to better practices or environmental conditions.
   
7.	Despite expectations, the highest yield was observed in non-irrigated areas, suggesting high reliance on rainfall or efficient water use in those zones.
   
9.	Longer crop growth durations (e.g., for Soybean and Wheat) correlate with higher yields, implying that patience and planning can lead to better productivity outcomes.


*✅ Strategic Recommendations:

1.	🌱 Promote High-Yield Crops (Soybean & Wheat):
Encourage farmers to adopt Soybean and Wheat, especially in regions with suitable conditions, as they consistently deliver better yields.

2.	📍 Target Low-Performing Regions:
Focus extension services, research, and technology support on South USA and South India to understand their constraints and enhance productivity.

3.	💧 Optimize Irrigation Practices:
Even though non-irrigated zones yield more, drip irrigation shows strong performance and should be expanded, especially in drought-prone or water-scarce areas.

4.	📆 Adjust Planting Schedules:
Encourage planting schedules that align with the peak yield month (June). Timely planting ensures crops reach maturity when environmental conditions are most favorable.

5.	📊 Leverage Sensor and NDVI Data:
Use NDVI (Normalized Difference Vegetation Index) and sensor analytics (average NDVI = 0.60) to guide real-time decisions on fertilizer use, irrigation, and pest control.

6.	🔁 Invest in Data-Driven Farming:
Continue to use smart dashboards and data collection to track growth durations, yield, and input use. This will improve precision farming practices over time.




