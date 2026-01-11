AWS DEPLOYEMENT PROOF 

AWS Cloud-Hosted Static Portal (Cloud Challenge Winner)
🏆 Project Overview
This repository contains the documentation and architectural details for my successful deployment during a college-level AWS Cloud Challenge, where I secured 3rd Prize. The objective was to move from local development to a live, production-grade cloud environment using a strictly Linux-based workflow.

🚀 Proof of Work (Verified Console Data)
Since the compute resources have been manually Stopped to optimize cloud costs, the following metadata from the live deployment phase serves as the technical record:

AWS Instance ID: i-0304632065c9d9214

Public IPv4 Address: 3.110.104.180

Instance Type: t3.micro

Region: ap-south-1 (Mumbai)

Availability Zone: ap-south-1a

**

🛠️ Tech Stack & Infrastructure

Compute: Amazon EC2 (Linux-based distribution).


Storage: Amazon S3 for static asset hosting and backup redundancy.


Workflow: Linux Command Line (SSH), Security Group configuration, and Public DNS mapping.

💻 Implementation Log
Environment Provisioning: Launched and configured a t3.micro instance within the Mumbai region, ensuring correct VPC and Subnet alignment.

Linux Workflow: Used CLI for system package updates and web server environment setup.

Vibe-Coding Integration: Leveraged AI-assisted development cycles to rapidly iterate on infrastructure configuration and network troubleshooting.

Security & Networking: Configured inbound rules for HTTP traffic on Port 80 while restricting administrative access to personal SSH keys.

💰 Cost Optimization & Lifecycle Management
Note on Current Status: Archived. As a professional best practice for managing personal cloud resources, I follow a "Deploy-Validate-Archive" cycle. After the deployment was validated by the challenge judges, I manually Stopped the instance to prevent unnecessary resource consumption and billing cycles.
