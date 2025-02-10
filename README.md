# 🌪️ Most Expensive Climate and Weather Disasters in the USA (1982 - 2022)

## 📌 Project Overview
This project analyzes the **most expensive climate and weather disasters in the USA** from **1982 to 2022** by using **data visualization techniques** to present insights into the financial toll of these disasters. The study highlights **top-costing disasters, trends over time, and state-wise cost distributions** while addressing **poorly designed graphs** and transforming them into **clear, informative visualizations**.

### 🎯 Objectives:
- **Identify the most expensive disasters** in the USA over a **40-year period**.
- **Analyze trends** in disaster types such as hurricanes, wildfires, floods, and storms.
- **Improve data visualizations** by redesigning poor graphical representations.
- **Use R for data processing** and **Tableau for visual storytelling**.
- **Provide recommendations** based on financial loss patterns.

---

## 📂 Project Files
- **📄 Project Report:** `Mukesh Rajmohan_Project Report.pdf`
- **📜 R Script (Data Processing):** `DIsaster_1982_2022.R`
- **📊 Tableau Workbook (Final Visualizations):** `Disaster.twbx`

---

## 🗃️ Dataset Information
- **Source:** [NOAA - National Centers for Environmental Information (NCEI)](https://www.ncei.noaa.gov/access/billions/)
- **Time Range:** 1982 - 2022
- **Attributes:**
  - `Date`: Disaster occurrence date.
  - `Disaster Type`: Type of event (Hurricane, Wildfire, Flood, etc.).
  - `Cost (Millions USD)`: Economic impact adjusted for inflation.
  - `State`: Affected US state(s).
  - `Deaths`: Fatalities caused by the disaster.
  - `Year`: Extracted from date for trend analysis.

---

## 🔧 Project Workflow
### **1️⃣ Data Preprocessing & Cleaning (R)**
- **Performed in:** `DIsaster_1982_2022.R`
- **Key Steps:**
  - Load datasets for **event-wise and state-wise disaster costs**.
  - Convert and standardize **date formats**.
  - Extract **yearly trends** to analyze time-based patterns.
  - Convert cost metrics from **millions to billions** for better readability.
  - Identify **the most expensive disaster each year** and **top 15 highest-cost disasters overall**.
  - Pivot **state-wise data** to analyze which states incurred the highest disaster-related costs.
  - Save processed datasets for **Tableau visualization**.

### **2️⃣ Data Visualization (Tableau)**
- **Performed in:** `Disaster.twbx`
- **Key Visualizations:**
  - **Bar Chart:** Top **15 costliest disasters** in US history.
  - **Time Series Plot:** Yearly **disaster costs trends** from 1982-2022.
  - **Geospatial Map:** **State-wise disaster costs** distribution.
  - **Stacked Bar Chart:** **Disaster types & their financial impact over time**.
  - **Comparative Analysis:** Original vs. Redesigned visualization effectiveness.

### **3️⃣ Analysis & Insights**
- **Performed in:** `Mukesh Rajmohan_Project Report.pdf`
- **Key Takeaways:**
  - Original graph **failed to present data clearly**, lacked proper labeling, and was **cluttered**.
  - **Redesigned graph** highlights only the **most relevant data points**, with better color coding and simplified structure.
  - **Hurricanes & tropical storms account for most high-cost disasters**, with **Hurricane Katrina (2005)** and **Hurricane Harvey (2017)** among the worst.
  - **2017 was the most financially devastating year**, with multiple disasters causing **record-breaking losses**.
  - **Southern and coastal states** are the most affected regions, with **Texas, Florida, and Louisiana** consistently facing severe economic losses.

---

## 📈 Key Findings
### 🏆 Most Expensive Disasters (1982-2022)
| Rank | Disaster Event | Year | Cost (Billion USD) |
|------|--------------|------|------------------|
| 1️⃣  | Hurricane Katrina | 2005 | $193.8B |
| 2️⃣  | Hurricane Harvey | 2017 | $151.0B |
| 3️⃣  | Hurricane Maria | 2017 | $107.1B |
| 4️⃣  | Hurricane Sandy | 2012 | $83.1B |
| 5️⃣  | Hurricane Ida | 2021 | $78.5B |

### 🌎 State-wise Impact
- **Texas, Florida, and Louisiana** have consistently experienced the **highest disaster costs**.
- **Wildfires impact Western states** (California, Oregon, Colorado) more severely.
- **Floods and hurricanes dominate the Southeastern US**.

### 📉 Trends Over Time
- **Climate change is driving more frequent and intense disasters**.
- **Financial losses have increased significantly** in the last two decades.
- **Hurricanes remain the dominant contributors** to billion-dollar disasters.

---

## 🚀 Future Enhancements
- **Machine Learning for Disaster Prediction:** Use AI to **forecast economic damage** based on climate patterns.
- **Interactive Dashboards:** Deploy **real-time Tableau dashboards** for disaster tracking.
- **Expanded Data Sources:** Integrate **FEMA & Insurance Loss Data** for a **holistic financial impact analysis**.

---

## 📚 References
1. **NOAA - Billion Dollar Weather and Climate Disasters**: [NCEI NOAA Data](https://www.ncei.noaa.gov/access/billions/)
2. **Tableau for Data Visualization**: [Tableau Public](https://public.tableau.com/)
3. **R for Data Cleaning & Manipulation**: [tidyverse](https://www.tidyverse.org/)
4. **Disaster Impact Analysis**: [HowMuch.net](https://howmuch.net/articles/most-expensive-naturals-disasters-in-usa)

---

## ⚙️ How to Run the Code
### **1️⃣ Prerequisites**
- **R & RStudio**
- **Tableau Desktop (or Tableau Public)**
- Required R Libraries:
  ```r
  install.packages("tidyverse")
  install.packages("lubridate")

---


### ✅ Key Features:
- **Complete project documentation** covering **data sources, methodology, and results**.
- **Step-by-step execution guide** for running the project in **R and Tableau**.
- **Financial impact analysis** of disasters over **four decades**.
- **Clear visualizations & future enhancement plans**.

Let me know if you need any modifications! 🚀
