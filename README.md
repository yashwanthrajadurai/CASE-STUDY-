# CASE-STUDY-

Case Study Title: Resource Allocation and Cost Optimization in an OpenStack Private Cloud

Case Overview:

ABC Cloud Services runs a private cloud using OpenStack to host virtual machines (VMs) for internal development, testing, and production workloads. Their cloud infrastructure comprises:

5 Compute Nodes, each with:
64 vCPUs
256 GB RAM
2 TB SSD storage
OpenStack Services Deployed:
Nova (Compute)
Neutron (Networking)
Cinder (Block Storage)
Glance (Image Management)
Keystone (Identity)
Horizon (Dashboard)
Heat (Orchestration)

They are considering expanding their cloud but want to first evaluate current capacity usage, VM density, and cost efficiency. The goal is to calculate whether their resource usage aligns with business needs and how to optimize it.

### Problem 1: Encryption Time Calculation
A company uses AES-256 encryption to secure its data before uploading it to the cloud. It takes
0.05 seconds to encrypt 1 MB of data.
Q: How long will it take to encrypt 2 TB of data before upload?
2 TB is equal to 2,000,000 MB (since 1 TB = 1,000,000 MB). If 1 MB takes 0.05 seconds to encrypt,
then 2,000,000 MB will take:
2,000,000 * 0.05 = 100,000 seconds.
That is equivalent to 27.78 hours. So, it will take approximately 27.78 hours to encrypt 2 TB of data.
### Problem 2: CPU Utilization Efficiency
A VM is allocated 8 vCPUs, but only uses 5.5 vCPUs on average.
Q: What is the CPU utilization efficiency?
CPU utilization efficiency is calculated as (used / allocated) * 100.
So, (5.5 / 8) * 100 = 68.75%.
The CPU utilization efficiency is 68.75%.
### Problem 3: Network Throughput Efficiency
A cloud server has a maximum bandwidth of 1 Gbps, but during peak hours it only uses 600 Mbps.
Q: What is the network throughput efficiency?
Throughput efficiency is calculated as (actual usage / maximum capacity) * 100.
So, (600 / 1000) * 100 = 60%.
The network throughput efficiency is 60%.
### Problem 4: Energy Efficiency
Two cloud setups process the same workload:
Setup A uses 500W for 2 hours.
Setup B uses 300W for 3.5 hours.
Q: Which setup is more energy-efficient?
Energy consumed by Setup A = 500W * 2h = 1000 Wh
Energy consumed by Setup B = 300W * 3.5h = 1050 Wh
Since both setups process the same workload, the one consuming less energy is more efficient.
Setup A is more energy-efficient.
### Problem 5: CPU Utilization Efficiency
A physical server has 16 cores and each VM uses 2 cores. CPU utilization is optimal at 75%.
Q: What is the maximum number of VMs that can be efficiently hosted?
Total usable cores at 75% utilization = 16 * 0.75 = 12 cores
Each VM uses 2 cores, so maximum number of VMs = 12 / 2 = 6.
Hence, 6 VMs can be efficiently hosted.
