
# Fleet Operations Analytics

## 📌 Project Overview
This project analyzes fleet operations for a humanitarian logistics organization. It combines **Python data analysis** and a **Tableau dashboard** to monitor truck performance, fuel consumption, driver efficiency, and maintenance needs.

**Objectives:**
- Track fuel consumption per truck and driver.
- Monitor distance traveled and trips completed.
- Identify trucks that require maintenance.
- Evaluate driver performance against benchmarks (1.8 km/L fuel efficiency).

## 📂 Project Structure
```
Fleet_Operations_Analytics/
│
├─ Dashboard/
│   └─ Fleet_Operations_Dashboard.twbx
├─ Python/
│   └─ fleet_analysis.ipynb  (or .py)
├─ data/
│   └─ fleet_data.csv
└─ README.md
```

## 🛠️ Requirements
- Python 3.8+  
- Jupyter Notebook (optional for `.ipynb`)  
- Required Python packages:
```bash
pip install pandas matplotlib seaborn numpy
```
- Tableau Desktop or Tableau Public (for interactive dashboard)

## 🚀 How to Run

### **1. Python Analysis**
- Open `fleet_analysis.ipynb` in Jupyter Notebook or VS Code.
- Run all cells to process the dataset (`fleet_data.csv`) and generate analytics.
- Optional: export processed data to CSV for Tableau.

```bash
python fleet_analysis.py   # If using .py script
```

### **2. Tableau Dashboard**
- Open `Dashboard/Fleet_Operations_Dashboard.twbx` in Tableau Desktop or Tableau Public.
- Use filters to select specific trucks, drivers, or date ranges.
- Hover over charts to see tooltips with detailed metrics.

## 📊 Features
- Fuel Consumption per Truck and Driver
- Distance and Trips Overview
- Maintenance Alerts
- Interactive Filters and Tooltips
- Benchmark comparison for fuel efficiency


## 📫 Contact
For questions or collaboration, contact: **mutazoficial@gmail.com**
