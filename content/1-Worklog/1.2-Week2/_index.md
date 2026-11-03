---
title: "Week 2 Worklog"
date: 2026-11-03
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Week 2 Objectives:

* Understand AWS Identity and Access Management (IAM) and its role in securing AWS resources.
* Understand the fundamental concepts of Amazon Virtual Private Cloud (VPC) and AWS networking.
* Learn how to create and configure a custom VPC with public and private subnets.
* Understand how EC2 instances communicate within a VPC and access the Internet.
* Learn how to manage AWS networking resources using both the AWS Management Console and AWS CLI.
* Apply basic AWS security practices, including Security Groups, Network ACLs, IAM Roles, and the Principle of Least Privilege.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - Learn about AWS Identity and Access Management (IAM). <br> - Understand the following concepts: <br>&emsp; + IAM Users and Groups <br>&emsp; + IAM Roles <br>&emsp; + IAM Policies <br>&emsp; + Multi-Factor Authentication (MFA) <br>&emsp; + Principle of Least Privilege <br> - **Practice:** <br>&emsp; + Explore IAM Dashboard. <br>&emsp; + Review IAM Users, Roles, and Policies. <br>&emsp; + Check MFA configuration. | 03/11/2026 | — | [AWS Study Group – IAM](https://cloudjourney.awsstudygroup.com/vi/) |
| 3 | - Learn the fundamentals of Amazon VPC. <br> - Understand the following concepts: <br>&emsp; + VPC and CIDR <br>&emsp; + Public and Private Subnets <br>&emsp; + Availability Zones <br>&emsp; + Internet Gateway (IGW) <br>&emsp; + Route Tables <br>&emsp; + NAT Gateway <br> - **Practice:** <br>&emsp; + Explore the Default VPC. <br>&emsp; + Review existing VPC networking components. <br>&emsp; + Draw a basic VPC architecture diagram. | 04/11/2026 | — | [AWS Study Group – VPC](https://cloudjourney.awsstudygroup.com/vi/) |
| 4 | - Learn how to create and configure a custom VPC. <br> - Understand network routing and subnet configuration. <br> - **Practice:** <br>&emsp; + Create a custom VPC (CIDR: 10.0.0.0/16). <br>&emsp; + Create a Public Subnet (10.0.1.0/24). <br>&emsp; + Create a Private Subnet (10.0.2.0/24). <br>&emsp; + Create and attach an Internet Gateway. <br>&emsp; + Configure Route Tables for the public subnet. <br>&emsp; + Explore Security Groups and Network ACLs. | 05/11/2026 | — | [The First Cloud Journey](https://cloudjourney.awsstudygroup.com/vi/) |
| 5 | - Learn how to deploy EC2 instances within a custom VPC. <br> - Understand the relationship between EC2 and VPC networking. <br> - Learn about IAM Roles for EC2. <br> - **Practice:** <br>&emsp; + Launch an EC2 instance in the Public Subnet. <br>&emsp; + Configure Security Group rules. <br>&emsp; + Connect to the EC2 instance via SSH. <br>&emsp; + Explore how IAM Roles grant permissions to EC2 instances. <br>&emsp; + Test network connectivity. | 06/11/2026 | — | [AWS Study Group – EC2 and IAM Roles](https://cloudjourney.awsstudygroup.com/vi/) |
| 6 | - Review AWS IAM and VPC concepts. <br> - Learn the differences between Security Groups and Network ACLs. <br> - Practice managing VPC resources using AWS CLI. <br> - **Practice:** <br>&emsp; + List VPCs, Subnets, and Route Tables using AWS CLI. <br>&emsp; + Retrieve EC2 instance information. <br>&emsp; + Verify network configuration and connectivity. <br>&emsp; + Review security configurations. <br>&emsp; + Clean up unused AWS resources. | 07/11/2026 | — | [AWS Study Group – The First Cloud Journey](https://cloudjourney.awsstudygroup.com/vi/) |

### Week 2 Achievements:

* **AWS IAM Fundamentals:**
  * Understood the role of IAM in managing access to AWS resources.
  * Learned the differences between IAM Users, Groups, Roles, and Policies.
  * Understood MFA and the Principle of Least Privilege.

* **AWS Networking Fundamentals:**
  * Understood the concept and purpose of Amazon VPC.
  * Learned the main networking components:
    * VPC and CIDR.
    * Public and Private Subnets.
    * Internet Gateway (IGW).
    * Route Tables.
    * NAT Gateway.
    * Security Groups and Network ACLs.

* **VPC Hands-on Practice:**
  * Explored the default VPC configuration.
  * Created and configured a custom VPC.
  * Configured public and private subnets.
  * Attached an Internet Gateway and configured route tables.
  * Tested basic network connectivity.

* **EC2 and IAM Role Practice:**
  * Launched an EC2 instance within a custom VPC.
  * Configured Security Groups and SSH access.
  * Explored IAM Roles for EC2 instances.
  * Practiced basic network troubleshooting.

* **AWS CLI Practice:**
  * Retrieved information about VPCs, subnets, and route tables.
  * Managed and inspected AWS resources using AWS CLI.
  * Reinforced the ability to use AWS Console and CLI together.

* **General Skills & Takeaways:**
  * Improved understanding of AWS networking, security, and infrastructure management.
  * Gained practical experience in designing and configuring basic cloud network infrastructure.
