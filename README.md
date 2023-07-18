# AWS
## Storage Services

AWS provides the folloiwing storage services:

**EBS** (Elastic Block Store) - it is a block-level storage service offered by AWS that provides highly available, low-latency block-level storage volumes for use with EC2 instances. EBS volumes are designed for use with a single EC2 instance, and they can be attached and detached as needed. [More information](#elastic-block-storage-ebs)

**EFS** (Elastic File System) - it is a fully-managed, highly scalable file storage service that provides a simple and scalable file system for use with EC2 instances. EFS is designed to support multiple EC2 instances simultaneously, making it ideal for use cases where multiple instances need to access a shared file system. [More information](#elastic-file-system-efs)

**FSx**  -provides you with the native compatibility of third-party file systems with feature sets for workloads such as Windows-based storage, high-performance computing (HPC), machine learning, and electronic design automation (EDA). [More information](#amazon-fsx)

**S3** (Simple Storage Service) - it is a highly scalable, durable, and secure object storage service offered by AWS. S3 allows users to store and retrieve any amount of data from anywhere on the web and provides industry-leading scalability, data availability, security, and performance. It can be used for a wide range of use cases, including data lakes, backup and archive, and content distribution. [More information](#simple-storage-service-s3)

This services could be categorized by [Block](https://aws.amazon.com/what-is/block-storage/), [File](https://aws.amazon.com/what-is/cloud-file-storage/) and [Object](https://aws.amazon.com/what-is/object-storage/) storage type.

<br>

![](images/main-qimg-5f3b66e058df8c4addc876556757d276.png)

<br>

## Elastic Block Storage (EBS)

<img src="images/aws-ec2-smaller-partitioned-root-volume.png" width="400">

Amazon Elastic Block Store (EBS) is an easy to use, high-performance, block-storage service designed for use with Amazon Elastic Compute Cloud (EC2) for both throughput and transaction intensive workloads at any scale. A broad range of workloads, such as relational and non-relational databases, enterprise applications, containerized applications, big data analytics engines, file systems, and media workflows are widely deployed on Amazon EBS.

You can choose from six different volume types to balance optimal price and performance. You can achieve single-digit-millisecond latency for high-performance database workloads such as SAP HANA or gigabyte per second throughput for large, sequential workloads such as Hadoop. You can change volume types, tune performance, or increase volume size without disrupting your critical applications, so you have cost-effective storage when you need it.

Designed for mission-critical systems, EBS volumes are replicated within an Availability Zone (AZ) and can easily scale to petabytes of data. Also, you can use EBS Snapshots with automated lifecycle policies to back up your volumes in Amazon S3, while ensuring geographic protection of your data and business continuity.

For more information, see [EBS](ebs.md) module.

<br>


## Elastic File System (EFS)

<img src="images/efs-1.png" width="600">

**Amazon EFS** is an AWS file sharing service that lets you manage file shares, like those used on traditional networks, and mount them on cloud or on-premises machines using the **NFSv4 protocol**.

It is a scalable, cloud-based file system for Linux-based applications and workloads that can be used in combination with AWS cloud services and on-premise resources.

For more information, see [EFS](efs.md) module.

<br>


## Amazon FSx

Amazon FSx provides fully managed third-party file systems.

Amazon FSx provides you with the native compatibility of third-party file systems with feature sets for workloads such as Windows-based storage, high-performance computing (HPC), machine learning, and electronic design automation (EDA).

You don’t have to worry about managing file servers and storage, as Amazon FSx automates the time-consuming administration tasks such as hardware provisioning, software configuration, patching, and backups.

Amazon FSx integrates the file systems with cloud-native AWS services, making them even more useful for a broader set of workloads.

![](images/fsx-logo.png)

For more information, see [Amazone FSx](fsx.md) module.

<br>


## Simple Storage Service (S3)

<img src="images/s3-3.png" width="200">

**Amazon Simple Storage Service**, widely known as **Amazon S3**, is a highly scalable, fast, and durable solution for object-level storage of any data type. Unlike the operating systems we are all used to, Amazon S3 does not store files in a file system, instead it stores files as objects. Object Storage allows users to upload files, videos, and documents like you were to upload files, videos, and documents to popular cloud storage products like Dropbox and Google Drive. This makes Amazon S3 very flexible and platform agnostic.

For more information, see [S3](s3.md) module.

<br>
