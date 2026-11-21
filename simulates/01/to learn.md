# To learn

- Amazon Macie? Other new services I haven't learned on the course?
- partition placement group vs. cluster placement group?
- NACL: what it is, why is it stateless?
- What is RPO?
- What is RTO?
- What is a NAT instance vs. NAT gateway?
- Important S3 services
  - macie
  - aws glue
  - storage lens
  - what else? What other services are processing stuff from s3?

## Amazon Macie

- Fully managed data security and data privacy service that uses ML and pattern matching to automatically discover, classify and protect sensitive data stored in S3
- Scan S3 buckets for PII, without writing a custom regex, go with Macie

## What is RPO? [Recovery point objective - how much data can we lose?]

- Recovery point objective
- Maximum acceptable amount of data loss measured in time when an outage or disaster occurs
- How far back in time we can rollout the data in case of failure. Basically, "how much data can we afford to lose?"
- If you take db backups once every hour, your RPO is 1h

## What is RTO? [Recovery time objective - how long can we be offline?]

- Recovery time objective
- Maximum acceptable amount of downtime after an outage or disaster occurs
- How quickly you must restore your application, infra, and network

## Important S3 services

- See 00. intro/19. S3 services.md
