# AWS Serverless File Processing Pipeline

## 📌 Project Overview
A serverless pipeline for uploading, processing, and distributing media files using S3, Lambda, and API Gateway.

## ❗ Problem Statement
A media startup needed a scalable, cost-effective way to handle user file uploads and processing without managing servers.

## 🏗️ Architecture
- API Gateway for upload endpoints
- S3 bucket for raw file storage with lifecycle rules
- Lambda functions for image/video processing on file upload
- SNS notifications for processed file delivery
- CloudWatch alarms for Lambda errors

## ✨ Features
- Fully serverless architecture
- Pay-per-use model for cost efficiency
- Automated file processing workflows
- Real-time notifications

## 🚀 Setup Instructions
1. Clone this repo  
2. Deploy resources with SAM or Terraform  
3. Upload files via API Gateway endpoint  
4. Monitor processing through CloudWatch  

## 🛠 AWS Services Used
S3, Lambda, API Gateway, SNS, CloudWatch

## ✅ Outcomes
- Reduced infrastructure costs by 40%
- Scaled seamlessly with user uploads
- Automated processing pipeline with zero manual intervention
