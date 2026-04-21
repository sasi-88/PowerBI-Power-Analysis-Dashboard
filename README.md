# PowerBI-Power-Analysis-Dashboard
Interactive Power BI dashboard analyzing  global Energy Trends Among both the Renewable and Non - Renewable energies
# Global Energy Transition & Capacity Growth Dashboard (Power BI)

##  Project Overview

This project presents an interactive **Power BI dashboard** analyzing global energy trends with a focus on **renewable energy transition, fossil fuel dependency, and regional performance**.

The goal is to transform raw energy data into meaningful insights that highlight how different countries and regions are progressing toward sustainable energy targets.

---

##  Data Source

The dataset used in this project was collected from:

 **Ember – Global Energy Think Tank**
Ember provides open-access data on electricity generation, emissions, and renewable energy trends across countries.

###  Data Includes:

* Electricity generation by fuel type
* Renewable energy share (%)
* CO₂ intensity
* Country-level metrics
* Socio-economic indicators (HDI, GDP per capita, Life expectancy)

---

##  Data Preparation

The dataset was processed and transformed before visualization:

* Cleaned missing and inconsistent values
* Standardized column formats
* Converted date fields into usable formats
* Created calculated columns for:

  * Year, Month, Decade
  * Fuel group classification (Renewable / Fossil / Mixed)

---

##  Data Modeling

A **star schema model** was implemented for efficient analysis:

### Fact Table:

* Energy metrics (generation, capacity, emissions)

### Dimension Tables:

* Geography (Country, Continent, Region)
* Date (Year, Decade, Time attributes)
* Fuel Type (Renewable, Fossil, Mixed)

This structure improves:

* Query performance
* Scalability
* Analytical clarity

---

##  DAX Measures Created

Several calculated measures were used:

* Total Capacity (GW)
* Renewable Capacity
* Fossil Capacity
* Renewable Share (%)
* Gap Analysis (Actual vs Target)
* Countries Above Target

These measures enabled deeper analytical insights across visuals.

---

##  Dashboard Pages

###  Global Overview

* Key KPIs (Capacity, Renewable Share, CO₂ Intensity)
* World map visualization
* Overall energy trends

---

### Energy Transition

* Renewable vs Fossil growth over time
* Decade-wise energy breakdown
* HDI vs Renewable Share analysis

---

### Country Deep Dive

* Country-level analysis
* Productive comparisons across metrics
* Detailed tables and drill-down capability

---

### Target vs Actual Analysis

* Renewable share vs target comparison
* Gap analysis (Above/Below target)
* Country performance evaluation

---


## Key Insights

* Renewable energy is steadily increasing globally, but fossil fuels still dominate overall capacity
* A small number of countries contribute the majority of global energy production
* Developed countries generally show higher renewable adoption rates
* Significant gaps exist between actual renewable share and targets in many regions
* Energy transition progress is uneven across continents

---

## Features of the Dashboard

* Interactive slicers (Year, Continent, Fuel Type)
* Drill-down and drill-through capabilities
* Conditional formatting for performance analysis
* Tooltip-based detailed insights
* Clean and structured layout for easy interpretation

---

## Tools & Technologies Used

* **Power BI Desktop**
* **DAX (Data Analysis Expressions)**
* **Data Modeling (Star Schema)**
* **Excel (Data preprocessing)**

---

##  Dashboard Preview

*(Add your screenshots in the repository and link them here)*

---

##  How to Use

1. Download the `.pbix` file from this repository
2. Open using Power BI Desktop
3. Use slicers to filter data
4. Explore different pages for insights

---

## Conclusion

This project demonstrates how raw energy data can be transformed into a **structured, interactive, and insight-driven dashboard**. It highlights both the progress and challenges in the global transition toward renewable energy.

---

## 🔗 Author

M Sasidhar
Power BI & Data Analytics Enthusiast
