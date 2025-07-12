# COVID-19-Global-Analysis
Tracking the pandemic: A global COVID-19 data across countries with real-time analytics in Power BI.

# **📝 Project Overview**

An interactive data-driven dashboard showcasing the global impact of COVID-19 through compelling visuals, insightful metrics, and continent-wise breakdowns.

# **Data Source** 🌐

- Website:  Worldometers-COVID-19 Data
  
- Import Method: Web connector from HTML tables

- Columns Extracted:

  `Country`, `TotalCases`, `TotalDeaths`, `TotalRecovered`, `Population`,
   `Continent`, `Cases per 1M`, `Deaths per 1M`

# **🎯 Objective** 

To visually analyze global COVID-19 trends—tracking cases, recoveries, and deaths—while comparing regions, continent-wise spread, and per million case density.

# **📊 Dashboard Highlights**

✅ Key Metrics: Total Cases, Deaths,Active Cases, Recoveries, Population and Cases per Million

🗺️ Map: Bubble sizes show country-wise case intensity

📈 Bar Chart: Compares countries with the highest number of active cases 

🕸️ Radar Chart: Shows comparison of Recovery %, Death %, and Cases per Million

📊 Clustered Column Chart: visualizes country-wise contribution to global totals

🍩 Donut Chart: View case distribution across continents

📋 Data Table: Country-wise breakdown with key metrics

🎛️ Filters: Interactive slicers for continent and country view


# **🗒️ Insights Delivered**

- Europe leads in total cases, followed by Asia and North America.

- Most countries show high recovery rates with relatively low fatalities.

- CFR differs across continents, reflecting healthcare response gaps.

- Europe and Asia together contribute the majority of global cases.

- Cases per million highlight countries with intense outbreak density.

- Map bubbles and interactive filters make hotspot tracking intuitive.

# **🛠 Tools & Techniques Used**

| Tool/Feature            | Purpose                                                |
| ----------------------- | ------------------------------------------------------ |
| Power BI Desktop        | interactive dashboard                                  |
| Power Query Editor      | Data cleaning and transformation                       |
| DAX                     | Metric like  *Case Fatality Rate*                      |
| Bing Maps               | Mapping country-wise spread                            |
| Conditional Formatting  | Enhanced readability in data tables                    |

# **🧠 DAX Summary**

- Case Fatality Rate (CFR) = `(Total Deaths ÷ Total Cases) * 100`

   ➤ Evaluates disease lethality level

- ActiveCases: `TotalCases − TotalRecovered − TotalDeaths`
  
   ➤ Shows currently infected cases

- DeathRate: `TotalDeaths ÷ TotalCases`
  
   ➤ Indicates fatality proportion

- NetActiveCases: `TotalCases − TotalRecovered − TotalDeaths`
  
  ➤ Tracks ongoing active infections

- RecoveryRate: `TotalRecovered ÷ TotalCases`

  ➤ Measures recovery success rate

- Severity Status: `Categorizes Net Active Cases as Critical, Moderate, or Normal using DAX SWITCH logic`
 
  ➤ Classifies severity based on active case thresholds.

# **🖼️ Dashboard Snapshot :**



<img width="1469" height="802" alt="Dashboard Overview" src="https://github.com/user-attachments/assets/2e68641c-1ff4-4f88-994a-1cc0ef628322" />




# **🚀 Future Scope**

- Add time-series trends and vaccination data

- Integrate forecast models for future case predictions

- Create country-level drill-through pages

- Publish dashboard for real-time public access.

  
# **👩‍💻 Developed By**

Saniya Devarshi

🎓 BCA (Data Science) | 2023–2026

📍 Sri Balaji University, Pune
