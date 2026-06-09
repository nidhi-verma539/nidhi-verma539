☁️ CloudWatch CPU Alerting using Amazon SNS
Sep 2025
Set up automated CPU monitoring and alerting on an EC2 instance using AWS CloudWatch and SNS.
Launched an EC2 instance and ran a CPU spike script to simulate high load
Created a CloudWatch alarm linked to an SNS topic for email notifications
Set the alarm threshold at 50% CPU utilization
Successfully received an email alert when CPU usage crossed the threshold
---
🌐 Deploy a Web Application on EC2 (Jenkins)
Aug 2025
Deployed Jenkins on an EC2 instance and made it accessible from outside AWS.
Launched an EC2 instance and installed Java and Jenkins
Started and enabled the Jenkins service
Opened port 8080 in the EC2 security group
Accessed Jenkins via the EC2 public IP and completed the initial setup using the admin password
---
🗂️ Static Website Hosting on Amazon S3
Aug 2025
Hosted a static website using Amazon S3's built-in static website hosting feature.
Created an S3 bucket and uploaded HTML/CSS/JS files
Enabled Static Website Hosting on the bucket
Configured a bucket policy to allow public read access
Website successfully deployed and accessible via the S3 endpoint URL
---
🟢 Node.js Application Deployment on AWS EC2
Aug 2025
Deployed a Node.js application on an EC2 instance from scratch.
Launched an EC2 instance and configured the server environment
Connected via SSH for secure remote access
Updated packages and installed Git, Node.js, and npm
Cloned the application repository, set environment variables, installed dependencies, and started the app
---
🔗 VPC Peering Between Two AWS VPCs
Aug 2025
Established private network connectivity between two VPCs using VPC Peering.
Created EC2 instances in separate test and prod VPCs
Configured route tables, internet gateways, and the VPC peering connection
Successfully enabled communication between the two VPCs over private IP addresses
---
💰 AWS Cloud Cost Optimization — Identify Stale EBS Snapshots
Apr 2025
Built a Lambda function to automatically identify and delete unused EBS snapshots to reduce storage costs.
Created an AWS Lambda function to scan EBS snapshots
Identified snapshots not associated with any active EC2 instance
Automated deletion of stale snapshots to optimize cloud storage costs
