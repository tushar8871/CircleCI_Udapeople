In this project, you will prove your mastery of the following learning objectives:

Explain the fundamentals and benefits of CI/CD to achieve, build, and deploy automation for cloud-based software products.
Utilize Deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes.
Utilize a configuration management tool to accomplish deployment to cloud-based servers.
Surface critical server errors for diagnosis using centralized structured logging.
Diagram of CI/CD Pipeline we will be building.

Instructions
Selling CI/CD
Getting Started
Deploying Working, Trustworthy Software
Configuration Management
Turn Errors into Sirens
Project Submission
For your submission, please submit the following:

A text file named urls.txt including:

Public Url to GitHub repository (not private) [URL01]
Public URL for your S3 Bucket (aka, your green candidate front-end) [URL02]
Public URL for your CloudFront distribution (aka, your blue production front-end) [URL03]
Public URLs to deployed application back-end in EC2 [URL04]
Public URL to your Prometheus Server [URL05]
Your screenshots in JPG or PNG format, named using the screenshot number listed in the instructions. These screenshots should be included in your code repository in the root folder.

Job failed because of compile errors. SCREENSHOT01
Job failed because of unit tests. SCREENSHOT02
Job that failed because of vulnerable packages. SCREENSHOT03
An alert from one of your failed builds. SCREENSHOT04
Appropriate job failure for infrastructure creation. SCREENSHOT05
Appropriate job failure for the smoke test job. SCREENSHOT06
Successful rollback after a failed smoke test. SCREENSHOT07
Successful promotion job. SCREENSHOT08
Successful cleanup job. SCREENSHOT09
Only deploy on pushed to master branch. SCREENSHOT10
Provide a screenshot of a graph of your EC2 instance including available memory, available disk space, and CPU usage. SCREENSHOT11
Provide a screenshot of an alert that was sent by Prometheus. SCREENSHOT12
Your presentation should be in PDF format named "presentation.pdf" and should be included in your code repository root folder.

Before you submit your project, please check your work against the project rubric. If you haven’t satisfied each criterion in the rubric, then revise your work so that you have met all the requirements.

Built With
Circle CI - Cloud-based CI/CD service
Amazon AWS - Cloud services
AWS CLI - Command-line tool for AWS
CloudFormation - Infrastrcuture as code
Ansible - Configuration management tool
Prometheus - Monitoring tool