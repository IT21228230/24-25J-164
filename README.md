# 24-25J-164 
#  Disease Analysis - Sharan U.

This repository contains the implementation of the **Automated Agriculture System** designed for **accurate water management** and **disease analysis** in tomato crops. The system leverages **machine learning**, **deep learning (CNNs)**, and **environmental data analysis** to provide real-time monitoring, disease detection, tailored interventions, and sustainable farming solutions.

---

## Project Overview

Growing tomatoes involves challenges such as managing diseases and optimizing resources. This project aims to:
- **Detect and diagnose tomato diseases** using image-based deep learning techniques.
- **Provide actionable recommendations** for treatment and resource optimization.
- Promote **sustainable agricultural practices** by reducing chemical dependency and waste.

### Key Features
1. **Real-time Monitoring**: Continuous data collection from plants and environmental sensors.
2. **Disease Diagnosis**: Accurate identification of bacterial, fungal, and viral infections using CNN-based models.
3. **Tailored Interventions**: Customized fertilization and treatment plans based on real-time data.
4. **Scalability and Accessibility**: Designed for small to medium-sized farms.
5. **User-Friendly Interface**: Mobile app and web dashboard for monitoring and recommendations.

---

## System Architecture

The system follows the **MAPE Control Loop**:
1. **Monitor**: Collect plant images and environmental data.
2. **Analyze**: Detect disease symptoms and growth anomalies.
3. **Plan**: Generate treatment strategies tailored to specific conditions.
4. **Execute**: Automate irrigation and fertilization systems based on analysis.

---

## Technologies Used

- **Programming Language**: Python
- **Machine Learning Frameworks**: TensorFlow, VGG16
- **Frontend**: React.js with Material UI
- **UI Design**: Figma
- **Backend Integration**: Docker, Kubernetes, Jenkins
- **Testing Tools**: Jest, Postman, Unit Test
- **Version Control**: Git (GitHub/GitLab)

---

## Dataset

The system uses a dataset consisting of:
- Images of healthy and diseased tomato plants under various environmental conditions.

### Preprocessing
- Noise removal, image augmentation, and normalization.
- Labeling images with specific disease categories.

---



# Yield Prediction and Harvest Readiness - IT21290206  Mayootharan P

This repository contains the implementation of a research-driven system for tomato yield prediction, harvest readiness estimation, and fertilizer plan prediction using real-time sensor data and agricultural department datasets. The project leverages advanced data analytics and machine learning models to enhance agricultural productivity and sustainability.

---

**Project Overview**

Efficient farming requires accurate predictions of crop yield, harvest readiness, and fertilizer needs. This project aims to combine real-time data from sensors with **historical datasets from agricultural departments to provide actionable insights for farmers.

**Key Objectives**
1. Yield Prediction: Forecast the expected yield of tomato crops using historical and real-time data.
2. Harvest Readiness: Estimate the optimal time for harvesting based on real-time environmental and crop data.
3. Fertilizer Plan Prediction: Provide tailored fertilizer recommendations based on soil and environmental conditions.


---

**Features**

- Real-Time Data Collection:
  - Soil Temperature Sensor: Monitors soil temperature.
  - Environment Temperature Sensor: Measures ambient temperature.
  - Humidity Sensor: Tracks environmental humidity.
  
- Data Integration:
  - Combines sensor data with historical datasets from agricultural departments for better accuracy.
  
- Predictive Models:
  - Machine learning models trained on historical and real-time data for yield, harvest readiness, and fertilizer recommendations.

- User-Friendly Interface:
  - Dashboard to visualize data and predictions.
  - Alerts for harvest readiness and fertilizer application schedules.

---

**System Architecture**

The system integrates the following components:
1. Data Collection: Real-time sensor data and historical datasets.
2. Preprocessing: Data cleaning, normalization, and feature extraction.
3. Model Training:
   - Yield prediction model.
   - Harvest readiness estimation model.
   - Fertilizer prediction model.
4. Prediction and Visualization:
   - Generate insights and display them on a user-friendly dashboard.

---

**Technologies Used**

- Programming Languages: Python
- Machine Learning Frameworks: Random Forest
- Database: Firebase for historical and real-time data storage
- Frontend: Flask 
- Backend: Python
- Sensors: Soil temperature, environmental temperature, and humidity sensors


---


**Data Sources**

1. Agricultural Department Datasets:
   - Historical data on tomato yield, fertilizer usage, and harvest timelines, Growth stage
2. Real-Time Sensor Data:
   - Soil temperature, environmental temperature, and humidity readings.

# Watering   Management - Nakulabasgaran Y. IT21228230
##  Overview

Water Management Technology. 
This project aims to:
- This component focuses on integrating advanced technologies to optimize water
usage in agricultural system, ensuring sustainable practices and reducing water 
wastage while maintaining crop health.

### Key Features
1. Soil Moisture Sensors: These sensors measure the moisture content in the soil, ensuring that crops receive the optimal amount of water.
2. Weather Forecast Integration: Utilizing weather data to predict rainfall and adjust irrigation schedules accordingly.
3. Automated Irrigation Systems: These systems can be programmed to deliver precise amounts of water to crops based on real-time data.
4. Scalability and Accessibility: Designed for small to medium-sized farms.
5. User-Friendly Interface: Mobile app and web dashboard for watering.


## System Architecture

The system integrates the following components:

    Data Collection: Real-time sensor data and historical datasets.
    Preprocessing: Data cleaning, normalization, and feature extraction.
    Model Training:
        Watering prediction model.
        Watering Schedule model.
    Prediction and Visualization:
        Generate insights and display them on a user-friendly dashboard.

## Technologies Used

    Programming Languages: Python
    Machine Learning Frameworks: RandomForestRegressor
    Database: Firebase for historical and real-time data storage
    Frontend: React.js with Material UI
    UI Design: Figma
    Backend Integration: Docker, Kubernetes, Jenkins
    Testing Tools: Jest, Postman, Unit Test, and Arduino IDE
	Version Control: Git (GitHub/GitLab)
    Tools: Submersible Mini pump - It give water to soil when the sensor sends the signal that the moisture level in the soil is low.
	       Channel-5V-Relay-Module - turn on and off the pump automatically as the required water level is reached 
	       ESP32 Microcontroller - For data processing and communication.

## Data Sources

    Agricultural Department Datasets:
        Historical data on Precipitation (mm),Ambient Temp (°C),Humidity (%),Soil Temp (°C),Soil Moisture (%),Watering Action,Watering Duration (minutes)
    Real-Time Sensor Data:
        Precipitation (mm),Ambient Temp (°C),Humidity (%),Soil Temp (°C),Soil Moisture readings.

# Integrated Weather Forecasting and Plant Growth Monitoring System Based on Soil Moisture Analysis - Sankeethan Y. IT21228162

##  Overview
 
This project aims to:
- This component integrates weather forecasting and soil moisture analysis to monitor plant growth and predict future growth patterns. 
The goal is to optimize farming practices by aligning them with environmental conditions and crop needs.


### Key Features
1. Develop a system for monitoring plant growth.
2. Weather Forecast Integration: Utilizing weather data to predict rainfall and adjust irrigation schedules accordingly.
3. Predict growth outcomes based on customized fertilization.
4. Scalability and Accessibility: Designed for small to medium-sized farms.
5. User-Friendly Interface: Mobile app and web dashboard for monitoring plant growth.

---

## System Architecture

The system integrates the following components:

    Data Collection: Real-time sensor data and historical datasets.
    Preprocessing: Data cleaning, normalization, and feature extraction.
    Model Training:
        plant growth prediction model.
        Weather forecasting  model.
    Prediction and Visualization:
        Generate insights and display them on a user-friendly dashboard.

## Technologies Used

    Programming Languages: Python
    Machine Learning Frameworks: RandomForestRegressor
    Database: Firebase for historical and real-time data storage
    Frontend: React.js with Material UI
    UI Design: Figma
    Backend Integration: Docker, Kubernetes, Jenkins
    Testing Tools: Jest, Postman, Unit Test, and Arduino IDE
	Version Control: Git (GitHub/GitLab)
	Sensor : Soil Moisture Sensor Module- measure or estimate the amount of water in the soil. 
    Tools: ESP32 Microcontroller - For data processing and communication.

## Data Sources

    Agricultural Department Datasets:
Historical data on Soil Moisture (%),Precipitation(mm),Fertilizer Amount(kg),Plant Height(cm),Leaf Area(cmÂ²),Growth Stage

    Real-Time Sensor Data:
        Precipitation (mm),Soil Moisture readings.
	
# GitHub Repositorie Link - https://github.com/IT21228230/24-25J-164.git
