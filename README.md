
# Voting Analysis using Big Data Technologies

This project demonstrates a real-time voting analysis system using modern big data technologies. The system simulates a voting process, extracts data from an external API, processes it using Apache Kafka and Apache Spark, and visualizes the results with Streamlit.

## Overview

### Components
1. **Data Extraction**:
   - Data is fetched from the API:
     ```text
     BASE_URL = 'https://randomuser.me/api/?nat=gb'
     ```
     Simulated voters are assigned to one of three parties:
     - **Management Party**
     - **Savior Party**
     - **Tech Republic Party**

2. **Real-time Data Processing**:
   - **Apache Kafka** is used for real-time streaming of voting data.
   - **Apache Spark** processes the data in real-time, aggregating results and performing analytics.

3. **Visualization**:
   - **Streamlit** provides an interactive dashboard to display voting results in real-time.


![Alt Text](https://raw.githubusercontent.com/Punam918/Real_Time_Voting_Analysis/refs/heads/master/Pictures/voting1.jpg)



![Alt Text](https://raw.githubusercontent.com/Punam918/Real_Time_Voting_Analysis/refs/heads/master/Pictures/voting2.jpg)

![Alt Text](https://raw.githubusercontent.com/Punam918/Real_Time_Voting_Analysis/refs/heads/master/Pictures/voting3.py.jpg)

