
# Deploying web app using lambda serverless

## Problem Statement

The cost and complexity of traditional online application hosting are increased by the requirement to manage servers, scale infrastructure, and handle operational overhead. Deploying a serverless web application with AWS Lambda and Amazon S3 that does away with server management, automatically scales with demand, provides high availability, and stays affordable while securely providing both static and dynamic content is a challenge.

## AWS Services Used
- S3
- Lambda serverless

## Architecture Overview
(attach diagram)


## Security Considerations
- IAM roles

## High Availability
- AWS Lambda is a multi-Availability Zone service, making it highly available.

## Cost Optimization
- Used AWS Lambda’s pay-per-use model to avoid idle server costs
- Used API Gateway HTTP APIs for lower request costs.
- Reduced compute load and hosting costs by serving static assets directly from S3.
- Avoided fixed infrastructure costs by using only on-demand AWS services.
