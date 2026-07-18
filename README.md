🚴‍♂️ Bike Station Performance Dashboard

📌 Project Overview

This Power BI project analyzes bike station availability, capacity, banking status, and operational performance across multiple cities. The goal is to transform raw station‑level data into meaningful insights that help stakeholders monitor station health, bike availability, and infrastructure utilization.

🎯 Objective
Analyze bike availability and station capacity.

Measure open vs closed station distribution.

Evaluate bike stand utilization across contract locations.

Identify performance gaps in cities with low availability.

Build an interactive Power BI dashboard for operational decision‑making.

📂 Dataset
Source: JCDecaux Bike Station Data
Domain: Transportation / Smart Mobility Analytics
Data Includes:

Station Status (Open / Closed)

Available Bikes

Bike Stands

Banking Status

Contract Name (City)

Bonus Status

🛠 Tools & Technologies
Microsoft Excel

Power Query

Power BI

DAX

🧹 Data Preprocessing
Removed duplicate station records.

Standardized numeric fields (bike count, stand count).

Converted station status into categorical values.

Cleaned contract names and unified text formats.

Built relationships between station attributes.

Loaded cleaned data into Power BI for modeling.

📊 Data Model
Fact Table: Bike Station Metrics
Dimension Tables: Contract, Status, Banking, Bonus

Relationships:

Contract → Stations (1:*)

Status → Stations (1:*)

Banking → Stations (1:*)

Cross‑filter direction: Single

📈 DAX Measures
Total Bikes

Total Bike Stands

Total Available Bikes

% Availability

% Closed Stations

Banking True/False Count

Bonus Station Count

📊 Dashboard Features
KPI Cards
Total Stations

Total Bikes

Total Bike Stands

% Open vs Closed Stations

Banking Status Distribution

Visualizations
Available Bikes by Contract Name

Total Bike Stands by Status

Station Status Breakdown

Banking True/False Comparison

Bonus vs Non‑Bonus Station Distribution

City‑wise Bike Stand Average

Interactive Features
Drill Down

Cross Filtering

Slicers (Contract, Status, Banking)

Tooltips

📈 Key Insights
(From your attached document — quoting two lines as required)

“Total station 753”
“Status: OPEN 1K (16.44%), CLOSED 6K (83.56%)”

Majority of stations are closed, indicating operational issues.

Marseille, Lyon, Toulouse, Brussels, and Cergy‑Pontoise show 0 availability, requiring immediate attention.

Banking-enabled stations represent 83%, showing strong infrastructure support.

Average bike stands vary significantly — cities like Namur, Creteil, Amiens have higher stand availability.

Bonus stations form a small portion (~16%), but contribute to better bike distribution.

💡 Recommendations
Prioritize reopening stations in major cities with zero availability.

Increase bike redistribution in low‑availability zones.

Improve maintenance cycles for closed stations.

Expand bonus station program to improve bike circulation.

Monitor banking-enabled stations for performance consistency.

📁 Project Structure
Bike‑Station‑Performance‑Dashboard
│
├── Dashboard Images
│   └── BikeStationDashboard.png
│
├── Power BI
│   └── BikeStation.pbix
│
├── Dataset
│   └── JCDecaux_Bike_Stations.csv
│
└── README.md

🎯 Conclusion
This project demonstrates how Power BI can convert raw bike station data into actionable operational insights. The dashboard helps city planners and mobility teams monitor station performance, bike availability, and infrastructure utilization, enabling smarter decision‑making for urban transportation systems.
