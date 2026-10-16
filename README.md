# Task 16: Create a Cloud Storage Bucket Using Amazon S3

## Overview

This project was completed as part of the Veda Technology Cloud Computing Internship (Task 16). The objective was to create an Amazon S3 bucket and upload sample objects to understand the fundamentals of cloud object storage.

## Aim

To create an object-storage bucket in Amazon S3 and upload sample files, including text documents and images.

## Objectives

- Understand the fundamentals of cloud object storage.
- Create and configure an Amazon S3 bucket.
- Upload and verify at least five objects.
- Understand common uses of cloud storage and basic storage security.

## Tools and Services

- Amazon Web Services (AWS)
- Amazon Simple Storage Service (Amazon S3)
- AWS Management Console
- GitHub for project documentation

## Bucket Configuration

|    Setting       |               Value                    |
|------------------|----------------------------------------|
| Bucket name      | `veda-task16-cloud-storage-pooja-2026` |
| AWS Region       | Asia Pacific (Mumbai)                  |
| Region code      | `ap-south-1`                           |
| Storage class    | S3 Standard                            |
| Uploaded objects | 5                                      |
| Upload result    | 5 succeeded, 0 failed                  |

## Implementation Steps

1. Signed in to the AWS Management Console.
2. Opened Amazon S3 and selected the Mumbai region (`ap-south-1`).
3. Created the bucket `veda-task16-cloud-storage-pooja-2026`.
4. Prepared three sample text files and two sample images.
5. Uploaded the five files to the S3 bucket.
6. Verified that all five objects appeared in the bucket's Objects tab.
7. Confirmed the upload status showed five successful uploads and zero failures.

## Uploaded Objects

|          Object name         |    Type    |
|------------------------------|------------|
| `aws-s3-notes.txt`           | Text file  |
| `cloud-storage-overview.txt` | Text file  |
| `cloud-storage-workflow.jpg` | JPEG image |
| `cloud-storage-workflow.txt` | Text file  |
| `sample-image.jpg`           | JPEG image |

## Evidence Screenshots

The following screenshots document the implementation:

1. `01_Bucket_Created.png` — Successful S3 bucket creation.
2. `02_Upload_Success.png` — Upload status showing five successful uploads and zero failures.
3. `03_Bucket_Contents.png` — The five objects visible in the bucket.

Screenshots will be added to this repository to provide visual evidence of the completed task.

## Security Considerations

- Keep the bucket private unless public access is explicitly required.
- Retain S3 Block Public Access settings.
- Avoid uploading sensitive or confidential information.
- Use appropriate access permissions and encryption settings.
- Review AWS resource usage to avoid unexpected charges.

**Note:** Verify the bucket's actual permissions and encryption settings in the AWS Console before documenting them as confirmed configurations.

## Interview Questions

### 1. What is object storage?

Object storage stores data as individual objects. Each object contains the data, a unique key, and metadata. Amazon S3 is an object-storage service designed to store and retrieve data at scale.

### 2. How is object storage different from VM storage?

Object storage stores data as objects in a storage service accessed through APIs or compatible interfaces. Virtual machine storage typically provides block devices or attached disks that an operating system can partition and format into a file system. Object storage is well suited to unstructured data, backups, media, and application files.

### 3. What are common uses of cloud object storage?

Common uses include backups, archival data, images, videos, documents, static website assets, application files, logs, and data used for analytics.

## Result

An Amazon S3 bucket was successfully created in the Mumbai region, and five sample objects were uploaded. The AWS Console confirmed that all five uploads succeeded, and the bucket contents were verified.

## Conclusion

This task provided practical experience with creating an Amazon S3 bucket, uploading objects, and verifying stored files. It demonstrated the basic workflow of cloud object storage and the importance of appropriate access controls and cost awareness.

