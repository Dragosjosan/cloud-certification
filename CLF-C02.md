## AWS Cloud Adoption Framework

- Business: makes sure you meet your business targets. Stakeholders: CEO, CFO, COO, CTO
- People:

# AWS Well-Architected Framework

## What is it?

- **Operational Excellence**: Running and monitoring systems
- **Security**: Protecting information and systems
- **Reliability**: Ensuring workloads perform intended functions correctly
- **Performance Efficiency**: Using resources efficiently
- **Cost Optimization**: Avoiding unnecessary costs
- **Sustainability**: Minimizing environmental impacts

## Key Functions

- Provides a consistent approach to evaluate architectures
- Identifies areas for improvement
- Helps implement designs that scale with business needs
- Reduces business risks

# AWS CloudTrail

## What is it?

A service that records API calls made in your AWS account for auditing, compliance, and troubleshooting.

## Key Functions

- Records **who** did **what** actions, **when**, and from **where**
- Stores activity logs in S3
- Monitors and alerts on unusual activity

## Important Details

- Default: 90-day event history (free)
- Trails: For long-term storage beyond 90 days
- Management Events: Administrative operations (default)
- Data Events: High-volume resource operations (S3 object access, Lambda executions)

# Amazon Simple Queue Service (SQS)

## What is it?

A fully managed message queuing service that enables decoupling and scaling of microservices, distributed systems, and serverless applications.
Key Functions

Sends, stores, and receives messages between components
Ensures delivery of each message at least once
Maintains the order of messages (FIFO queues)
Buffers requests when downstream services are unavailable
Supports dead-letter queues for handling failed messages

# AWS Direct Connect

## What is it?

A dedicated network connection service that establishes a private link from your on-premises network directly to AWS, bypassing the public internet.

## Key Functions

- Provides consistent network performance with reduced latency
- Supports private connectivity to Amazon VPC resources
- Reduces bandwidth costs for high-volume data transfer
- Offers connection speeds from 50 Mbps to 100 Gbps
- Enables hybrid cloud architectures with predictable network performance

# AWS Augmented AI (Amazon A2I)

## What is it?

A service that makes it easy to build human review workflows for machine learning applications, enabling human review of low-confidence predictions.

## Key Functions

- Integrates human review for ML model predictions
- Creates custom human review workflows for your ML applications
- Routes low-confidence predictions to human reviewers
- Provides pre-built workflows for Amazon Rekognition and Amazon Textract
- Manages reviewer assignments, instructions, and results

# AWS CloudFront

## What is it?

A global content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers with low latency and high transfer speeds.

## Key Functions

- Caches content at edge locations worldwide
- Accelerates both static and dynamic content delivery
- Integrates with AWS Shield for DDoS protection
- Supports custom SSL certificates for HTTPS
- Provides real-time metrics and logs for monitoring
