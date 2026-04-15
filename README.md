# AWS S3 Static Website Hosting

## Project Overview
This project demonstrates how to host a static website using Amazon S3 without using servers.

## AWS Services Used
- Amazon S3
- Bucket Policy
- Static Website Hosting

## Architecture
User → Internet → Amazon S3 → Static Website

## Steps Performed
1 Created S3 Bucket
2 Disabled Block Public Access
3 Uploaded index.html
4 Enabled Static Website Hosting
5 Configured Bucket Policy
6 Hosted the website publicly

## Bucket Policy Used

{
  "Version":"2012-10-17",
  "Statement":[{
      "Effect":"Allow",
      "Principal":"*",
      "Action":["s3:GetObject"],
      "Resource":["arn:aws:s3:::siddesh-aws-static-website/*"]
  }]
}

## What I Learned
- How S3 works
- Static website hosting
- Bucket permissions
- Public access configuration
- Serverless architecture

## My AWS Learning Progress

Project 1
EC2 Web Server Deployment ✅

Project 2
S3 Static Website Hosting ✅

Project 3
AWS CI/CD Pipeline – Automated Website Deployment
