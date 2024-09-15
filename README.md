This project aims to develop a scalable and automated system that monitors student CGPA records, evaluates academic standing, and issues alerts for students at risk. The project streamlines academic monitoring using data pipelines and AWS technologies.


# Objective:

This project aims to develop a scalable and automated system that monitors student CGPA records, evaluates academic standing, and issues alerts for students at risk. The project streamlines academic monitoring using data pipelines and AWS technologies.




# Dataset:

The dataset consists of CGPA records for students over multiple semesters, including Student ID, CGPA, and semester dates. The data is used to assess academic standing and alert students whose CGPA falls below institutional standards.



# Methodology:

The project follows a step-by-step approach, leveraging AWS services and tools to automate and monitor the academic standing process.



# Step 1: Data Analytical Question Formulation

![PIC 1-1](https://github.com/user-attachments/assets/c4f1a1f1-f525-4a68-975c-0ee84a0cb6e1)


•	Question: How can we efficiently monitor student CGPA and issue academic alerts based on CGPA thresholds?



# Step 2: Data Discovery

![PictureTWO](https://github.com/user-attachments/assets/5630d64f-33cd-4c62-9a5e-c6d5747e8a0d)

![PIC 1](https://github.com/user-attachments/assets/ac4c3fdf-ff54-407b-96a5-0a60fd843b00)

•	Data Collection: Collected CGPA records from the UCW Registrar’s Office.
•	Exploration: Identified key columns like CGPA, Student ID, and Semester Dates.



# Step 3: Data Storage Design

![PIC 3](https://github.com/user-attachments/assets/467a0962-3e9a-4f61-ac2c-7459425ef02a)

![Picture3](https://github.com/user-attachments/assets/3b5540f8-c6df-4f2e-9115-f5abb3ed1da0)

•	Design: Created a schema for storing CGPA records in AWS RDS, ensuring fast query performance and secure access.



# Step 4: Test Dataset Generation

![PIC 4](https://github.com/user-attachments/assets/4a26c17c-3c2f-4c0e-ac67-ab98ce9a8f2e)

![Picture4-1](https://github.com/user-attachments/assets/6d013d96-6dce-4ada-9ac8-7b653e789a90)

![Picture4-2](https://github.com/user-attachments/assets/6d47c3e4-db52-4174-a687-76d8cfe42bdd)

•	Test Data: Generated simulated CGPA data to test the system’s functionality before using live student records.



# Step 5: Data Ingestion

![PIC 5](https://github.com/user-attachments/assets/a5ee21d7-7e40-4fd5-bc76-343bb4ee961b)

![Picture5](https://github.com/user-attachments/assets/58081ef6-f72a-4e13-9787-69de5ed0194f)

•	Tool: Used AWS Lambda to automate the ingestion of CGPA data, ensuring real-time updates.



# Step 6: Data Storage

![Picture6](https://github.com/user-attachments/assets/bcd89a26-575f-4ef4-a192-44d91bbf43bf)

•	Implementation: Stored data in AWS RDS, using relational databases to allow for easy access and querying.



# Step 7: Data Pipeline Design

![Picture7-1](https://github.com/user-attachments/assets/ee2bb43f-2586-414d-83a9-6ddbb0a3f027)

![Picture7-2](https://github.com/user-attachments/assets/d9d296c9-bd07-410f-b6b4-3ad3b64a262b)

![Picture7-3](https://github.com/user-attachments/assets/14c82ab8-e762-4c62-bfdb-2ecb76f2461f)

•	Design: Mapped out the entire data pipeline using draw.io, from ingestion to analysis and visualization.



# Step 8: Data Cleaning

![Picture8](https://github.com/user-attachments/assets/04659c43-a43a-417c-b712-5b698b78e601)

•	Process: Cleaned the data to remove duplicates, handle missing values, and standardize CGPA formats.



# Step 9: Data Structuring

•	Structure: Organized the cleaned data into tables, ready for analysis.



# Step 10: Data Pipeline Implementation

![Picture10-1](https://github.com/user-attachments/assets/6fa34715-2bb8-4f1f-b4cf-ba61bdbf0796)

![Picture10-2](https://github.com/user-attachments/assets/3df77b6c-7279-4872-bcfb-18a8c8445e87)

•	Technology: Deployed the pipeline using AWS Lambda for event-driven automation and AWS Elastic Beanstalk for scalable applications.



# Step 11: Data Analysis

![Picture11-1](https://github.com/user-attachments/assets/dd03e510-a5f0-440e-9967-ccc2aaa57f04)

![Picture11-2](https://github.com/user-attachments/assets/71f13967-92c2-447d-ae4f-b73e455f5b34)

•	Analysis Tool: Used AWS Athena to analyze CGPA records, identifying students at risk and calculating alert thresholds.



# Step 12: Data Visualization

•	Tool: Used AWS QuickSight to create visualizations showing CGPA trends, academic standing distributions, and alerts.



# Step 13: Data Publishing

![Picture13-1](https://github.com/user-attachments/assets/4e7fcb41-9ddd-4ec8-be3d-3fb4b302c946)

![Picture13-2](https://github.com/user-attachments/assets/68a86529-0856-4064-ad99-e362a8e87dbf)

![Picture13-3](https://github.com/user-attachments/assets/78c584c9-8505-4504-8d2c-aa857d847dd0)

•	Method: Published the results on a web portal for faculty to access real-time academic standing reports.



# Step 14: Data Enriching

![Picture14](https://github.com/user-attachments/assets/5bc3e27d-3558-4266-8b52-b40796136a48)

•	Process: Enhanced the dataset with additional information, like student attendance, to offer a more comprehensive academic standing analysis.



# Step 15: Data Protection

![Picture15-1](https://github.com/user-attachments/assets/45262ab2-90c9-4024-a5de-96c587c427e2)

![Picture15-2](https://github.com/user-attachments/assets/f247a37e-2a0a-4069-aed2-9e25e3b877ab)

•	Security: Implemented security measures via AWS IAM to ensure that student data was protected and only accessible to authorized personnel.



# Step 16: Data Governance

![Picture16-1](https://github.com/user-attachments/assets/9fbaa28e-cedf-4375-a97e-80c3924e9fb2)

![Picture16-2](https://github.com/user-attachments/assets/59c94b22-4e7c-46cd-b357-18d9191409df)

•	Governance: Established governance policies to maintain data integrity and compliance with institutional guidelines, using AWS CloudTrail for audit trails.



# Step 17: Data Monitoring

![Picture17-1](https://github.com/user-attachments/assets/4b807bdd-4c57-44cb-85b6-6e0e555dc3ac)

![Picture17-2](https://github.com/user-attachments/assets/66982fd5-9a09-405b-a683-37b1d2360580)

•	Monitoring: Set up AWS CloudWatch to monitor the system's health and alert administrators if any issues arise.
