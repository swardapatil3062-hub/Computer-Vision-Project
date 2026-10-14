# Computer-Vision-Project

#  WattWise Vision — Smart Electricity Meter Reader

##  Project Overview
**WattWise Vision** is an AI-powered electricity meter reading system that uses Computer Vision and Optical Character Recognition (OCR) to extract electricity readings from meter images. It calculates electricity consumption by comparing current readings with previous readings, detects unusual usage patterns, and forecasts future electricity consumption using Machine Learning.

##  Objectives
- Automatically extract electricity meter readings from uploaded images.
- Calculate electricity consumption using previous and current readings.
- Detect abnormal electricity usage and generate alerts.
- Predict future electricity consumption using Machine Learning.
- Provide an easy-to-use web interface for monitoring electricity usage.

##  Key Features
- **Meter Image Upload:** Upload an electricity meter image for automatic reading extraction.
- **OCR-Based Reading:** Extract numerical readings using EasyOCR.
- **Consumption Calculation:** Calculate electricity usage in kWh.
- **Anomaly Detection:** Identify unusually high electricity consumption.
- **Usage Forecasting:** Predict future electricity consumption using historical data.
- **Data Storage:** Store meter readings and consumption history in MySQL.
- **Web Dashboard:** Display readings, consumption, alerts, and predictions.

##  Tech Stack
- **Programming Language:** Python
- **Computer Vision:** OpenCV
- **OCR:** EasyOCR
- **Backend:** Flask
- **Database:** MySQL
- **Machine Learning:** Scikit-learn
- **Frontend:** HTML, CSS, JavaScript
- **Development Platform:** Google Colab / Local Python Environment

##  Project Workflow
1. Upload an electricity meter image.
2. Process the image using OpenCV.
3. Extract the meter reading using EasyOCR.
4. Compare the current reading with the previous reading.
5. Calculate electricity consumption in kWh.
6. Detect abnormal consumption using anomaly detection.
7. Forecast future electricity usage using Machine Learning.
8. Display the results on the web dashboard and save the data in MySQL.

##  Consumption Calculation
**Electricity Consumption = Current Reading − Previous Reading**

Example:

- Previous Reading: 1250 kWh
- Current Reading: 1380 kWh
- Total Consumption: 130 kWh

##  Project Uniqueness
WattWise Vision integrates four key technologies into one system:

- Computer Vision for meter image processing.
- OCR for automatic reading extraction.
- Anomaly Detection for identifying unusual consumption.
- Machine Learning for forecasting future electricity usage.

This combination reduces manual data entry and helps users monitor electricity consumption more efficiently.

##  Applications
- Residential electricity monitoring.
- Smart energy management systems.
- Electricity consumption analysis.
- Energy-saving and usage awareness.
- Smart homes and IoT-based energy solutions.

##  Future Enhancements
- Electricity bill estimation based on tariff rates.
- Support for different types of electricity meters.
- Real-time alerts through email or SMS.
- Interactive charts for monthly consumption.
- Integration with IoT-based smart energy meters.

##  Project Status
**Status:** In Development

This project is being developed as an AI/ML and Computer Vision project to demonstrate automated meter reading, electricity consumption analysis, anomaly detection, and usage forecasting.
