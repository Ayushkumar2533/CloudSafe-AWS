# CloudSafe – Project Screenshots & Evidence

This folder contains screenshots captured during the development, configuration, and testing of the CloudSafe – Secure Cloud File Storage & Recovery System built on Amazon Web Services (AWS).

These images provide visual evidence of the major AWS services and security features implemented in the project, including secure storage, access control, versioning, recovery, monitoring, and cost optimization.

---

## Project Overview

CloudSafe is designed to securely store files in the cloud while ensuring data protection, recoverability, and operational visibility. The project uses AWS services to provide a robust storage environment with controlled access and auditing features.

### Key Features
- Secure file storage using Amazon S3
- Data recovery through S3 versioning
- Access control and permissions through AWS IAM
- Monitoring and auditing using AWS CloudTrail
- Storage lifecycle management for cost efficiency

---

## 1. S3 Bucket Creation

**File:** `s3_bucket.jpeg`

This screenshot shows the Amazon S3 bucket created for the CloudSafe project. Amazon S3 serves as the primary cloud storage service for storing files as objects.

**Purpose:**
- Provides object-based cloud storage
- Stores project files securely
- Acts as the central storage component of CloudSafe

**AWS Service:** Amazon S3

---

## 2. S3 Versioning Enabled

**File:** `versioning_enabled.jpeg`

This screenshot shows that S3 Versioning has been enabled for the CloudSafe bucket.

Versioning allows Amazon S3 to keep multiple versions of an object, which helps protect stored data from accidental modification or deletion.

**Purpose:**
- Preserves previous versions of files
- Protects against accidental overwrites
- Enables file recovery and rollback
- Supports the backup and restoration capability of CloudSafe

**AWS Service:** Amazon S3 – Versioning

---

## 3. Multiple Object Versions

**File:** `multiple_versions.jpeg`

This screenshot demonstrates that multiple versions of an object are stored in the S3 bucket.

When versioning is enabled, older versions of files remain available even after updates or deletions. This is a key part of the project’s recovery strategy.

**Purpose:**
- Shows version history
- Demonstrates preservation of previous versions
- Supports restoration of earlier file states

**AWS Service:** Amazon S3 – Versioning

---

## 4. Accidental File Deletion and Recovery

**File:** `accidental_file-deletion.jpeg`

This screenshot highlights the testing of accidental file deletion in the CloudSafe S3 bucket.

With S3 Versioning enabled, a deletion does not necessarily remove the object permanently. Previous versions can be restored, making the system resilient to accidental data loss.

**Purpose:**
- Simulates accidental deletion
- Validates data recovery mechanisms
- Demonstrates the reliability of the storage setup

**AWS Service:** Amazon S3 – Versioning

---

## 5. S3 Lifecycle and Cost Optimization

**File:** `lifecycle_cost-optimization.jpeg`

This screenshot shows the lifecycle configuration applied to the CloudSafe bucket.

Amazon S3 lifecycle rules automatically manage objects over time, helping optimize storage costs by moving data to more cost-effective storage classes based on usage and retention rules.

**Purpose:**
- Automates storage management
- Reduces long-term storage costs
- Improves efficiency and scalability

**AWS Service:** Amazon S3 – Lifecycle Management

---

## 6. IAM Access Control

**File:** `IAM_Access_control.jpeg`

This screenshot shows the AWS IAM configuration used to manage access to cloud resources in the CloudSafe project.

AWS Identity and Access Management (IAM) allows the project to define who can access specific resources and what actions they are allowed to perform. This is essential for enforcing security and least-privilege access.

**Purpose:**
- Controls access to AWS resources
- Enforces least-privilege permissions
- Improves cloud security
- Restricts unauthorized access

**AWS Service:** AWS IAM

---

## 7. CloudTrail Testing and Audit Visibility

**File:** `cloudtrail_testing.jpeg`

This screenshot shows AWS CloudTrail activity and testing for the CloudSafe environment.

CloudTrail records AWS API calls and account activity, providing visibility into user and system actions. This helps with monitoring, auditing, troubleshooting, and incident investigation.

**Purpose:**
- Tracks user and system activity
- Provides audit visibility
- Supports security analysis
- Helps monitor cloud operations

**AWS Service:** AWS CloudTrail

---

## Screenshot Summary

| Screenshot | AWS Service | Demonstrated Function |
|-----------|------------|----------------------|
| `s3_bucket.jpeg` | Amazon S3 | Secure cloud object storage |
| `versioning_enabled.jpeg` | S3 Versioning | Data protection through version control |
| `multiple_versions.jpeg` | S3 Versioning | Multiple versions of stored objects |
| `accidental_file-deletion.jpeg` | S3 Versioning | Recovery from accidental deletion |
| `lifecycle_cost-optimization.jpeg` | S3 Lifecycle | Cost-effective storage lifecycle management |
| `IAM_Access_control.jpeg` | AWS IAM | Identity and access management |
| `cloudtrail_testing.jpeg` | AWS CloudTrail | Activity logging and auditing |

---

## CloudSafe AWS Workflow

The project follows a simple yet effective cloud workflow:

User/File → Amazon S3 → S3 Versioning → Recovery

Additional security and optimization layers:
- AWS IAM → Access Control
- S3 Lifecycle → Cost Optimization
- AWS CloudTrail → Monitoring and Audit

---

## Conclusion

These screenshots collectively demonstrate the core AWS components and security practices used in the CloudSafe project. They provide visual evidence of secure storage, data recovery, access control, monitoring, and lifecycle optimization.

This documentation helps reflect the implementation quality and the practical use of AWS services in building a secure and reliable cloud storage system.

---

## Note

These screenshots represent the AWS configuration and testing performed during the CloudSafe project and are included as project evidence and technical documentation.
