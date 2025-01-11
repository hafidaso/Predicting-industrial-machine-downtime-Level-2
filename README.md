# Industrial Machine Downtime Prediction Analysis

## 📋 Overview
This project analyzes operational data from high-precision metal component manufacturing machines to predict and prevent downtime. The analysis aims to support proactive maintenance planning through data-driven insights.

## 🎯 Objectives
- Analyze operational data to identify patterns leading to machine downtime
- Develop data-driven insights for proactive maintenance
- Reduce unplanned machine failures
- Optimize maintenance scheduling

## 💾 Dataset
The dataset (`machine_downtime.csv`) contains operational metrics including:
- Date readings
- Machine identifiers
- Assembly line information
- Pressure measurements
- Temperature readings
- Vibration and speed metrics
- Voltage and torque data
- Cutting force measurements
- Downtime indicators

## 🛠️ Technical Stack
- Python
- Pandas
- Matplotlib
- Seaborn

## 📊 Analysis Components
1. **Data Preparation & Cleaning**
   - Date parsing
   - Missing value handling
   - Column standardization

2. **Exploratory Data Analysis (EDA)**
   - Correlation analysis
   - Temporal downtime patterns
   - Machine-specific analysis
   - Assembly line performance
   - Operational metrics vs. downtime

3. **Key Findings**
   - Hydraulic pressure correlation (-0.56)
   - Torque impact (-0.41)
   - Cutting force relationship (0.45)
   - Spindle speed influence (0.28)

## 📈 Visualizations
- Correlation heatmaps
- Monthly downtime trends
- Machine-specific downtime analysis
- Assembly line performance comparisons
- Operational metrics boxplots

## 💡 Recommendations
1. Implement real-time hydraulic pressure monitoring
2. Regular torque system maintenance
3. Vibration analysis integration
4. Optimize cutting force and spindle speed
5. Enhance voltage stability
6. Deploy predictive maintenance models

## 📝 Usage
1. Clone the repository:
```bash
git clone https://github.com/hafidaso/Predicting-industrial-machine-downtime-Level-2/tree/main


