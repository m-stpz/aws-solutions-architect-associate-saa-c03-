# Simulate attempt 1

9. A company stores millions of documents in Amazon S3 and needs to identify which buckets contain personally identifiable information (PII) such as names, addresses, and credit card numbers. The security team wants a managed service that discovers, classifies, and reports sensitive data without building custom scanning jobs. Which service should the solutions architect recommend?

- My answer:
  - Amazon inspector: wrong
    - why?
      - inspector assesses vulnerabilities in compute workloads and container images, no s3 data classification

- Correct:
  - Macie
    - uses managed ML and pattern matching to discover and classify sensitive data such as PII in s3, and generates findings for reviews

- Other alternatives
  - AWS config: evaluates resource config compliance, not the contents of s3 objects
  - Amazon GuardDuty: detects threats and anomalous behavior. It doesn't discover/classify PII in s3 objects

> Use Macie for managed sensitive-data discovery and PII classification in S3

11. A company wants organization-wide visibility into Amazon S3 storage usage, activity trends, and cost optimization opportunities across all of its accounts. Which S3 feature provides this visibility with aggregated dashboards and metrics?

- My answer:
  - Trusted advisor: wrong
    - provides best-practice checks, but it's not a detailed s3 usage and activity analytics service

- Correct:
  - Storage lens: provides organization-wide dashboards and metrics for storage usage, and cost optimization across accounts

- Other alternatives:
  - AWS CloudTrail data events: records API activity for auditing. It's not an S3 storage usage and cost analytics service
  - S3 inventory: provides object listing for a bucket, not organization-wise usage dashboards or cost recommendations

> Use s3 storage lens for organization-wise s3 usage, activity, and cost-optimization visibility

20. A public web application on EC2 instances was working. A security engineer then added a network ACL to the public subnet that allows inbound TCP 443 from the internet and outbound TCP 443 to the internet, but denies all other traffic. Clients can now establish TCP connections, but HTTPS responses never arrive. What is the most likely cause and fix?

- My answer

- Correct

- Other alternatives

>

N.

- My answer

- Correct

- Other alternatives

>

N.

- My answer

- Correct

- Other alternatives

>
