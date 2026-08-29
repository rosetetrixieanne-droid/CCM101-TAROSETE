# Cloud Provider Comparison

## Checkpoint 4 - Research the Major Cloud Providers

Cloud providers offer similar infrastructure services, but each provider uses different names and technologies for these services. This comparison focuses on four important infrastructure components: compute, storage, networking, and identity and access management (IAM).

## Cloud Infrastructure Services Comparison

| Infrastructure Component | AWS | Microsoft Azure | Google Cloud Platform |
|---|---|---|---|
| **Compute** | **Amazon EC2 (Elastic Compute Cloud)** - Provides scalable virtual servers that can be used to run applications and workloads. | **Azure Virtual Machines** - Provides scalable virtual machines that give users control over their computing environment. | **Compute Engine** - Provides scalable virtual machines and bare-metal instances for running workloads. |
| **Storage** | **Amazon S3 (Simple Storage Service)** - Provides scalable object storage for storing and protecting data. | **Azure Storage / Blob Storage** - Provides scalable storage for objects, files, disks, queues, and tables. | **Cloud Storage** - Provides scalable and managed object storage using buckets. |
| **Networking** | **Amazon VPC (Virtual Private Cloud)** - Provides an isolated virtual network where AWS resources can communicate securely. | **Azure Virtual Network (VNet)** - Provides private networking for Azure resources such as virtual machines and allows communication with the internet and on-premises networks. | **Virtual Private Cloud (VPC)** - Provides global, scalable, and flexible networking for Google Cloud resources such as Compute Engine and GKE. |
| **Identity and Access Management (IAM)** | **AWS IAM** - Controls who can access AWS resources and what actions they are allowed to perform. | **Microsoft Entra ID / Azure RBAC** - Manages identities and controls access to Azure resources through roles and permissions. | **Google Cloud IAM** - Controls which users, groups, and service accounts can access Google Cloud resources and what permissions they have. |

The services above perform similar infrastructure functions even though their names and implementations are different. AWS uses Amazon EC2, S3, VPC, and IAM; Azure uses Virtual Machines, Azure Storage, Virtual Network, and Microsoft Entra ID/Azure RBAC; while Google Cloud uses Compute Engine, Cloud Storage, VPC, and Google Cloud IAM. [1][2][3]

---

## Guide Questions

### 1. Which cloud provider offers the broadest range of services? Explain your answer.

**Amazon Web Services (AWS)** is generally considered to offer one of the broadest ranges of cloud services. AWS documentation states that it provides **over 200 services** covering areas such as compute, storage, databases, analytics, networking, security, and developer tools. [1]

### 2. Which cloud platform would you recommend for an organization that primarily uses Microsoft products? Why?

I would recommend **Microsoft Azure** because it integrates closely with Microsoft's products and services. Azure works with Microsoft technologies such as Windows, Microsoft 365, Microsoft Entra ID, and other Microsoft enterprise services, making it a convenient choice for organizations already using the Microsoft ecosystem. [4]

### 3. Which platform is widely recognized for Artificial Intelligence (AI), Machine Learning (ML), and Kubernetes services?

**Google Cloud Platform (GCP)** is widely recognized for its strong AI, machine learning, and Kubernetes capabilities. Google Cloud provides **Vertex AI** for building, training, and deploying machine learning models and **Google Kubernetes Engine (GKE)** for running containerized applications using Kubernetes. [5][6]

### 4. What similarities did you observe among the three cloud providers?

All three cloud providers offer the same major categories of infrastructure services, including compute, storage, networking, and identity and access management. They also provide scalable and managed resources that allow organizations to run applications without having to purchase and maintain all of the underlying physical infrastructure themselves. [1][2][3]

---


## References

[1] Amazon Web Services. *Overview of Amazon Web Services*. AWS Documentation.

[2] Microsoft. *Azure Documentation*. Microsoft Learn.

[3] Google Cloud. *Google Cloud Documentation*. Google Cloud.

[4] Microsoft. *Azure Integration with Microsoft 365*. Microsoft Learn.

[5] Google Cloud. *Vertex AI Documentation*. Google Cloud.

[6] Google Cloud. *Google Kubernetes Engine*. Google Cloud Documentation.
