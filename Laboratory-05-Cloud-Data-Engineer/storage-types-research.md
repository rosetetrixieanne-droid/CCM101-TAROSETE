# Cloud Storage Types Research

## Comparison of Cloud Storage Types

| Storage Type   | Description                                                                             | Primary Use Case                                                                           | Cloud Provider Example |
| -------------- | --------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ | ---------------------- |
| Block Storage  | Stores data in fixed-size blocks that can be accessed individually.                     | Best for virtual machines, databases, and applications that need fast storage access.      | AWS EBS                |
| File Storage   | Stores data as files in folders and directories that can be shared by multiple systems. | Best for shared files, documents, and applications that need a common file system.         | AWS EFS                |
| Object Storage | Stores data as objects together with metadata and a unique identifier.                  | Best for photos, videos, backups, documents, and other large amounts of unstructured data. | AWS S3                 |

## Why Object Storage is Suitable for the Client

Object Storage is a good choice for the client's photo-sharing application because it is designed to store large amounts of unstructured data such as images. It can also scale as the number of uploaded photos increases, making it suitable for a system that may eventually store millions of user-uploaded images.
