## Celebal Excellence Internship Program (CEI)
<p>
Week 4 Assignment Project Title : UBER END-TO-END PROJECT
Submitted By: Harshit Sharma

Role: Data Engineering Intern
Assignment Week: Week 4
Domain: Data Engineering
</p>

## UBER END-TO-END PROJECT

This project is an end-to-end real-time data engineering pipeline built on Azure. The data originates from an external REST API and is first ingested using Azure Data Factory (ADF). ADF orchestrates and retrieves the raw data from the API, then stores it in the Bronze layer for raw data retention.

After ingestion, the data is published to Azure Event Hub, which acts as a real-time streaming platform. Apache Spark Structured Streaming continuously consumes the events from Event Hub, performs data cleansing, validation, and business transformations, and enriches the records as required.

The transformed data is then processed through a Medallion Architecture consisting of Bronze, Silver, and Gold layers. The Bronze layer stores raw data, the Silver layer contains cleaned and validated data, and the Gold layer contains business-ready datasets.

In the Gold layer, a Star Schema data model is implemented with fact and dimension tables to support analytical workloads. Finally, the curated data can be consumed by reporting and BI tools for dashboards, KPI tracking, and business insights.
## Project Architecture

![Project Architecture](https://github.com/anshlambagit/Uber_Data_Engineer_Project/blob/main/architecture.png)


Task 1: Explore Azure Portal & Create Resource Group

<img width="1645" height="880" alt="image" src="https://github.com/user-attachments/assets/790957bb-5b1d-46d9-83cd-b901f6baea03" />


Task 2: Storage Setup
Created Storage Account
Created Blob Container
Uploaded CSV File


<img width="1637" height="876" alt="Screenshot 2026-06-08 201119" src="https://github.com/user-attachments/assets/b6ed3bf2-4fd6-43ee-ac45-420e79c63221" />


Task 3: ADF Basics
Created Azure Data Factory
Created Linked Service
Created Source and Destination Datasets

<img width="1661" height="901" alt="Screenshot 2026-06-08 173557" src="https://github.com/user-attachments/assets/1be9814e-40f4-4671-904f-9c3204528f66" />


Linked Service

<img width="1522" height="741" alt="Screenshot 2026-06-08 173612" src="https://github.com/user-attachments/assets/cfa46b2e-8176-471e-99c6-39af5d54a83a" />

Task 4: Pipeline Development
Created Copy Data Pipeline
Configured Source and Destination
Added ForEach Activity (if applicable)
Screenshot

<img width="797" height="312" alt="Screenshot 2026-06-08 201216" src="https://github.com/user-attachments/assets/5c0fd361-b38b-4579-b703-52f868413357" />


Task 5: Pipeline Execution
Executed Pipeline using Debug/Trigger
Screenshot

<img width="1626" height="906" alt="Screenshot 2026-06-08 173926" src="https://github.com/user-attachments/assets/0171374b-497f-4f0c-ad19-08840b986b08" />


Task 6: IAM Roles
Assigned Reader Role
Assigned Contributor Role
Provided Storage Access to ADF

<img width="1505" height="877" alt="Screenshot 2026-06-08 201733" src="https://github.com/user-attachments/assets/d24898cf-8db7-4e1b-ab55-e4f9b2e6094b" />

