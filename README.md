## 📊 Power Distribution and Feeder Performance Analysis — Nigeria (2024)

### 🔍 Project Overview

This project presents a data-driven analysis of an electrical power distribution network, focusing on feeder-level performance, system efficiency, and load behavior across various discos in Nigeria (2024).

Using industrial-style electrical data (similar to PLC/SCADA outputs), the project simulates how engineers can monitor and evaluate system performance using modern data analytics tools.

### ⚙️ Tools & Technologies

* Python (Data Analysis)
* Power BI (Dashboard & Visualization)
* Pandas, NumPy, Matplotlib
* Parquet & CSV Data Formats

### 🧠 Workflow

The project follows a structured data pipeline:
1. Data Acquisition
   * Dataset obtained in Parquet format
   * Converted to CSV for analysis using python pyarrow
2. Data Analysis (Python)
   * Performed exploratory data analysis using `pandas`
   * Generated statistical summaries (`df.describe()`)
   * Evaluated relationships between key variables (e.g., power vs power factor)
   * Visualized trends using matplotlib
3. Data Visualization (Power BI)
   * Designed an interactive dashboard
   * Created KPIs for system performance
   * Built trend analysis (hourly, monthly, daily)
   * Implemented system health indicators (voltage, current, power factor)
   * Conducted feeder-level performance comparison

### ⚡ Key Metrics Analyzed
* Active Power (kW)
* Peak Active Power (kW)
* Voltage (V)
* Current (A)
* Power Factor (PF)

### 📈 Key Questions Answered
This dashboard was designed to answer critical engineering questions:
* What is the overall system performance?
* When does peak load occur?
* Is the system operating efficiently?
* Which feeders contribute the most load?
* Which feeders are inefficient or critical?
* How stable is voltage and current across the network?

### 🔥 Key Insights
* Peak load occurs during evening hours, indicating demand concentration
* Power factor averages around 0.90, showing moderate efficiency
* Certain feeders consistently contribute higher load demand
* Efficiency tends to reduce slightly as load increases
* Variability in load suggests fluctuating operational conditions

### 📊 Dashboard Features
* KPI summary (power, current, voltage, efficiency)
* Time-based analysis (hourly, daily, monthly)
* System health monitoring (PF, voltage, current status)
* Feeder performance comparison
* Interactive filtering (location, sector, time)

### 🚀 Conclusion
This project demonstrates how electrical engineering principles can be combined with data analytics tools to simulate a modern power system monitoring and analysis workflow.
