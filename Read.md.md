# 🚗 EV Vehicle Performance Analysis Dashboard

## 📌 Project Overview
The EV Vehicle Performance Analysis Dashboard is a data analytics project developed using **Python, MySQL, and Power BI**.

The project focuses on analyzing Electric Vehicle (EV) performance data such as:
- Battery Capacity
- Distance Traveled
- Energy Usage
- Vehicle Efficiency
- Charging Analysis
- Location-wise Performance

The main objective of this project is to transform raw EV data into meaningful insights using data preprocessing, SQL analysis, and interactive visualizations.

---

# 🛠 Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data preprocessing and analysis |
| Pandas | Data cleaning and manipulation |
| MySQL | Database storage and SQL queries |
| Power BI | Dashboard and visualization |
| DAX | KPI calculations |
| CSV Dataset | Data source |

---

# 🚀 Features

✅ KPI Cards  
- Total Vehicles  
- Average Distance  
- Average Efficiency  
- Average Battery Capacity  

✅ EV Model Analysis  
- Compare vehicle models using charts and KPIs

✅ Scatter Plot Analysis  
- Analyze relationship between battery capacity and distance

✅ Location Analysis  
- Compare EV performance across locations

✅ Interactive Dashboard  
- Dynamic filtering using slicers

---

# 📊 Dashboard Components

- Clustered Column Chart
- Scatter Plot
- Bar Chart
- KPI Cards
- Map Visualization
- Slicers (Filters)

---

# 🐍 Python Analysis

Python was used for:
- Loading CSV data
- Data cleaning
- Handling missing values
- Efficiency calculation
- Exporting processed data

## Example Code

```python
import pandas as pd

df = pd.read_csv("ev_data_500.csv")

df['efficiency'] = df['distance'] / df['energy_used']

df.to_csv("ev_final.csv", index=False)
```

---

# 🗄 MySQL Analysis

MySQL was used for:
- Storing EV data
- Running SQL queries
- Data analysis

## Example Query

```sql
SELECT AVG(battery_capacity) 
FROM ev_data;
```

---

# 📈 Power BI Dashboard

Power BI was used to create:
- KPI cards
- EV model comparison charts
- Scatter plots
- Location-based analysis
- Interactive dashboard filters

The dashboard provides insights into:
- Top-performing EV models
- Efficiency trends
- Distance analysis
- Battery performance

---

# ⚙️ How to Run the Project

## Step 1
Install:
- Python
- MySQL
- Power BI Desktop

## Step 2
Load the EV dataset into Python or MySQL.

## Step 3
Run the Python preprocessing code.

## Step 4
Export the processed dataset:

```python
df.to_csv("ev_final.csv", index=False)
```

## Step 5
Import the cleaned dataset into Power BI.

## Step 6
Create visualizations and KPI dashboards.

---

# 🎯 Project Outcome

The project successfully:
- Analyzed EV performance data
- Built interactive dashboards
- Generated meaningful business insights
- Improved understanding of data analytics and visualization

---

# 📚 Learning Outcomes

- Data preprocessing using Python
- SQL database operations
- Dashboard creation in Power BI
- KPI analysis and visualization
- Interactive reporting techniques

---

# 👨‍💻 Author

**Nagaraj**

Skills Used:
- Python
- SQL
- Power BI
- Pandas
- Data Visualization
