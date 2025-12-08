---
title: "Week 3 Worklog"
date: 2025-09-10
weight: 1
chapter: false
pre: " <b> 1.3. </b> "
---

### Week 3 Objectives:

* Learn about methods to connect VPCs and on-premises networks:
  * VPC Peering - direct connection between two VPCs
  * Transit Gateway - centralized connection for multiple VPCs
  * Direct Connect Gateway - dedicated connection from on-premises
  * VPN Site-to-Site - VPN connection from on-premises network
  * VPN Client-to-Site - VPN connection for individual clients

* Master the types of Load Balancers in AWS:
  * Application Load Balancer (ALB)
  * Network Load Balancer (NLB)
  * Classic Load Balancer (CLB)
  * Gateway Load Balancer (GWLB)

* Practice creating and configuring EC2 instances with advanced features.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --------- | ------------ | --------------- | -------------- |
| 2   | - Learn about VPC Peering <br> - Learn about Transit Gateway | 09/15/2025 | 09/15/2025 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> <br> <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Learn about Direct Connect Gateway <br> - Learn about VPN Site to Site: <br>&emsp; + Virtual Private Gateway <br>&emsp; + Customer Gateway <br> - Learn about VPN Client to Site | 09/23/2025 | 09/23/2025 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> <br> <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Learn about Elastic Load Balancing: <br>&emsp; + Application Load Balancer <br>&emsp; + Network Load Balancer <br>&emsp; + Classic Load Balancer <br>&emsp; + Gateway Load Balancer | 09/24/2025 | 09/24/2025 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> <br> <https://cloudjourney.awsstudygroup.com/> |
| 5   | - **Practice:** <br>&emsp; + Create and configure EC2 instance <br>&emsp; + Test connectivity between instances | 09/25/2025 | 09/25/2025 | <https://000003.awsstudygroup.com/> |
| 6   | - **Practice:** <br>&emsp; + Create Multi-AZ NAT Gateway <br>&emsp; + Create EC2 Instance Connect Endpoint | 09/26/2025 | 09/26/2025 | <https://000003.awsstudygroup.com/> |


### Week 3 Achievements:

* **Clear understanding of advanced VPC connectivity methods:**
  * **VPC Peering:** Learned how to directly connect two VPCs to allow private network traffic
  * **Transit Gateway:** Understood how to use Transit Gateway as a central hub for multiple VPCs and on-premises networks
  * **Direct Connect Gateway:** Mastered how to establish dedicated connections from on-premises networks to AWS

* **Mastered VPN methods on AWS:**
  * **VPN Site-to-Site:** Understood how to connect entire on-premises network with VPC
    * Virtual Private Gateway (VGW)
    * Customer Gateway (CGW)
  * **VPN Client-to-Site:** Learned how to allow individual clients to securely connect to VPC

* **Proficient in Elastic Load Balancing:**
  * **Application Load Balancer (ALB):** Understood how to use for web applications, with URL/hostname-based routing
  * **Network Load Balancer (NLB):** Learned how to use for ultra-high performance and low latency traffic
  * **Classic Load Balancer (CLB):** Understood basic load balancer type for legacy applications
  * **Gateway Load Balancer (GWLB):** Mastered how to use for virtual appliances

* **Successfully practiced with EC2:**
  * Created and configured EC2 instances with appropriate settings
  * Tested network connectivity between EC2 instances
  * Deployed Multi-AZ architecture to ensure high availability
  * Created NAT Gateway to allow instances to connect outbound
  * Used EC2 Instance Connect Endpoint for secure access

* **Comprehensive knowledge:**
  * Understood how to design complex connectivity infrastructure on AWS
  * Mastered how to choose appropriate connectivity methods for each use case
  * Learned how to load balance and optimize application performance
