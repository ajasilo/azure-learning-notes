# Day 01 – Introduction to Cloud Concepts (Azure)

## What I Learned
- **Servers and Data Centers**: Applications like Instagram or Gmail run on servers. Traditionally, companies built their own **data centers**, requiring high costs, maintenance, and dedicated system administrators.  
- **Private Cloud**: Infrastructure owned and operated by a single organization (on-premises). Common in banks or organizations with sensitive data.  
- **Public Cloud**: Cloud providers (Azure, AWS, GCP) own global data centers and offer resources to anyone with an account. Cost-effective and scalable.  
- **Hybrid Cloud**: A mix of public and private cloud—used when sensitive data must remain on-premises but other workloads can run on the public cloud.  

## Key Concepts
- **Virtualization**: Splitting one powerful physical server into multiple **virtual machines (VMs)** using a hypervisor.  
- **API (Application Programming Interface)**: Allows programmatic access to cloud services (e.g., requesting 100 VMs via script instead of clicking manually).  
- **Regions & Availability Zones**: Data centers are grouped into regions; each region has multiple availability zones for high availability and redundancy.  
- **Load Balancer**: Distributes requests across multiple servers to ensure performance and failover support.  

## Cloud Features
- **Scalability**: Infrastructure can scale up/down based on demand (manual or auto).  
- **Elasticity**: Dynamic scaling (auto-scaling) when traffic spikes.  
- **High Availability**: Designing applications to stay online most of the time (e.g., multiple replicas across zones).  
- **Disaster Recovery**: Backup and recovery strategies to handle failures, often storing data in another region.  

## Reflection
Day 1 was about understanding **fundamental cloud concepts** (public, private, hybrid, virtualization, APIs, scalability, HA, DR).  
These serve as prerequisites before diving into hands-on Azure services. This foundation will make the next steps (like creating an Azure account and provisioning resources) much easier.  
