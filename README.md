# AWS Data Analytics Platform for The City of Vancouver
Project Description
The AWS Data Analytics Platform (DAP) for the City of Vancouver was developed to store, process, and analyze vast datasets related to urban infrastructure and public services. The project uses AWS cloud services for secure storage, data encryption, monitoring, and processing to enable the city to make data-driven decisions efficiently.

# Project Title
Implementation of Data Analytics Platform for the City of Vancouver using AWS

# Objective
The main objective of this project is to design a scalable and secure Data Analytics Platform (DAP) using Amazon Web Services (AWS) to analyze datasets such as operating permits, parking tickets, lost and found pets, and 3-1-1 inquiries from 2023 and 2024. The platform leverages AWS services to automate data ingestion, processing, analysis, and visualization, ensuring high availability, data security, and operational efficiency.

# Background
As the City of Vancouver seeks to optimize its public services, it requires a robust platform to store and analyze a vast amount of data. The DAP was designed using AWS to meet these challenges by offering a secure environment for data storage, encryption, monitoring, and analysis. The platform uses various AWS services like S3, Glue, Athena, and EC2 to ensure the timely availability and security of public datasets.

# Scope
The project focuses on the following areas:
Data Storage: Efficient and secure storage of datasets using Amazon S3.
Data Transformation: Automating data ingestion and transformation using AWS Glue.
Data Analysis: Using Amazon Athena for querying and analyzing the datasets.
Data Security: Ensuring encryption and access control using AWS KMS and IAM policies.
Monitoring: Using CloudWatch and CloudTrail for continuous monitoring of system performance and data security.

# Methodology
Current State Assessment:
Analyze the existing data sources and workflows.
Identify key datasets, such as operating permits and parking tickets.
Data Storage Design:
Store datasets in Amazon S3 with versioning, encryption, and backup mechanisms.
Data Cleansing and ETL Process:
Use AWS Glue DataBrew to clean and prepare data for analysis.
Data Protection:
Implement AWS KMS for encryption and S3 bucket policies for access control.
Data Monitoring:
Monitor performance and track expenditures using CloudWatch dashboards and alarms.
Data Governance:
Establish governance processes to ensure data quality, including masking sensitive data.
Data Analysis and Visualization:
Perform SQL-based queries using Athena, and visualize the results with integrated tools.

# Tools and Technologies
AWS Services: S3, Glue, Athena, EC2, CloudWatch, CloudTrail, KMS
Data Profiling: AWS Glue DataBrew for cleansing and transforming datasets.
Data Analysis: Amazon Athena for querying datasets stored in S3.
Data Monitoring: CloudWatch for monitoring system performance and CloudTrail for tracking API calls.
Security: AWS KMS for encryption, IAM for access control.

# Deliverables
Data Analytics Platform (DAP): A comprehensive platform deployed on AWS, including processes, data pipelines, and security measures.
Cleaned Datasets: Datasets that are cleansed, transformed, and validated, stored in S3 for further analysis.
Monitoring Dashboard: A real-time dashboard created in CloudWatch to monitor data quality and system performance.
Documentation: Detailed documentation outlining data flows, ETL processes, and governance measures.
Training Resources: Educational materials for city officials and administrators on how to use the platform effectively.

# DAP Architecture Overview
The architecture is built on six core pillars:
Operational Excellence: Automated data processing and monitoring using AWS Glue and CloudWatch.
Security: Data encryption using KMS and secure access control with IAM.
Reliability: Data replication across regions using S3 and regular backups.
Performance Efficiency: Use of Athena and Glue for scalable data processing.
Cost Optimization: Efficient use of serverless technologies and lifecycle management in S3.
Sustainability: Use of AWS serverless technologies to minimize resource consumption.

# Timeline
Phase 1 (Design & Implementation): Completed by August 27, 2024.
Phase 2 (Data Protection & Monitoring): Completed by September 15, 2024.

# Conclusion
This project demonstrates the use of AWS cloud services to design a scalable, secure, and efficient Data Analytics Platform for the City of Vancouver. The platform ensures high data quality, reliable performance, and robust security measures, while being cost-effective and sustainable.
