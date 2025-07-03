# aws-cloudformation-automation-lab
AWS CloudFormation Lab - Automating Infrastructure Deployment and Teardown (EC2, VPC, S3)
# AWS CloudFormation Automation Lab 🚀

This repository documents a hands-on lab exercise demonstrating **automated infrastructure provisioning and deletion** using **AWS CloudFormation**.

## 🏗️ Lab Overview

We created a CloudFormation stack that deployed the following AWS resources:
- A **Virtual Private Cloud (VPC)** with subnets
- An **Internet Gateway**
- A **Web Server (EC2 instance)** hosted in a public subnet
- A **Security Group** allowing HTTP/SSH access
- An **S3 Bucket**

We then used CloudFormation to **delete all resources**—demonstrating Infrastructure as Code (IaC) lifecycle management.

## 🔧 Technologies Used

- **AWS CloudFormation**
- **EC2 (Elastic Compute Cloud)**
- **VPC, Subnets, and Internet Gateway**
- **S3 (Simple Storage Service)**
- **IAM Roles and Permissions**

## 📷 Lab Evidence

Check the `/screenshots` folder for:
- Stack creation steps
- EC2 public IP and connectivity
- Deletion process (including `DELETE_FAILED` and manual cleanup)
- Final GitHub push

## 📘 Lessons Learned

- Importance of dependency management during resource deletion
- How to troubleshoot `DELETE_FAILED` using the CloudFormation Events tab
- Manual steps sometimes required to clean up public IPs or internet gateways before stack removal

## 📂 Folder Structure


## 📌 Status

✅ **Lab Complete** – All resources created and successfully deleted via CloudFormation (with minor manual adjustments).

---

🧠 *For recruiters or cloud learners: this lab showcases practical skills in IaC using AWS-native tooling.*

