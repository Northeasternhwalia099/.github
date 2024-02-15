Infrastructure Design and CloudFormation
I designed a scalable and highly available infrastructure using CloudFormation templates for a REST API service. This involved creating a robust and dynamic environment that can automatically adjust to the changing demands of the application, ensuring both scalability and reliability. The use of CloudFormation allowed for defining the entire infrastructure in code, making the setup and deployment processes more efficient and repeatable.

Service Discovery and Monitoring
For service discovery and DNS mappings, I employed AWS Route 53, which provided a reliable and cost-effective way to route end-users to Internet applications. Additionally, I integrated Amazon Simple Email Service (SES) for handling user-verification emails, enhancing the security and integrity of the user registration process. To monitor application performance and log metrics, I utilized Amazon CloudWatch. This enabled the creation of alarms based on the application's exceptions, ensuring immediate notification and swift resolution of any issues.

Continuous Integration and Deployment (CI/CD)
A significant achievement was establishing a Continuous Integration and Continuous Deployment (CI/CD) pipeline using GitHub Actions. This pipeline was responsible for building Amazon Machine Images (AMIs), triggering AWS Lambda functions, generating artifacts, and deploying the web application. The implementation of this CI/CD pipeline significantly reduced deployment time by 60%, streamlining the development process and enabling more frequent and reliable releases.
