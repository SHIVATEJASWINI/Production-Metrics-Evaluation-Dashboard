# 📊 Production Metrics Evaluation Dashboard

This Power BI dashboard provides a comprehensive analysis of manufacturing production metrics. It helps stakeholders monitor output performance, track machine efficiency, manage downtime, and optimize shift operations across departments.

## 🏭 Objective

To evaluate and monitor real-time-like production data across multiple machines, shifts, and departments to improve operational efficiency and production quality.

Key goals include:

- Identifying underperforming machines or shifts  
- Tracking production targets vs. actual output  
- Analyzing downtime trends and maintenance types  
- Monitoring cost impacts and production quality  

## 📈 Key Dashboard Features

| Feature | Description |
|--------|-------------|
| ✅ Total Output & Output Per Shift | Visual cards displaying total and average output across shifts |
| ⚙️ Machine Efficiency | Bar and bubble charts tracking average machine efficiency by department |
| 🧭 Downtime Analysis | Visual breakdown of downtime minutes across machines and shifts |
| 🧰 Maintenance Type vs Status | Machine status comparison across maintenance types (Corrective, Preventive, Emergency) |
| 💸 Repair Cost Trends | Line chart showing cost fluctuations relative to downtime |
| 🏷️ Product Quality Distribution | Bar chart of department count by product quality (High, Medium, Low) |
| 📦 Departmental Summary | Pie and stacked bar charts showing production trends across departments |
| 🎯 Target Achievement | Gauge chart showing overall production target fulfillment |
| 🌡️ Temperature vs Efficiency | Scatter plot of machine temperature versus efficiency percentage |
| 📊 Shift-Based Downtime | Bar chart comparing average downtime across Morning, Afternoon, and Night shifts |

## 🧾 Data Fields

The dataset includes detailed operational metrics:

- timestamp  
- machine_id  
- department  
- shift  
- output_units  
- production_target  
- machine_status  
- downtime_minutes  
- efficiency_percentage  
- defects_reported  
- repair_cost  
- maintenance_type  
- product_quality  
- operator_id  
- shift_duration  
- machine_temperature  
- cost_impact  
- production_target_achievement  

These fields allow users to slice and analyze performance by department, machine, shift, and production quality.

## 🛠 Built With

- Power BI Desktop  
- DAX measures & calculated columns  
- Visual interactions and slicers for flexible analysis  

## 📂 Repository Contents

| File | Description |
|------|-------------|
| Production_Metrics_Dashboard.pbix | Power BI dashboard file |
| README.md | Project documentation |

## 🚀 How to Use

1. Clone or download this repository.  
2. Open `Production_Metrics_Dashboard.pbix` in Power BI Desktop.  
3. Interact with the visuals using slicers (e.g., by shift, department, machine).  
4. Customize the dashboard as per your operational context.

## 🤝 Contribution

If you'd like to suggest improvements or extend the analysis, feel free to fork the repository or raise an issue.
