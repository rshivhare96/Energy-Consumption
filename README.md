# Energy Consumption Analysis Report: Methodology and Findings

In this analysis, we explored the consumption patterns of various energy types, focusing on both conventional and renewable sources. The primary objective was to understand the evolution of energy consumption over time and identify the sectors contributing the most to this consumption. Below is a step-by-step explanation of what we did in the code and the insights generated.

---

## Loading and Preprocessing the Dataset

### What We Did:
- We imported the necessary libraries, including Pandas for data manipulation, Plotly for visualization, and others to support the analysis.
- We loaded a CSV file containing energy consumption data for various sectors and energy types from 1973 to 2023.

### Output:
- The dataset was successfully loaded, and initial exploration showed the available columns like "Year", "Sector", and multiple renewable energy types.

---

## Data Cleaning

### What We Did:
- To handle any potential missing or null values in the dataset, we checked and filled the missing data to ensure no gaps in our analysis.
  
### Output:
- The dataset was fully cleaned, allowing for smooth analysis without missing data errors.

---

## Yearly Consumption Trends Visualization

### What We Did:
- We created a visualization to examine the yearly consumption trends for renewable energy types, including hydroelectric power, geothermal energy, solar energy, wind energy, and others. Using Plotly, we plotted interactive line charts to show how the consumption of these energy types evolved from 1973 to 2023.

### Output:
- **Hydroelectric Power**: The highest consumption was in 1994. It remained stable from 1973 to 1993, then declined after 1994, with a small rise in 2013.
- **Geothermal Energy**: Steadily increased from 1973 to 2011, staying stable since then.
- **Solar Energy**: Usage began in 1989, and after remaining constant till 2012, it rapidly grew every year until 2023.
- **Wind Energy**: Usage started in 1989, remained constant until 1999, then increased significantly until 2022, with a slight drop in 2023.
- **Waste Energy**: In use since 1973, it saw growth until peaking in 1996, then fluctuated mildly each year.
- **Fuel Ethanol**: Grew steadily from 1981 till 2010, with consumption remaining constant afterward.
- **Biomass Losses**: Introduced in 1981, its usage grew significantly until 2006, then rose rapidly until 2010, with minor fluctuations since.
- **Renewable Diesel Fuel**: Introduced in 2011, it grew sharply in 2013 and continued to rise until 2023.
- **Other Bio-Fuel**: In use since 2014, it grew steadily till 2020, then rapidly increased every year until 2023.
- **Conventional Hydroelectric Power**: In use since 1973, it saw peaks in 1984 and 1997, with minor fluctuations year by year.
- **Biodiesel**: Introduced in 2001, its usage saw rapid growth from 2005 to 2007, then fluctuated until peaking in 2016, with a slight increase again in 2023.

---

## Comparing Renewable and Conventional Energy Usage

### What We Did:
- We visualized the proportion of renewable energy in comparison to conventional energy. Using a line chart, we compared the trends of wind, solar, and conventional energy consumption over the years.

### Output:
- **Conventional Energy** has been in use since 1973, while wind and solar energy started being used in 1989. Wind energy surpassed conventional energy in 2018 and continued increasing. Solar energy consumption overtook conventional energy in 2022. Wind energy has consistently been higher than conventional energy usage since 2019, and in comparison to solar, wind energy has been used more.

---

## Top Sectors Consuming Renewable Energy

### What We Did:
- We analyzed which sectors (Electric Power, Residential, Commercial, Industrial, Transportation) consume the most energy for each renewable energy type. For each energy type, we grouped the data by sector and created bar charts to visualize the top sectors for each energy type.

### Output:
- **Hydroelectric Power**: Top sectors are Industrial (506.594) and Commercial (13.336).
- **Geothermal Energy**: Electric Power (2,127.281), Residential (795.357), Commercial (448.977), Industrial (131.861), Transportation (0).
- **Solar Energy**: Electric Power (2,837.874), Residential (2,732.439), Commercial (442.051), Industrial (110.778), Transportation (0).
- **Wind Energy**: Electric Power (12,995.34), Commercial (5.766), Industrial (5.124).
- **Waste Energy**: Electric Power (8,859.278), Commercial (1,438.234), Industrial (7,506.891).
- **Fuel Ethanol**: Commercial (277.168), Industrial (337.502), Transportation (20,678.68).
- **Biomass Losses**: Industrial (14,750.63).
- **Renewable Diesel**: Transportation (1,283.948).
- **Other Bio-Fuel**: Transportation (93.879).
- **Conventional Hydroelectric Power**: Electric Power (48,224.27).
- **Biodiesel**: Transportation (2,903.285).

---

## Total Energy Consumption by Sector

### What We Did:
- We calculated the total energy consumption across all sectors, summing up the consumption of all energy types for each sector to understand which sectors are the largest consumers of energy overall.

### Output:
- **Electric Power**: The largest consumer of energy, accounting for 57.9% of total consumption (74,938.714).
- **Transportation**: The second-largest, with 19.3% (24,959.796).
- **Industrial**: 18% of total consumption (23,349.383).
- **Residential**: 2.81% (3,633.231).
- **Commercial**: 2.03% (2,625.532).

---

## Concluding Remarks

Through this detailed analysis, we have identified the energy consumption trends for different renewable energy types and their adoption by various sectors. The data shows a rapid rise in the use of wind and solar energy, with wind surpassing conventional energy in 2018 and solar in 2022. Electric power generation remains the dominant consumer of most energy types, particularly renewable ones. This analysis provides critical insights for energy policy and sustainability efforts aimed at reducing reliance on conventional energy sources and promoting renewable energy adoption across industries.
