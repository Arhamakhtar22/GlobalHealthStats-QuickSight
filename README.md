# GlobalHealthStats-QuickSight
This visualization is based on the Global Health Statistics dataset i got from Kaggle. This dataset provides insights statistics on global health, focusing on various diseases, treatments, and outcomes. The data spans multiple countries and years.
In this project, I focus on just five diseases (COVID-19, Cancer, Diabetes, Alzheimer's and HIV/AIDS) with four different types of visualizations.

Link to the dataset:  https://www.kaggle.com/datasets/malaiarasugraj/global-health-statistics

<img width="995" alt="Screenshot 2024-12-06 at 8 25 24 PM" src="https://github.com/user-attachments/assets/68415175-5173-405b-8aca-d96ff2650d45">



1) Time Series Line Chart
 <img width="563" alt="Screenshot 2024-12-06 at 7 54 59 PM" src="https://github.com/user-attachments/assets/9a9fac03-cd5a-4281-8fd0-60e6a347e8fc">

 In this chart we can answer how the mortality rates have changed over several years for each disease. If you hover the cursor on each line, it provides you with the rate.
 This chart can be created by using:
 - "Year" to the X-axis
 - Mortality Rate to the Value field
 - Adding Disease Name as a color

2) Stacked Bar Chart for Age and Gender Analysis
  <img width="707" alt="Screenshot 2024-12-06 at 8 00 21 PM" src="https://github.com/user-attachments/assets/e8a91b1e-263a-44df-a983-e2b056994290">
  In this chart we can see how do diseases affect different age groups and genders. You can filter by Disease Name or Year
  This chart can be created by using:
  - "Age Group" to the X-axis
  - "Gender" to the Color field
  - "Population Affected" as the Value field

3) Box Plot for Treatment Cost by Disease
   <img width="570" alt="Screenshot 2024-12-06 at 8 04 19 PM" src="https://github.com/user-attachments/assets/d4069f9c-9fb3-4a3a-87d1-e9ff4f864870">
   
In this chart we can find how does the cost of treating different diseases vary across countries. It can identify outliers or countries with exceptionally high treatment costs
This chart can be created by using:
     - "Disease Name" to the Category field
     - "Avg Treatment Cost" for the Value field

4) Point Map
  <img width="685" alt="Screenshot 2024-12-06 at 8 08 09 PM" src="https://github.com/user-attachments/assets/a5301593-0cc4-4178-999a-d7e85a1fd7f4">
  This chart can be created by using:
  - "Country" in the Geospatial field
  - "Population Affected" for Size
    
