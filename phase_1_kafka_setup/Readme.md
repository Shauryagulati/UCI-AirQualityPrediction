Phase 1: Kafka Setup and Data Streaming (20 Points)
Objective: Install Apache Kafka, create a Kafka producer to stream air quality data, and a Kafka consumer to process the data in real-time.

Requirements:

Kafka Setup and Configuration:
Install Apache Kafka and its dependencies on your development environment
Configure and start Zookeeper and Kafka servers
Create a Kafka topic for air quality data
Producer Implementation:
Develop a Python script that reads the UCI Air Quality dataset
Create a Kafka producer that sends the dataset records to your Kafka topic
Implement a time delay mechanism to simulate real-time data (each record should be sent with an appropriate delay to mimic hourly readings)
Include proper error handling and logging
Consumer Implementation:
Develop a Python script that creates a Kafka consumer
Configure the consumer to read from your air quality data topic
Process the incoming data and store it for analysis
Implement appropriate error handling and logging
Data Preprocessing:
Develop a strategy for handling missing values (-200) in the dataset
Document your approach to data preprocessing and justify your decisions
Implement the preprocessing logic in your producer or consumer (or both)
Deliverables:

py: Python script for the Kafka producer
py: Python script for the Kafka consumer
md: Documentation of your Kafka setup process, including any challenges encountered and how you resolved them
md: Documentation of your data preprocessing strategy
Evaluation Criteria:

Correct implementation of Kafka producer and consumer (10 points)
Proper handling of the dataset, including missing values (5 points)
Effective simulation of real-time data streaming (3 points)
Quality of documentation and error handling (2 points)
