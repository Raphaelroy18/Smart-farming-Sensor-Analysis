# Smart farming sensor Analysis
*OVERVIEW

This report summarizes a dataset containing 500 rows of sensor and farming data related to crop yield prediction for the year 2024. The data includes information on various farms, identified by farm Id, across different regions such as 'Central USA', 'East Africa', 'North India', 'South India', and 'South USA'. Key features include the crop type (Cotton, Maize, Rice, Soybean, Wheat), soil moisture_%, soil_pH, temperature C, rainfall mm, humidity_%, sunlight hours, irrigation type, fertilizer type, and pesticide usage ml. Temporal aspects are captured through sowing date, harvest date, and timestamp, with total days representing the duration between sowing and harvest. The target variable is yield per hectare, representing crop yield. Location data is provided via latitude and longitude, and crop health is assessed using the NDVI_index and crop disease status.

Based on the first five sample data entries, we can observe variations in farming practices and environmental conditions across different regions. For example, 'North India' uses 'Organic' fertilizer and no irrigation for 'Wheat', while 'South USA' uses 'Inorganic' fertilizer and 'Sprinkler' irrigation for 'Soybean'. The average soil moisture_% is 26.75, with a standard deviation of 10.14, indicating variability in soil moisture levels. The mean soil pH is 6.52, suggesting slightly acidic to neutral soil conditions. The average yield kg per hectare is 4032.93, with a standard deviation of 1173.26, showing considerable yield variation. The NDVI index ranges from 0.30 to 0.90, with a mean of 0.60, reflecting varying levels of vegetation health. The crop disease status indicates the presence of mild to severe diseases in some farms.

*DATA SOURCE 

The data was gotten from kaggle[download here](https://www.kaggle.com/datasets/atharvasoundankar/smart-farming-sensor-data-for-yield-prediction?resource=download)

*TECHNOLOGIES USE FOR THIS PROJECT
Microsoft Excel (for data cleaning, basic statistics and insights)
Power BI (for DAX calculations, creating key performance indicators (KPIs)  power query and visualization).

*DASHBOARD
(<img width="1262" height="709" alt="Screenshot 2025-07-22 001307" src="https://github.com/user-attachments/assets/300066c1-3766-4aa6-99dc-e8d002de91f9" />

*RELEVANT ENQUIRIES FOR THE ANALYSIS

1. Line Chart: Yield Kg per Hectare vs. Harvest Date (Month)
•	Insight: Yield increases from April through June, peaking at nearly 728,039.50 Kg/Ha in June, then declines steadily in July and drops sharply in August.
•	Interpretation: This suggests that June is the most productive harvest month, likely due to optimal growing conditions. Post-June, environmental or agronomic factors may reduce crop productivity.


<img width="1267" height="701" alt="Screenshot 2025-07-22 003106" src="https://github.com/user-attachments/assets/b96036b3-081c-4004-927a-7fbb15bb5eb7" />


