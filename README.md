# Database-Management-System-for-MH-Thamrin-University

MH.Thamrin Univeristy is a well known university in Indonesia. MH. Thamrin University, established in 1987 in Jakarta, Indonesia, is a respected private institution named after the nationalist Mohammad Husni Thamrin. It offers programs in Health Sciences, IT and Engineering, and Economics and Business, focusing on applied learning and innovation. With modern facilities and a prime location, the university prepares students for professional success and community impact. This project focusing on the database on the faculty of computer development based on the informatin we got from MH Thamrin University's Dean.

# ERD
<img width="2118" height="1046" alt="image" src="https://github.com/user-attachments/assets/96f40bd2-7e4d-4f2e-b950-d78a1612224b" />
- A total of 10 entities including its attributes, primary key, and relationship was created for inital ERD.

<img width="2149" height="1232" alt="image" src="https://github.com/user-attachments/assets/dac45975-033d-4b9d-9d32-d1b92ea8bfdf" />
- Expanded to 20 entities after applying 3NF normalization to reduce redundancy and improve data integrity.

# SQL Implementation
## DDL
<img width="2035" height="1141" alt="image" src="https://github.com/user-attachments/assets/fb99f22a-7f62-4137-a1a6-bfb5157d3257" />
- Created the database structure using CREATE.

| ! <img width="1906" height="1069" alt="image" src="https://github.com/user-attachments/assets/9d6c4bb6-ebd8-4fc2-80a0-5279977855cb" /> | ! <img width="1906" height="1069" alt="image" src="https://github.com/user-attachments/assets/9d6c4bb6-ebd8-4fc2-80a0-5279977855cb" /> |
|-------------------------------|-------------------------------|
<p align="center">
  <img width="1906" height="1069" alt="image" src="https://github.com/user-attachments/assets/9d6c4bb6-ebd8-4fc2-80a0-5279977855cb" />
  <img width="1908" height="1070" alt="image" src="https://github.com/user-attachments/assets/ec3674cb-3981-4701-bc61-21227ebbef9d" />
</p>
- Successfully tested ALTER and DROP commands to adjust and remove database objects as required.

## DML
<p align="center">
  <img width="1908" height="1058" alt="image" src="https://github.com/user-attachments/assets/319892a3-4817-4143-9bf2-0d2fec8bf785" />
  <img width="1906" height="1066" alt="image" src="https://github.com/user-attachments/assets/c03f0926-4b7e-4a0f-93e1-a9b658fa5191" />
</p>
- Inserted all data into the table we utilize INSERT ALL function.

<p align="center">
  <img width="1906" height="1065" alt="image" src="https://github.com/user-attachments/assets/bb4342cc-aee5-49a1-9203-de4774d1a8a1" /> 
  <img width="1908" height="1066" alt="image" src="https://github.com/user-attachments/assets/0e1f79e8-76d9-46bf-9566-3334a168a2c9" />
</p>
<p align="center">
  <img width="1908" height="1070" alt="image" src="https://github.com/user-attachments/assets/639f802e-57d1-43cd-b5a8-9dbd5a5e296c" /> 
  <img width="1906" height="1073" alt="image" src="https://github.com/user-attachments/assets/7591e6e1-f78d-4f73-ba8c-83e8ed8e9c1f" />
</p>
- Other DML function such as UPDATE, DELETE, and JOIN was also tested and showing successful adjustment.

<p align="center">
  <img width="1911" height="1063" alt="image" src="https://github.com/user-attachments/assets/04926d93-6177-4c20-97e3-b96633532db5" /> 
  <img width="1898" height="1060" alt="image" src="https://github.com/user-attachments/assets/7d445356-33e1-49fc-ada0-01756839464f" />
</p>
<img width="1909" height="1068" alt="image" src="https://github.com/user-attachments/assets/0186a702-96dd-4c63-97ff-225d42de8d68" />
- Aggregating function using DML where we list courses' average grade by initialy define the numerical grade in each alphabet grade.
- The aggregation was successful, showing Introduction to Multimedia Technology and Machine Learning have the **highest average grade.**
- Meanwhile, Data Structure has the **lowest average grade.**

<p align="center">
  <img width="1746" height="978" alt="image" src="https://github.com/user-attachments/assets/2d106442-8279-4e7b-9973-f5f81b4e0c70" /> 
  <img width="1737" height="980" alt="image" src="https://github.com/user-attachments/assets/eefd7684-6583-42cb-8d2c-4a6886894710" />
</p>
- Lastly, nested queris was tested where we wanted to look for alumni that invlove in projects in specific department.
- Successfully retrieved accurate and relevant results.

# Results
- Highest average grades: Introduction to Multimedia Technology, Machine Learning.
- Lowest average grade: Data Structure.
- All queries executed successfully, confirming data accuracy and integrity.

# Conclusion
This project presents the complete database development cycle from conceptual design of an ERD to the actual working SQL database. The resulting system supports accurate data management, complex reporting, and provides a strong foundation for future integration into a larger student information system that covering the entire university.








