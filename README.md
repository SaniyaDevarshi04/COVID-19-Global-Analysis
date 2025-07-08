# COVID-19-Global-Analysis
Tracking the pandemic: A global COVID-19 data across countries with real-time analytics in Power BI.

# **Project Overview**

An interactive data-driven dashboard showcasing the global impact of COVID-19 through compelling visuals, insightful metrics, and continent-wise breakdowns.

# **Data Source** 🌐

- Website:  https://www.worldometers.info/coronavirus/

- Import Method: Web connector from HTML tables

- Columns Extracted:

  `Country`, `TotalCases`, `TotalDeaths`, `TotalRecovered`, `Population`,
   `Continent`, `Cases per 1M`, `Deaths per 1M`

# **🎯 Objective** 

To visually analyze global COVID-19 trends—tracking cases, recoveries, and deaths—while comparing regions, continent-wise spread, and per million case density.

# **📊 Dashboard Highlights**

✅ Key Metrics: Total Cases, Recoveries, Deaths, Population, and Cases per Million

🗺️ Map: Bubble sizes show country-wise case intensity

📈 Bar Chart: Compare cases, recoveries, and deaths side by side

🍩 Donut Chart: View case distribution across continents

📋 Data Table: Country-wise breakdown with key metrics

🎛️ Filters: Interactive slicers for continent and country view


# **Insights Delivered**

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

# **🧠 DAX (Callculated Measure)**

- Case Fatality Rate (CFR) = `(Total Deaths / Total Cases) * 100`

# **💾 Project Files**

dashboard file:


# **🚀 Future Scope**

- Add time-series trends and vaccination data

- Integrate forecast models for future case predictions

- Create country-level drill-through pages

- Publish dashboard for real-time public access.

  
# **👩‍💻 Developed By**

Saniya D.
