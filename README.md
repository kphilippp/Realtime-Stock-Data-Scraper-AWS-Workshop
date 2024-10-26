
# Realtime Stock Data Scraper

This project serves as an introduction to key AWS services for managing and analyzing streaming data. Through this project, I explored the basics of:

- **AWS Kafka**
- **AWS EC2**
- **AWS Glue**
- **AWS Athena**

Additionally, I refreshed my knowledge of **AWS S3** for data storage and integration.

## What I Learned

### AWS Kafka
AWS Kafka is a service used to process "streaming" data, organizing and distributing it in real-time. Key concepts I learned include:
- **Producers**: Applications or services that send data to Kafka.
- **Brokers**: Servers that store data streams and manage data topics.
- **Topics**: Logical channels where data streams are categorized.
- **Partitions**: Subdivisions within topics that allow for parallel processing.
- **Consumers**: Applications or services that retrieve and process data from Kafka topics.

Kafka is supported by **Zookeeper**, a server management system that helps manage Kafka brokers, handle leader elections, and ensure data consistency across brokers.

### AWS EC2
AWS EC2 provides scalable virtual machine instances on AWS. In this project, I deployed Kafka on an EC2 instance instead of my local machine, learning about instance management, networking, and security configurations for cloud-based applications.

### AWS Glue
AWS Glue is a data integration service that transforms raw data in S3 into structured tables, making it queryable. Glue uses:
- **Crawlers**: Tools that scan data in S3, determine its schema, and create metadata tables automatically.
  
Glue simplifies the process of preparing data for analysis by services like Athena.

### AWS Athena
AWS Athena is a serverless query service that allows SQL querying on data stored in S3, using tables created by AWS Glue. In this project, Athena was used to query and analyze stock data that was parsed and structured by Glue.

### AWS S3
AWS S3 served as the primary storage for our data. I refreshed my understanding of S3’s capabilities, including data storage, organization, and integration with other AWS services like Glue and Athena.

## Summary
This project provided a hands-on introduction to streaming data processing and analysis using Kafka, along with a robust AWS-based data pipeline using EC2, S3, Glue, and Athena. Each component plays a distinct role, creating a powerful workflow for handling and querying real-time stock data.

<img width="1271" alt="Screenshot 2024-10-25 at 9 28 35 PM" src="https://github.com/user-attachments/assets/82571ec2-de25-43d2-8a82-4c36242f8130">
<img width="1623" alt="Screenshot 2024-10-25 at 9 27 58 PM" src="https://github.com/user-attachments/assets/466c6203-b389-4ccc-b075-92a17efc7e69">
