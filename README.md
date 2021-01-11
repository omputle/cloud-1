# cloud-1

### Aim of the project
The aim of this project was to introduce the student to Cloud Computing by having them host a wordress website on a clod platform like AWS Cloud services, Google Cloud Services or Microsoft Azure Cloud Services.

## Technologies used
I used AWS Elastic Beanstalk to create the web environment for the project. AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling web applications and services. You can simply upload your code and Elastic Beanstalk automatically handles the deployment, from capacity provisioning, load balancing, auto-scaling to application health monitoring. [Click Here](https://aws.amazon.com/elasticbeanstalk/) to read more on AWS Elastic Beanstalk.

For servers, Amazon EC2 (Elastic Compute Cloud) was used. [Click here to read more](https://aws.amazon.com/ec2/)

For data manangement, RDS (Relational Database Service) was used. [Click here to read more](https://aws.amazon.com/rds/)

To store images, Amazon S3 (Simple Storage Service) was used. [Click here to read more](https://aws.amazon.com/s3/)

### Project Requirements
- Application must run constantly on at least two servers.
- In case of hardware failure of an instance, another instance must automatically go up. 
- CSS loaded from a CDN.