---
label: Domain 1
---

:::banner
The following domain objectives are derived from the [AWS Certified Solutions Architect - Associate (SAA-C03) Exam Guide](https://d1.awsstatic.com/training-and-certification/docs-sa-assoc/AWS-Certified-Solutions-Architect-Associate_Exam-Guide.pdf){ target="_blank" }.
:::

# Domain 1: Design Secure Architectures

## Task Statement 1: Design secure access to AWS resources.

Knowledge of:

- Access controls and management across multiple accounts
- AWS federated access and identity services
  - AWS Identity and Access Management [IAM]
  - AWS Single Sign-On [AWS SSO]
- AWS global infrastructure
  - Availability Zones
  - AWS Regions
- AWS security best practices (for example, the principle of least privilege)
- The AWS shared responsibility model

Skills in:

- Applying AWS security best practices to IAM users and root users (for example, multi-factor authentication [MFA])
- Designing a flexible authorization model that includes IAM users, groups, roles, and policies
- Designing a role-based access control strategy
  - AWS Security Token Service [AWS STS]
  - Role switching
  - Cross-account access
- Designing a security strategy for multiple AWS accounts
  - AWS Control Tower
  - Service control policies [SCPs]
- Determining the appropriate use of resource policies for AWS services
- Determining when to federate a directory service with IAM roles

## Task Statement 2: Design secure workloads and applications.

Knowledge of:

- Application configuration and credentials security
- AWS service endpoints
- Control ports, protocols, and network traffic on AWS
- Secure application access
- Security services with appropriate use cases
  - [Amazon Cognito](/products/cognito.md)
  - Amazon GuardDuty
  - Amazon Macie
- Threat vectors external to AWS (for example, DDoS, SQL injection)

Skills in:

- Designing VPC architectures with security components (for example, security groups, route tables, network ACLs, NAT gateways)
- Determining network segmentation strategies (for example, using public subnets and private subnets)
- Integrating AWS services to secure applications
  - AWS Shield
  - [AWS WAF](/products/waf.md)
  - AWS SSO
  - AWS Secrets Manager
- Securing external network connections to and from the AWS Cloud (for example, VPN, AWS Direct Connect)

## Task Statement 3: Determine appropriate data security controls.

Knowledge of:

- Data access and governance
- Data recovery
- Data retention and classification
- Encryption and appropriate key management

Skills in:

- Aligning AWS technologies to meet compliance requirements
- Encrypting data at rest
  - [AWS Key Management Service [AWS KMS]](/products/kms.md)
- Encrypting data in transit
  - [AWS Certificate Manager [ACM]](/products/acm.md) using TLS
- Implementing access policies for encryption keys
- Implementing data backups and replications
- Implementing policies for data access, lifecycle, and protection
- Rotating encryption keys and renewing certificates