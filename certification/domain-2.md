---
label: Domain 2
---

:::banner
The following domain objectives are derived from the [AWS Certified Solutions Architect - Associate (SAA-C03) Exam Guide](https://d1.awsstatic.com/training-and-certification/docs-sa-assoc/AWS-Certified-Solutions-Architect-Associate_Exam-Guide.pdf){ target="_blank" }.
:::

# Domain 2: Design Resilient Architectures

## Task Statement 1: Design scalable and loosely coupled architectures.

Knowledge of:

- API creation and management
  - [Amazon API Gateway](/products/api-gateway.md)
  - REST API
- AWS managed services with appropriate use cases
  - AWS Transfer Family
  - [Amazon Simple Queue Service [Amazon SQS]](/products/sqs.md)
  - Secrets Manager
- Caching strategies
- Design principles for microservices (for example, stateless workloads compared with stateful workloads)
- Event-driven architectures
- Horizontal scaling and vertical scaling
- How to appropriately use edge accelerators (for example, content delivery network [CDN])
- How to migrate applications into containers
- Load balancing concepts
  - Application Load Balancer
- Multi-tier architectures
- Queuing and messaging concepts (for example, publish/subscribe)
- Serverless technologies and patterns
  - [AWS Fargate](/products/fargate.md)
  - [AWS Lambda](/products/lambda.md)
- Storage types with associated characteristics (for example, object, file, block)
- The orchestration of containers
  - [Amazon Elastic Container Service [Amazon ECS]](/products/ecs.md)
  - [Amazon Elastic Kubernetes Service [Amazon EKS]](/products/eks.md)
- When to use read replicas
- Workflow orchestration
  - AWS Step Functions

Skills in:

- Designing event-driven, microservice, and/or multi-tier architectures based on requirements
- Determining scaling strategies for components used in an architecture design
- Determining the AWS services required to achieve loose coupling based on requirements
- Determining when to use containers
- Determining when to use serverless technologies and patterns
- Recommending appropriate compute, storage, networking, and database technologies based on requirements
- Using purpose-built AWS services for workloads

## Task Statement 2: Design highly available and/or fault-tolerant architectures.

Knowledge of:

- AWS global infrastructure
  - Availability Zones
  - AWS Regions
  - [Amazon Route 53](/products/route53.md)
- AWS managed services with appropriate use cases
  - Amazon Comprehend
  - Amazon Polly
- Basic networking concepts (for example, route tables)
- Disaster recovery (DR) strategies (for example, backup and restore, pilot light, warm standby, active-active failover, recovery point objective [RPO], recovery time objective [RTO])
- Distributed design patterns
- Failover strategies
- Immutable infrastructure
- Load balancing concepts
  - Application Load Balancer
- Proxy concepts
  - Amazon RDS Proxy
- Service quotas and throttling (for example, how to configure the service quotas for a workload in a standby environment)
- Storage options and characteristics (for example, durability, replication)
- Workload visibility
  - AWS X-Ray

Skills in:

- Determining automation strategies to ensure infrastructure integrity
- Determining the AWS services required to provide a highly available and/or fault-tolerant architecture across AWS Regions or Availability Zones
- Identifying metrics based on business requirements to deliver a highly available solution
- Implementing designs to mitigate single points of failure
- Implementing strategies to ensure the durability and availability of data (for example, backups)
- Selecting an appropriate DR strategy to meet business requirements
- Using AWS services that improve the reliability of legacy applications and applications not built for the cloud (for example, when application changes are not possible)
- Using purpose-built AWS services for workloads