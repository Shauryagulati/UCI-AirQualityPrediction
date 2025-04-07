This assignment provides hands-on experience with Apache Kafka for real-time data streaming and environmental time series analysis. You will work with the UCI Air Quality dataset to set up a Kafka pipeline, explore the data, and develop predictive models for pollutant concentrations. This assignment is structured to help you understand the fundamentals of Kafka and its application in real-time environmental monitoring contexts.

The Urban Environmental Monitoring Challenge: As urbanization accelerates, monitoring and predicting air quality has become increasingly critical for public health management and urban planning. High concentrations of air pollutants like CO, NOx, and Benzene can significantly impact respiratory health and overall quality of life. Real-time air quality data analysis is essential for providing timely air quality alerts, optimizing traffic flow to reduce emissions, and informing policy decisions.

Your Role: You are tasked with setting up a Kafka-based data pipeline to stream air quality sensor data in real-time, analyze the time series data, and develop predictive models to forecast pollutant concentrations.

Technical Requirements

Kafka Version: 3.0.0 or newer
Python Version: 3.8 or newer
Required Libraries: kafka-python, pandas, numpy, scikit-learn, matplotlib, statsmodels
Optional Libraries: tensorflow/keras (only if choosing deep learning approaches)
System Requirements:
Minimum 8GB RAM, 4 CPU cores
10GB free disk space

Dataset Description
Dataset Name: UCI Air Quality Dataset

Source: UCI Machine Learning Repository - Air Quality Dataset (https://archive.ics.uci.edu/ml/datasets/Air+QualityLinks to an external site.)

Format and Structure:

CSV file format with 9,358 hourly instances (March 2004 to February 2005)
15 columns including date/time and various sensor readings
Missing values are marked with -200 in the dataset
Features include CO, NOx, NO2, Benzene, and other pollutant measurements
Ground truth measurements from certified analyzers included alongside sensor readings
For Your Reference:

CO: Carbon monoxide, measured in mg/m³
NOx: Nitrogen oxides, measured in ppb (parts per billion)
NO2: Nitrogen dioxide, measured in µg/m³
Benzene: Measured in µg/m³
Normal urban ranges: CO (0.5-5 mg/m³), NOx (5-100 ppb), Benzene (0.5-10 µg/m³)
