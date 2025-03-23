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

# AWS Artifact

## What is it?

A central resource for compliance-related information that provides on-demand access to AWS security and compliance documents and agreements.

## Key Functions

- Provides downloadable AWS security and compliance documentation
- Offers access to AWS ISO certifications, SOC reports, and PCI reports
- Enables review and acceptance of agreements with AWS
- Allows management of agreements for multiple accounts
- Helps demonstrate AWS infrastructure compliance to auditors

# AWS Pricing Calculator

## What is it?

A web-based planning tool that provides cost estimates for AWS services based on your anticipated usage patterns.

## Key Functions

- Creates detailed AWS cost estimates before deployment
- Allows configuration of service parameters to match expected usage
- Organizes estimates by groups for different use cases or projects
- Provides itemized breakdowns of costs per service
- Supports sharing estimates via unique URLs
- Helps compare different deployment scenarios and their costs

# Amazon Macie

## What is it?

A security service that uses machine learning to automatically discover, classify, and protect sensitive data stored in AWS, particularly in S3 buckets.

## Key Functions

- Automatically discovers and reports sensitive data (PII, credentials, financial data)
- Continuously monitors data access activity for anomalies
- Creates an inventory of S3 buckets with sensitivity scoring
- Generates detailed reports of findings
- Integrates with AWS Security Hub for centralized security management
- Provides automated remediation options through EventBridge
- Helps maintain compliance with regulations like GDPR, HIPAA, and PCI

# AWS Global Accelerator

## What is it?

A networking service that improves the availability and performance of applications by using the AWS global network to optimize the path from users to applications.

## Key Functions

- Routes traffic through AWS's global network instead of the public internet
- Provides static IP addresses that serve as fixed entry points to applications
- Automatically redirects traffic to healthy endpoints during failures
- Reduces latency by connecting users to the nearest edge location
- Improves availability with instant failover between AWS Regions
- Works with EC2 instances, Elastic IP addresses, ALBs, and NLBs
- Enables blue/green deployment testing and weighted routing

# AWS Config

## What is it?

A service that enables you to assess, audit, and evaluate the configurations of your AWS resources for compliance monitoring, resource management, and security analysis.

## Key Functions

- Records configuration changes to AWS resources over time
- Evaluates resources against desired configurations using rules
- Provides detailed configuration history of resources
- Enables compliance auditing and security analysis
- Stores configuration snapshots that can be used for troubleshooting
- Integrates with other services like CloudTrail for comprehensive monitoring
- Supports multi-account, multi-region data aggregation
