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

![Picture4-1](https://github.com/user-attachments/assets/3bcbdb66-ac19-41a7-aa72-fc19c3a698d4)

![Picture4-2](https://github.com/user-attachments/assets/67dd667d-8411-43f2-85cb-d256fdb855a4)

•	Test Data: Generated simulated CGPA data to test the system’s functionality before using live student records.



# Step 5: Data Ingestion

![PIC 5](https://github.com/user-attachments/assets/a5ee21d7-7e40-4fd5-bc76-343bb4ee961b)

![Picture5](https://github.com/user-attachments/assets/0277b79d-4f9e-4a33-9e8a-bb61e8b5022d)

•	Tool: Used AWS Lambda to automate the ingestion of CGPA data, ensuring real-time updates.



# Step 6: Data Storage

![PIC 6](https://github.com/user-attachments/assets/625c9209-72c5-4a07-b24f-c4eee3d0d3f0)

![Picture6](https://github.com/user-attachments/assets/16e9e686-de2d-40e6-a8b3-49905a83419e)

•	Implementation: Stored data in AWS RDS, using relational databases to allow for easy access and querying.



# Step 7: Data Pipeline Design

![PIC 7](https://github.com/user-attachments/assets/150803d9-f401-4536-aac6-095b84330533)

![Picture7-1](https://github.com/user-attachments/assets/44ddc453-d351-4456-9b19-a7cb9d1f08e6)

![Picture7-2](https://github.com/user-attachments/assets/488cd264-0483-486f-a4ee-afcecdae5726)

![Picture7-3](https://github.com/user-attachments/assets/9707eab3-cd7a-482b-908c-4eeba8199408)

•	Design: Mapped out the entire data pipeline using draw.io, from ingestion to analysis and visualization.



# Step 8: Data Cleaning

![PIC 8](https://github.com/user-attachments/assets/ff2a8eda-abda-40ae-9b61-aa84cc4c0dd1)

![Picture8](https://github.com/user-attachments/assets/6da3ef67-5458-45d4-b0f3-36f30445a2c0)

•	Process: Cleaned the data to remove duplicates, handle missing values, and standardize CGPA formats.



# Step 9: Data Structuring

![PIC 9](https://github.com/user-attachments/assets/2e5ef07d-0f09-44d4-a978-0d5e9869dc71)

•	Structure: Organized the cleaned data into tables, ready for analysis.



# Step 10: Data Pipeline Implementation

![Picture10-1](https://github.com/user-attachments/assets/1976e779-bff7-40f4-9228-accefc21d568)

![Picture10-2](https://github.com/user-attachments/assets/44a5dd80-3e38-4a7d-b063-a2d7cb434dfd)

•	Technology: Deployed the pipeline using AWS Lambda for event-driven automation and AWS Elastic Beanstalk for scalable applications.



# Step 11: Data Analysis

![PIC 11](https://github.com/user-attachments/assets/84ae1595-083a-4ec8-9f7f-52a3b72ad270)

![Picture11-1](https://github.com/user-attachments/assets/cf37d158-909f-43bd-9740-d0258af5e71d)

![Picture11-2](https://github.com/user-attachments/assets/4f0226d3-27cc-4ea8-84b2-de4e49d2ade3)

•	Analysis Tool: Used AWS Athena to analyze CGPA records, identifying students at risk and calculating alert thresholds.



# Step 12: Data Visualization

![PIC 12](https://github.com/user-attachments/assets/ea68760d-cf70-4dfc-ba78-1491467f2fb4)

•	Tool: Used AWS QuickSight to create visualizations showing CGPA trends, academic standing distributions, and alerts.



# Step 13: Data Publishing

![Picture13-1](https://github.com/user-attachments/assets/7dc0ba2d-dce0-4296-ba97-c721782a6dc4)

![Picture13-2](https://github.com/user-attachments/assets/bab51347-c6f7-43ae-8a73-7ee2049530c0)

![Picture13-3](https://github.com/user-attachments/assets/38d98d34-b422-4a2e-b0fc-70ec42dc90ee)

•	Method: Published the results on a web portal for faculty to access real-time academic standing reports.



# Step 14: Data Enriching

![Picture14](https://github.com/user-attachments/assets/7986eb87-b646-41be-a4e7-8729cf8db792)

•	Process: Enhanced the dataset with additional information, like student attendance, to offer a more comprehensive academic standing analysis.



# Step 15: Data Protection

![Picture15-1](https://github.com/user-attachments/assets/028852d1-9b80-401a-a5cd-44c8c283488e)

![Picture15-2](https://github.com/user-attachments/assets/0a421bd0-3f4c-49c5-94fa-93682fa32c25)

•	Security: Implemented security measures via AWS IAM to ensure that student data was protected and only accessible to authorized personnel.



# Step 16: Data Governance

![Picture16-1](https://github.com/user-attachments/assets/573b7016-e865-4697-a695-38d5e0497d12)

![Picture16-2](https://github.com/user-attachments/assets/5ceb17a6-9d32-4ad0-a77b-b3fea5125c35)

•	Governance: Established governance policies to maintain data integrity and compliance with institutional guidelines, using AWS CloudTrail for audit trails.



# Step 17: Data Monitoring

![Picture17-1](https://github.com/user-attachments/assets/85185cf3-3c9a-41e9-a104-5ac398321760)

![Picture17-2](https://github.com/user-attachments/assets/4663b363-3910-4f81-91ad-6f77a30a44a9)

•	Monitoring: Set up AWS CloudWatch to monitor the system's health and alert administrators if any issues arise.
