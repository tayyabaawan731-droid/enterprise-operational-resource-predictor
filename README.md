# enterprise-operational-resource-predictor
Power BI dashboard for healthcare operational performance analysis, resource prediction, spatial mapping, time-intelligence insights, and automated alerts.
# Enterprise Operational Performance & Resource Predictor

## Overview

This project is a Power BI-based healthcare operational performance and resource prediction dashboard designed to monitor operational resources, performance, demand, and resource deficits.

The dashboard provides interactive analysis through KPI cards, Decomposition Tree, geographical mapping, time-intelligence DAX calculations, predictive analysis, automated alerts, slicers, and page navigation.

## Objectives

- Monitor operational resource availability and requirements
- Identify resource deficits across regions and departments
- Analyze healthcare facility performance
- Visualize geographical resource distribution
- Apply time-intelligence DAX calculations
- Analyze historical resource trends
- Estimate future resource demand
- Generate automated resource alerts
- Provide interactive filtering and analysis

## Dashboard Structure

### Executive Overview

The Executive Overview page provides a high-level summary of healthcare operational performance.

It includes:

- Total Available Resources
- Total Required Resources
- Total Resource Deficit
- Average Utilization
- Average Performance
- Current Resource Alert Status
- Resource Deficit Trend Over Time

### Resource Analysis

The Resource Analysis page provides detailed analysis of operational resource deficits.

It includes:

- Resource Deficit Analysis using a Decomposition Tree
- Resource Deficit by Department
- Resource Utilization by Department

The Decomposition Tree analyzes resource deficits through:

Region → Department → Resource Type → Facility

### Spatial Resource Analysis

The Spatial Resource Analysis page provides geographical analysis of healthcare resources.

It includes:

- Operational Resource Deficit by Location
- Resource Deficit by Region
- Performance by Facility

The map uses:

- Facility
- Region
- Latitude
- Longitude
- Resource Deficit

### Prediction & Automated Alerts

The Prediction & Automated Alerts page focuses on historical trends, predictive resource analysis, and operational alerts.

It includes:

- Previous Month Deficit
- Deficit Growth %
- 30-Day Moving Average
- Predicted Resource Demand
- Current Resource Alert
- Resource Demand Prediction & Moving Average
- Resource Alert Distribution

## DAX Measures

The project includes DAX measures for operational performance and predictive analysis.

### Operational Measures

- Total Available Resources
- Total Required Resources
- Total Resource Deficit
- Average Utilization
- Average Performance

### Time-Intelligence Measures

- Previous Month Deficit
- Deficit Growth %
- 30-Day Moving Average

### Predictive Measure

- Predicted Resource Demand

### Alert Measure

- Resource Alert

## Automated Alert Logic

The dashboard uses threshold-based logic to identify resource conditions.

- Critical: Resource deficit is above the defined threshold or utilization exceeds 90%
- Warning: Utilization is between 75% and 90%
- Healthy: Utilization is below 75%

These alerts help identify areas that may require operational attention.

## Interactive Features

The dashboard provides:

- Region slicer
- Department slicer
- Resource Type slicer
- Date slicer
- Synchronized slicers across pages
- Interactive Decomposition Tree
- Geographical mapping
- Page navigation
- Interactive KPI cards
- Time-based analysis

## Dataset

The project uses a simulated healthcare operational dataset containing:

- Date
- Facility
- Region
- Department
- Resource Type
- Available Resources
- Required Resources
- Patient Demand
- Utilization %
- Performance %
- Latitude
- Longitude
- Resource Deficit
- Alert Status

## Tools & Technologies

- Microsoft Power BI
- DAX
- Microsoft Excel
- Data Visualization
- Time-Series Analysis
- Spatial Mapping
- Predictive Analytics

## Project Structure

Enterprise-Operational-Resource-Predictor/

├── Enterprise_Operational_Resource_Predictor.pbix
├── Enterprise_Operational_Resource_Predictor.xlsx
└── README.md

## Key Features

- Multi-page Power BI dashboard
- Healthcare operational performance monitoring
- Resource deficit analysis
- Decomposition Tree analysis
- Spatial mapping using Latitude and Longitude
- Time-intelligence DAX calculations
- 30-day moving average
- Resource demand prediction
- Automated resource alerts
- Interactive slicers
- Synchronized filters
- Dashboard page navigation
- Department and regional analysis

## Project Outcome

This project demonstrates the use of Power BI to transform operational healthcare data into an interactive decision-support dashboard.

The dashboard helps identify resource shortages, analyze operational performance, monitor geographical resource distribution, evaluate historical trends, estimate future resource demand, and highlight potential operational issues through automated alerts.

## Author

Tayyaba Awan

Computer Science Student

National University of Pakistan

## Project Type

Mini Project – Enterprise Operational Performance & Resource Predictor

## Domain

Healthcare Analytics

## License

This project is created for educational and internship purposes.
