# spotify-data-engineering-project

### Introduction
In this project, we'll create an ETL pipeline on AWS using the Spotify API. The pipeline will get daily trending song data from the Spotify API as a JSON file, convert it to the appropriate format, and put it into an AWS data store.

### Architecture Diagram
![Architecture Diagram](https://github.com/Keshavpatta/spotify-data-engineering-project/blob/main/Flow_diagram.jpg)

### Services Used

1. **S3(Simple Storage Servic) :** Amazon S3 is an object storage service offering industry-leading scalability, data availability, security, and performance. S3 is built to store and retrieve any amount of data from anywhere. Customers of all sizes and industries can store and protect any amount of data for virtually any use case, such as data lakes, cloud-native applications, and mobile applications.

2. **AWS Lambda :** AWS Lambda is an event-driven, serverless computing platform provided by Amazon as a part of Amazon Web Services. It is designed to enable developers to run code without provisioning or managing servers. It executes code in response to events and automatically manages the computing resources required by that code.

3. **Cloud Watch :** Amazon CloudWatch is a service that monitors applications, responds to performance changes, optimizes resource use, and provides insights into operational health. By collecting data across AWS resources, CloudWatch gives visibility into system-wide performance and allows users to set alarms, automatically react to changes, and gain a unified view of operational health.
