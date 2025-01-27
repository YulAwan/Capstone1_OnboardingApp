# AWS Cloud Institute Capstone Project

Over 10 labs at **AWS Cloud Institute**, I built a **serverless customer onboarding app** for AnyCompany Bank using AWS services.

The solution automates customer verification using **AI/ML services** like:

- **Rekognition** for facial matching
- **Textract** for extracting data from uploaded documents

It also integrates key AWS services such as:

- **Amazon S3** for secure document storage
- **DynamoDB** for metadata management
- **Lambda** for serverless logic
- **SNS/SQS** for communication and queuing

I built and deployed my Infrastructure as Code (**IaC**) using the **AWS SAM template**.

One critical moment in this project was refactoring the architecture to implement **Step Functions** and the state machine. This was my first experience using Step Functions in a development process, and it was a game-changer. It leverages **parallel states** to process multiple document types asynchronously, ensuring faster performance.

To enhance monitoring and debugging, I also added **AWS X-Ray tracing** to monitor both the Step Functions workflow and individual Lambda functions. This made performance tuning and troubleshooting much more efficient.

Three .zip files contains the samples of documents to test the app.
