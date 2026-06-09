## UBER END-TO-END PROJECT (Internship Project)

Built an end-to-end ELT pipeline for Uber ride analytics using Medallion Architecture (Bronze, Silver, and Gold layers). Implemented scalable data ingestion, transformation, and data quality processing workflows to move raw data into analytics-ready datasets. Designed and developed a Star Schema data model in the Gold layer to support downstream BI

## Project Architecture

![Project Architecture](https://github.com/anshlambagit/Uber_Data_Engineer_Project/blob/main/architecture.png)


Task 1: Explore Azure Portal & Create Resource Group
Screenshot

<img width="1645" height="880" alt="image" src="https://github.com/user-attachments/assets/790957bb-5b1d-46d9-83cd-b901f6baea03" />


Task 2: Storage Setup
Created Storage Account
Created Blob Container
Uploaded CSV File
Screenshot

<img width="1637" height="876" alt="Screenshot 2026-06-08 201119" src="https://github.com/user-attachments/assets/b6ed3bf2-4fd6-43ee-ac45-420e79c63221" />


Task 3: ADF Basics
Created Azure Data Factory
Created Linked Service
Created Source and Destination Datasets

<img width="1661" height="901" alt="Screenshot 2026-06-08 173557" src="https://github.com/user-attachments/assets/1be9814e-40f4-4671-904f-9c3204528f66" />


Linked Service

<img width="1522" height="741" alt="Screenshot 2026-06-08 173612" src="https://github.com/user-attachments/assets/cfa46b2e-8176-471e-99c6-39af5d54a83a" />


Get Metadata Activity



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

Screenshot

(Add Role Assignment Screenshot)
