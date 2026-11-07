# Amazon S3 Public Documentation Portfolio

This portfolio organizes my Amazon S3 public documentation work by project and technical problem. AWS documentation is collaboratively maintained, so the links below identify current public artifacts connected to my contributions rather than sole ownership of every current revision.

## S3 Vectors and Vector Buckets

I led and authored documentation from public preview through general availability for Amazon S3 Vectors. The work spanned user-guide architecture, API guidance, security and access management, AWS PrivateLink, CloudFormation resources, code examples, and cross-service integrations.

- [S3 Vectors overview](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-vectors.html)
- [Getting started with S3 Vectors](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-vectors-getting-started.html)
- [Vector buckets](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-vectors-buckets.html)
- [Vector indexes](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-vectors-indexes.html)
- [Working with vectors](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-vectors-vectors.html)
- [Querying vectors with AWS CLI and SDK for Python examples](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-vectors-query.html)
- [Listing vectors with AWS CLI and SDK for Python examples](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-vectors-list.html)
- [S3 Vectors best practices](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-vectors-best-practices.html)
- [Integrations with other AWS services](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-vectors-integration.html)
- [Amazon OpenSearch Service integration](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-vectors-opensearch.html)
- [Amazon Bedrock Knowledge Bases integration](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-vectors-bedrock-kb.html)
- [Security in S3 Vectors](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-vectors-security.html)
- [Identity and access management](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-vectors-access-management.html)
- [Data protection and encryption](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-vectors-data-encryption.html)
- [VPC endpoints and AWS PrivateLink](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-vectors-privatelink.html)
- [Regions, endpoints, and quotas](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-vectors-regions-quotas.html)
- [S3 Vectors API operations](https://docs.aws.amazon.com/AmazonS3/latest/API/API_Operations_Amazon_S3_Vectors.html)
- [S3 Vectors CloudFormation resource reference](https://docs.aws.amazon.com/AWSCloudFormation/latest/TemplateReference/AWS_S3Vectors.html)
- CloudFormation resources: [Index](https://docs.aws.amazon.com/AWSCloudFormation/latest/TemplateReference/aws-resource-s3vectors-index.html), [VectorBucket](https://docs.aws.amazon.com/AWSCloudFormation/latest/TemplateReference/aws-resource-s3vectors-vectorbucket.html), and [VectorBucketPolicy](https://docs.aws.amazon.com/AWSCloudFormation/latest/TemplateReference/aws-resource-s3vectors-vectorbucketpolicy.html)

## S3 Express One Zone and Directory Buckets

I authored launch, API, user-guide, security, and performance content for S3 Express One Zone and directory buckets. I also developed public Java SDK examples and integration tests covering directory-bucket operations.

- [Directory buckets overview](https://docs.aws.amazon.com/AmazonS3/latest/userguide/directory-buckets-overview.html)
- [Getting started with S3 Express One Zone](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-express-getting-started.html)
- [Differences for directory buckets](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-express-differences.html)
- [Optimizing S3 Express One Zone performance](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-express-optimizing-performance-design-patterns.html)
- [Security for directory buckets](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-express-security.html)
- [Authentication and authorization](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-express-authenticating-authorizing.html)
- [IAM authorization](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-express-security-iam.html)
- [Directory bucket API operations](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-express-APIs.html)
- [AWS SDK examples for directory buckets](https://docs.aws.amazon.com/code-library/latest/ug/s3-directory-buckets_example_s3-directory-buckets_Scenario_ExpressBasics_section.html)
- [Java SDK examples and integration tests](https://github.com/awsdocs/aws-doc-sdk-examples/pull/7109)
- [Documentation-subchapter tooling contribution](https://github.com/awsdocs/aws-doc-sdk-examples-tools/pull/118)
- [Public repository documentation update](https://github.com/awsdocs/aws-doc-sdk-examples/pull/7162)

## API Reliability, Permissions, and Operational Guidance

This work focused on making API behavior, constraints, permissions, errors, billing behavior, and operational requirements explicit and usable by developers and automated tools.

- [PutObject API constraints](https://docs.aws.amazon.com/AmazonS3/latest/API/API_PutObject.html#PutObject-constraints)
- [Required permissions for Amazon S3 API operations](https://docs.aws.amazon.com/AmazonS3/latest/userguide/using-with-s3-policy-actions.html)
- [Charges for failed requests](https://docs.aws.amazon.com/AmazonS3/latest/userguide/ErrorCodeBilling.html)
- [HeadObject API](https://docs.aws.amazon.com/AmazonS3/latest/API/API_HeadObject.html)
- [Requester Pays buckets](https://docs.aws.amazon.com/AmazonS3/latest/userguide/RequesterPaysBuckets.html)
- [CreateBucket errors](https://docs.aws.amazon.com/AmazonS3/latest/API/API_CreateBucket.html#API_CreateBucket_Errors)
- [GetObject errors](https://docs.aws.amazon.com/AmazonS3/latest/API/API_GetObject.html#API_GetObject_Errors)
- [Presigned URLs and object integrity](https://docs.aws.amazon.com/AmazonS3/latest/userguide/using-presigned-url.html)
- [Bucket naming rules](https://docs.aws.amazon.com/AmazonS3/latest/userguide/bucketnamingrules.html)
- [Delete-marker behavior](https://docs.aws.amazon.com/AmazonS3/latest/userguide/DeleteMarker.html)

## Security and Encryption

I authored launch and corrective guidance for secure-by-default storage, encryption choices, permissions, and public-access controls.

- [Server-side encryption](https://docs.aws.amazon.com/AmazonS3/latest/userguide/serv-side-encryption.html)
- [Default bucket encryption](https://docs.aws.amazon.com/AmazonS3/latest/userguide/default-bucket-encryption.html)
- [Using AWS KMS encryption](https://docs.aws.amazon.com/AmazonS3/latest/userguide/UsingKMSEncryption.html)
- [Default encryption FAQ](https://docs.aws.amazon.com/AmazonS3/latest/userguide/default-encryption-faq.html)
- [Specifying DSSE-KMS](https://docs.aws.amazon.com/AmazonS3/latest/userguide/specifying-dsse-encryption.html)
- [Blocking public access](https://docs.aws.amazon.com/AmazonS3/latest/userguide/access-control-block-public-access.html)

## S3 Object Lambda and Applied Tutorials

These projects translated multi-service architectures into reproducible tutorials with implementation steps and code.

- [Transforming data with S3 Object Lambda](https://docs.aws.amazon.com/AmazonS3/latest/userguide/tutorial-s3-object-lambda-uppercase.html)
- [Detecting and redacting PII with Amazon Comprehend](https://docs.aws.amazon.com/AmazonS3/latest/userguide/tutorial-s3-object-lambda-redact-pii.html)
- [Hosting on-demand streaming video](https://docs.aws.amazon.com/AmazonS3/latest/userguide/tutorial-s3-cloudfront-route53-video-streaming.html)
- [Batch-transcoding videos with S3 Batch Operations, Lambda, and MediaConvert](https://docs.aws.amazon.com/AmazonS3/latest/userguide/tutorial-s3-batchops-lambda-mediaconvert-video.html)
- [Creating S3 Object Lambda Access Points](https://docs.aws.amazon.com/AmazonS3/latest/userguide/olap-create.html)
- [Transforming objects with S3 Object Lambda](https://docs.aws.amazon.com/AmazonS3/latest/userguide/transforming-objects.html)

## S3 Select, Inventory, and Storage Analytics

I authored and improved technical guidance for querying object data, inventory reporting, storage observability, and interactions between storage features.

- [S3 Select error responses](https://docs.aws.amazon.com/AmazonS3/latest/API/ErrorResponses.html#SelectObjectContentErrorCodeList)
- [S3 Select conditional expressions](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-glacier-select-sql-reference-conditional.html)
- [S3 Select aggregate functions](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-select-sql-reference-aggregate.html)
- [S3 Select expressions](https://docs.aws.amazon.com/AmazonS3/latest/userguide/s3-select-sql-reference-select.html)
- [Amazon S3 Inventory](https://docs.aws.amazon.com/AmazonS3/latest/userguide/storage-inventory.html)
- [Restricting access to an S3 Inventory report](https://docs.aws.amazon.com/AmazonS3/latest/userguide/example-bucket-policies.html#example-bucket-policies-s3-inventory)
- [S3 Storage Lens metrics glossary](https://docs.aws.amazon.com/AmazonS3/latest/userguide/storage_lens_metrics_glossary.html)
- [S3 Intelligent-Tiering](https://docs.aws.amazon.com/AmazonS3/latest/userguide/intelligent-tiering-overview.html)

## S3 on Outposts, Private Connectivity, and Multi-Region Architecture

These projects documented hybrid-cloud operations, regional behavior, endpoint selection, replication, and connectivity constraints.

- [S3 on Outposts metrics and capacity](https://docs.aws.amazon.com/AmazonS3/latest/userguide/S3OutpostsCapacity.html)
- [S3 Replication on Outposts](https://docs.aws.amazon.com/AmazonS3/latest/userguide/S3OutpostsReplication.html)
- [ListOutpostsWithS3 API](https://docs.aws.amazon.com/AmazonS3/latest/API/API_s3outposts_ListOutpostsWithS3.html)
- [AWS PrivateLink for Amazon S3](https://docs.aws.amazon.com/AmazonS3/latest/userguide/privatelink-interface-endpoints.html)
- [Multi-Region Access Point restrictions](https://docs.aws.amazon.com/AmazonS3/latest/userguide/MultiRegionAccessPointRestrictions.html)

## Core S3 Onboarding

I recreated or rewrote foundational S3 content and later developed a command-line onboarding workflow.

- [What is Amazon S3?](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html)
- [Getting started with Amazon S3](https://docs.aws.amazon.com/AmazonS3/latest/userguide/getting-started-next-steps.html)
- [Getting started with Amazon S3 using the AWS CLI](https://docs.aws.amazon.com/AmazonS3/latest/userguide/GettingStartedS3CLI.html)
