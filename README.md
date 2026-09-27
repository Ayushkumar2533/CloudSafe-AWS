# CloudSafe – Secure Cloud File Storage & Recovery System

CloudSafe is an AWS-based cloud storage and recovery project developed for a hackathon. The project demonstrates how cloud services can be used to securely store files, maintain previous versions, recover accidentally deleted files, manage storage costs, control access, and monitor cloud activity.

## 🎯 Objectives

* Securely store files in the cloud
* Maintain previous versions of files
* Recover files after accidental deletion
* Manage storage using lifecycle rules
* Control access using IAM
* Monitor and audit cloud activity using CloudTrail

## ☁️ AWS Services Used

### Amazon S3

Used for secure object/file storage.

### S3 Versioning

Maintains previous versions of objects and allows recovery after accidental deletion or modification.

### S3 Lifecycle Management

Used to manage stored objects according to lifecycle rules and help reduce storage costs.

### AWS IAM

Used to manage users, permissions, and access to AWS resources.

### AWS CloudTrail

Used to record and monitor AWS API activity for auditing and security visibility.

## 🔐 Key Features

* Cloud-based file storage
* File versioning
* Accidental deletion recovery
* Lifecycle-based storage management
* Access control using IAM
* Activity auditing using CloudTrail

## 🏗️ Project Architecture

The project uses Amazon S3 as the main storage service. S3 Versioning provides recovery of previous object versions, Lifecycle Management helps manage storage, IAM controls access, and CloudTrail provides audit visibility.

## 🧪 Recovery Test

A test file was uploaded to the S3 bucket and then deleted. With S3 Versioning enabled, the previous version remained available and could be used for recovery.

## 📸 Project Screenshots

Implementation and testing screenshots are available in the `screenshots` folder.

## 📂 Repository Contents

```text
CloudSafe/
│
├── README.md
├── screenshots/
│   ├── AWS project screenshots
│   └── testing evidence
│
└── CloudSafe-Hackathon-Presentation.pptx
```

## 🎓 Hackathon Project

**Project:** CloudSafe
**Problem:** Secure Cloud File Storage & Recovery System
**Platform:** Amazon Web Services (AWS)

## 👨‍💻 Author

Ayush Kumar

This project was created as a cloud computing hackathon project to demonstrate practical implementation of AWS storage, security, recovery, lifecycle management, and auditing concepts.

