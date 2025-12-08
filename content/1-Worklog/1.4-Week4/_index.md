---
title: "Week 4 Worklog"
date: 2025-09-10
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---

### Week 4 Objectives:

* Learn about Route 53 - DNS service and domain management on AWS
* Master AWS CloudFormation - Infrastructure as Code (IaC) tool for automating resource deployment
* Learn about AWS Directory Service - centralized directory management service
* Learn about AWS Quick Starts - rapid deployment templates
* Practice setting up Hybrid DNS with Route 53 Resolver
* Practice setting up VPC Peering with Cross-Peer DNS enabled
* Practice deploying AWS Transit Gateway (TGW) with attachments and route tables

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --------- | ------------ | --------------- | -------------- |
| 2   | - Learn about Route 53 <br> - Learn about AWS Quick Starts <br> - Learn about AWS CloudFormation <br> - Learn about AWS Directory Service | 09/29/2025 | 09/29/2025 | <https://000010.awsstudygroup.com/vi/> <br> <https://000037.awsstudygroup.com/vi/> |
| 3   | - **Practice:** Setting up Hybrid DNS with Route 53 Resolver <br>&emsp; + Create keypair <br>&emsp; + Initialize CloudFormation Template <br>&emsp; + Configure Security Group <br>&emsp; + Connect to Remote Desktop Gateway (RDGW) server <br>&emsp; + Deploy Microsoft AD <br>&emsp; + Setup DNS <br>&emsp; + Clean up resources | 09/30/2025 | 09/30/2025 | <https://000010.awsstudygroup.com/vi/> |
| 4   | - **Practice:** Setting up VPC Peering <br>&emsp; + Initialize CloudFormation Template <br>&emsp; + Create Security Group and EC2 Instance <br>&emsp; + Update Network ACL <br>&emsp; + Create Peering connection <br>&emsp; + Enable Cross-Peer DNS <br>&emsp; + Clean up resources | 10/01/2025 | 10/01/2025 | <https://000019.awsstudygroup.com/vi/> |
| 5   | - Learn more about Transit Gateway (TGW): <br>&emsp; + TGW Attachment <br>&emsp; + TGW Policy Tables <br>&emsp; + TGW Route Tables <br>&emsp; + TGW Multicast | 10/02/2025 | 10/02/2025 | <https://000020.awsstudygroup.com/vi/> |
| 6   | - **Practice:** AWS Transit Gateway Overview <br>&emsp; + Initialize CloudFormation Template <br>&emsp; + Create Transit Gateway <br>&emsp; + Create Transit Gateway Attachment <br>&emsp; + Create Transit Gateway Route Table <br>&emsp; + Add Transit Gateway Routes to VPC Route Tables <br>&emsp; + Clean up resources | 10/03/2025 | 10/03/2025 | <https://000020.awsstudygroup.com/vi/> |


### Week 4 Achievements:

* **Mastered DNS and management services on AWS:**
  * **Route 53:** Understood how to use fully managed DNS service by AWS
  * **Route 53 Resolver:** Learned how to set up Hybrid DNS to connect on-premises and AWS DNS
  * Understood how to manage domains and DNS records

* **Deep understanding of Infrastructure as Code (IaC):**
  * **AWS CloudFormation:** Mastered how to use templates to automate and manage AWS resources
  * Learned how to write CloudFormation templates to deploy complex architectures
  * Understood main components: Resources, Parameters, Outputs, Conditions

* **Learned about resource management:**
  * **AWS Directory Service:** Understood how to use centralized directory management service
  * **AWS Quick Starts:** Learned how to leverage available rapid deployment templates

* **Successfully practiced Hybrid DNS Setup:**
  * Created keypair for Remote Desktop Gateway (RDGW)
  * Deployed CloudFormation template to automate configuration
  * Configured appropriate Security Groups
  * Deployed Microsoft AD on AWS
  * Set up DNS Resolver for Hybrid connection
  * Cleaned up resources after completion

* **Successfully practiced VPC Peering:**
  * Created Security Groups and EC2 instances for VPCs
  * Updated Network ACL to allow traffic
  * Created VPC Peering connection between VPCs
  * Enabled Cross-Peer DNS resolution
  * Tested connectivity between VPCs

* **Successfully practiced Transit Gateway:**
  * Understood Transit Gateway components: Attachments, Route Tables, Routes
  * Deployed Transit Gateway using CloudFormation
  * Created Transit Gateway attachments for VPC
  * Configured Transit Gateway route tables
  * Added routes to VPC route tables to route through TGW
  * Tested connectivity through Transit Gateway

* **Comprehensive knowledge:**
  * Learned how to choose between VPC Peering and Transit Gateway for different scenarios
  * Understood how to set up complex multi-VPC network architecture
  * Gained ability to automate deployment using CloudFormation
