# AWS Static Website Hosting using S3 and CloudFront

## Project Overview

This project demonstrates how to host a static website using Amazon S3 and deliver it globally using Amazon CloudFront CDN. The goal of this project is to gain hands-on experience with AWS storage, content delivery networks, and basic cloud architecture.

## AWS Services Used

* Amazon S3
* Amazon CloudFront
* AWS IAM

## Technologies Used

* HTML
* CSS
* CloudFront CDN

## Architecture

User → CloudFront CDN → S3 Static Website

## Implementation Steps

### 1. Create S3 Bucket

* Created an S3 bucket to store website files.

### 2. Upload Website Files

* Uploaded index.html and other assets to the S3 bucket.

### 3. Enable Static Website Hosting

* Enabled static website hosting in S3.
* Configured index document as index.html.

### 4. Configure Bucket Policy

* Added bucket policy to allow public read access.

### 5. Create CloudFront Distribution

* Configured CloudFront distribution with the S3 website endpoint as origin.

### 6. Test Website

* Accessed the website through the CloudFront domain.

## Project Screenshots

### Architecture Diagram

![Architecture](screenshots/architecture-diagram.pn)

### S3 Bucket

s3-bucket.png

### Static Website Hosting

static-website-hosting.png

### Bucket Policy

bucket-policy.png

### CloudFront Distribution

cloudfront-distribution.png

### Website Output

website-output.png

## Learning Outcomes

* Hosting static websites on Amazon S3
* Configuring CloudFront CDN
* Managing bucket policies and permissions
* Understanding cloud content delivery architecture

## Author

Mohammad Rahil
Aspiring Cloud Support Engineer
