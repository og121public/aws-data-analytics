# AWS Data Analytics domains:

### 1. Collection
### 2. Storage and Data Management
### 3. Processing
### 4. Analysis and Visualization
### 5. Security
-   ---------------
##  1: Collection
### 1.1: operational characteristics of the collection system.
- data loss is within tolerance limits in the event of failures.
- costs associated with data acquisition, transfer, and provisioning
    from various sources into the collection system (for example,
    networking, bandwidth, ETL, data migration).
- failure scenarios that the collection system may experience, and
    take remediation actions based on impact.
- data persistence at various points of data capture.
- latency characteristics of the collection system.

### 1.2: collection system that handles the frequency, volume, and source of data.
- volume and flow characteristics of incoming data.
- flow characteristics of data to potential solutions.
- tradeoffs between various ingestion services, and take into account
    scalability, cost, fault tolerance, and latency.
- throughput capability of a variety of types of data collection
    solutions, and identify bottlenecks.
- collection solution that satisfies connectivity constraints of the
    source data system.

### 1.3: collection system that addresses the key properties of data, such as order, format, and compression.
- capture data changes at the source.
- data structure and format, compression applied, and encryption
    requirements.
- impact of out-of-order delivery of data, duplicate delivery of data,
    and the tradeoffs between at-most-once, exactly-once, and at-least-
    once processing.
- transform and filter data during the collection process.
##  2: Storage and Data Management
### 2.1: operational characteristics of the storage solution for analytics.
- appropriate storage service or services on the basis of cost
    compared to performance.
- durability, reliability, and latency characteristics of the storage
    solution based on requirements.
- requirements of a system for strong or eventual consistency of the
    storage system.
- appropriate storage solution to address data freshness requirements.

### 2.2: appropriate data access and retrieval patterns.
- appropriate storage solution based on update patterns (for example,
    bulk, transactional, micro batching).
- appropriate storage solution based on access patterns (for example,
    sequential or random access, continuous usage or one-time usage).
- appropriate storage solution to address change characteristics of
    data (append-only changes or updates).
- appropriate storage solution for long-term storage and transient
    storage.
- appropriate storage solution for structured data and semi-
    structured data.
- appropriate storage solution to address query latency requirements.

### 2.3: appropriate data layout, schema, structure, and format.
- appropriate mechanisms to address schema evolution requirements.
- appropriate storage format for a specific task.
- appropriate compression and encoding strategies for a chosen storage
    format.
- appropriate data sorting and distribution strategies and the storage
    layout for efficient data access.
- cost and performance implications of different data distributions,
    layouts, and formats (for example, size and number of files).
- data formatting and partitioning schemes for data-optimized
    analysis.

### 2.4: data lifecycles based on usage patterns and business requirements.
- appropriate strategy to address data lifecycle requirements.
- appropriate lifecycle and data retention policies to different
    storage solutions.

### 2.5: appropriate system to catalog data and to manage metadata.
- mechanisms to discover new and updated data sources.
- mechanisms to create and update data catalogs and metadata.
- mechanisms to search and retrieve data catalogs and metadata.
- mechanisms to tag and classify data.
##  3: Processing
### 3.1: appropriate data processing solution requirements.
- data preparation and usage requirements.
- different types of data sources and targets.
- performance and orchestration needs.
- appropriate services for cost, scalability, and availability.

### 3.2: solution to transform and prepare data for analysis.
- appropriate ETL and ELT techniques for batch workloads and real-
    time workloads.
- failover, scaling, and replication mechanisms.
- techniques to address concurrency needs.
- techniques to improve cost-optimization efficiencies.
- orchestrate workflows.
- aggregate and enrich data for downstream consumption.

### 3.3: automate and operationalize data processing solutions.
- automated techniques for repeatable workflows.
- methods to identify and recover from processing failures.
- logging and monitoring solutions to enable auditing and
    traceability.
##  4: Analysis and Visualization
### 4.1: operational characteristics of an analysis and visualization
solution.
- costs associated with analysis and visualization.
- scalability associated with analysis.
- failover recovery and fault tolerance within the RPO and RTO.
- availability characteristics of an analysis tool.
- dynamic, interactive, and static presentations of data.
- performance requirements of an appropriate visualization approach
    (for example, pre-compute and consume static data, consume dynamic
    data).

### 4.2: appropriate data analysis solution for a given scenario.
- compare analysis solutions.
- right type of analysis based on the customer use case (for example,
    streaming, interactive, collaborative, operational).

### 4.3: appropriate data visualization solution for a given scenario.
- output capabilities for a given analysis solution (for example,
    metrics, KPIs, tabular, API).
- appropriate method for data delivery (for example, web, mobile,
    email, collaborative notebooks).
- define the appropriate data refresh schedule.
- appropriate tools for different data freshness requirements (for
    example, Amazon OpenSearch Service, Amazon QuickSight, Amazon EMR
    notebooks).
- capabilities of visualization tools for interactive use cases (for
    example, drill down, drill through, pivot).
- appropriate data access mechanism (for example, in memory, direct
    access).
- integrated solution from multiple heterogeneous data sources.
##  5: Security
### 5.1: appropriate authentication and authorization mechanisms.
- appropriate authentication methods (for example, federated access,
    SSO, AWS Identity and Access Management \[IAM\]).
- appropriate authorization methods (for example, policies, ACLs,
    table and column level permissions).
- appropriate access control mechanisms (for example, security groups,
    role-based controls).

### 5.2: data protection and encryption techniques.
- data encryption and masking needs.
- different encryption approaches (for example, server-side
    encryption, client-side encryption, AWS Key Management Service \[AWS
    KMS\], AWS CloudHSM).
- at-rest and in-transit encryption mechanisms.
- data obfuscation and masking techniques.
- basic principles of key rotation and secrets management.

### 5.3: data governance and compliance controls.
- data governance and compliance requirements.
- configure access, and audit logging across data analytics services.
- appropriate controls to meet compliance requirements.
## IN-SCOPE AWS services and features
#### Analytics
- Amazon Athena
- Amazon CloudSearch
- Amazon EMR
- AWS Glue
- Amazon Kinesis
- AWS Lake Formation
- Amazon Managed Streaming for Apache Kafka (Amazon MSK)
- Amazon OpenSearch Service
- Amazon QuickSight
#### Application Integration
- Amazon MQ
- Amazon Simple Notification Service (Amazon SNS)
- Amazon Simple Queue Service (Amazon SQS)
- AWS Step Functions
#### Compute
- AWS Auto Scaling
- Amazon EC2
- AWS Lambda
#### Database
- Amazon DocumentDB (with MongoDB compatibility)
- Amazon DynamoDB
- Amazon ElastiCache
- Amazon Neptune
- Amazon RDS
- Amazon Redshift
- Amazon Timestream
#### Frontend Web and Mobile
- Amazon API Gateway
- AWS AppSync
- Amazon Simple Email Service (Amazon SES)
#### Management and Governance
- AWS CloudFormation
- AWS CloudTrail
- Amazon CloudWatch
- AWS Trusted Advisor
#### Machine Learning
- Amazon SageMaker
#### Migration and Transfer
- AWS Database Migration Service (AWS DMS)
- AWS DataSync
- AWS Snowball
- AWS Transfer Family
#### Networking and Content Delivery
- AWS Direct Connect
- Elastic Load Balancing (ELB)
- Amazon VPC
#### Security, Identity, and Compliance
- AWS Artifact
- AWS Certificate Manager (ACM)
- AWS CloudHSM
- Amazon Cognito
- AWS IAM Identity Center (successor to AWS Single Sign-On)
- AWS Identity and Access Management (IAM)
- AWS Key Management Service (AWS KMS)
- Amazon Macie
- AWS Secrets Manager
#### Storage
- Amazon Elastic Block Store (Amazon EBS)
- Amazon S3
- Amazon S3 Glacier