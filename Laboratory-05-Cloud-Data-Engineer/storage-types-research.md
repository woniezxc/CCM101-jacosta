# Types of Cloud Storage Research

## Comparison Table

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
| :--- | :--- | :--- | :--- |
| **Block Storage** | Splits data into fixed-sized blocks, each with a unique identifier. Operates like a raw, unformatted hard drive connected directly to an OS. | Operating system boot volumes, high-performance databases (e.g., MySQL, PostgreSQL), transactional logging. | AWS Elastic Block Store (EBS) |
| **File Storage** | Stores data in a hierarchical directory structure of files and folders (using protocols like NFS or SMB/CIFS). | Shared file systems, enterprise content management, legacy application migration, shared home directories. | AWS Elastic File System (EFS) |
| **Object Storage** | Stores data as discrete objects containing the file payload, custom metadata, and a globally unique identifier in a flat address space. | Unstructured data storage (photos, videos, audio), web asset hosting, data lakes, backups, disaster recovery. | AWS Simple Storage Service (S3) |

## Client Explanation: Why Object Storage for User-Uploaded Images?

For a photo-sharing application handling millions of user-uploaded images, Object Storage is the optimal choice because it provides infinite horizontal scalability without requiring server disk management or costly storage re-architecting. Containers are ephemeral, making local storage unsuitable for persistent application media. Object Storage allows images to be uploaded, retrieved, and served directly via HTTP/S REST APIs while remaining cost-effective, highly durable, and decoupled from your compute servers.
