
# AWS S3 + CloudFront Static Website

## Project Overview
This project demonstrates how to host a static website using Amazon S3 and distribute website content globally using Amazon CloudFront.

## AWS Services Used
- Amazon S3
- Amazon CloudFront
- Origin Access Control (OAC

## Project Structure

```plaintext
cloudfront-project/
│
├── index.html
├── style.css
└── README.md
```

## Project Architecture

```plaintext
User Browser
    |
    v
CloudFront Distribution
    |
    v
Origin Access Control
    |
    v
Private Amazon S3 Bucket
    |
    v
index.html and style.css
```

## Features
- Static website hosting
- Private S3 bucket
- CloudFront content delivery
- HTTPS support
- CloudFront caching
- Cache invalidation

## Deployment Steps
1. Created an S3 bucket.
2. Uploaded HTML and CSS files.
3. Created CloudFront distribution.
4. Configured Origin Access Control.
5. Updated S3 bucket policy.
6. Tested website using CloudFront URL.
7. Practiced cache invalidation.

## Technologies
- HTML
- CSS
- AWS S3
- AWS CloudFront

## Learning Outcome
Learned how to host and distribute static websites using AWS CloudFront and Amazon S3.
