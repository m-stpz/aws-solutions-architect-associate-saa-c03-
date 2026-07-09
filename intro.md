# Intro

- AWS Solutions Architect Exam [SAA-C03]
- AWS (Amazon Web Services) cloud provider that provides servers/services on demand and easily scalable

Some services

- AWS EC2
- ECR
- ECS
- AWS Elastic Beanstalk
- AWS Lambda
- Auto Scaling
- IAM
- AWS KMS
- S3
- SES
- RDS
- Aurora
- DynamoDB
- ElastiCache
- SQS
- SNS
- AWS Step functions
- CloudWatch
- CloudFormation
- CloudTrail
- API Gateway
- Elastic Load Balancing
- CloudFront
- Kinesis
- Route 53

## History

- 2002: Internally launched
- 2003: Amazon infra is one of their core strength. Idea to market
- 2004: Launched publicly with SQS
- 2006: Relaunched with SQS, S3 & EC2
- 2007: Launched in Europe

## AWS Global Infrastructure

- AWS Regions
- AWS Availability Zones
- AWS Data Centers
- AWS Edge Locations/Points of presence

https://aws.amazon.com/about-aws/global-infrastructure/regions_az/

- How to choose an AWS Region?
  - Compliance: data governance and legal requirements
  - Proximity to customers: reduced latency
  - Available services within a region
  - Pricing: it varies from region to region

- AWS Availability zones
  - Each region has zones (usually 3 - min 3/max 6)
  - Each availability zone (AZ) is one or more discrete data centers with redundant power, networking, and connectivity
  - Each zone is separate from each other, so they're separated from disasters
  - They're connected with high bandwidth, ultra-low latency networking

- AWS Points of presence (Edge locations)
  - 400+ points of present (400+ edge locations & 10+ regional caches)
  - 90+ cities across 40+ countries
  - Content is delivered to users with lower latency

- AWS has global services
  - Identity and Acess Management (IAM)
  - Route 53 (DNS service)
  - CloudFront (CDN)
  - WAT (Web application firewall)

- Most AWS services are region-scoped:
  - Amazon EC2 (Infrastructure as a service)
  - Elastic Beanstalk (Platform as a service)
  - Lambda (Function as a service)
  - Rekognition (Software as a service)
