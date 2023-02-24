# ISTDA-Final-Data-Engineering-Project
End to end data engineering project on Google Cloud
 
 This project involves:   
 
 data ingestion from weather API in JSON file format via NIFI 
 
 after some transformation,  streaming the real-time data to Kafka.
 
 Load the incoming real time data from Kafka to BigQuery via Spark
 
 Docker container created in order to deploy Streamlit application quickly in case of changes to the source code.


![image](https://user-images.githubusercontent.com/56925242/221169917-b4fedaf6-3417-4ee4-a6fb-9220456aee0b.png)

NIFI
![image](https://user-images.githubusercontent.com/56925242/221180666-a0790c66-0b92-47cf-b358-afa43bd68532.png)

BigQuery Table
![image](https://user-images.githubusercontent.com/56925242/221185944-ad94a236-fb26-4acc-bcfc-35c36a393c26.png)
