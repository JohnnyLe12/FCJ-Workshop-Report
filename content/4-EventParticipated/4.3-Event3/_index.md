---
title: "Event 3"
date: 2025-11-29
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---

# AWS Well-Architected Security Pillar Workshop

**Date:** Saturday, November 29, 2025  
**Time:** 8:30 AM - 12:00 PM 
**Location:** AWS Vietnam Office

---

## Speaker Lineup

### Le Vu Xuan An
**AWS Cloud Club Captain (HCMU/TE)**

Captain of AWS Cloud Club at Ho Chi Minh City University of Technology, specializing in cloud architecture and security.

### Tran Duc Anh
**AWS Cloud Club Captain (SGU)**

Captain of AWS Cloud Club at Saigon University, with experience in AWS security services.

### Tran Doan Cong Ly
**AWS Cloud Club Captain (PTIT)**

Captain of AWS Cloud Club at Posts and Telecommunications Institute of Technology, specializing in infrastructure security.

### Danh Hoang Hieu Nghi
**AWS Cloud Club Captain (HUFLIT)**

Captain of AWS Cloud Club at HCMC University of Foreign Languages - Information Technology, with expertise in cloud security practices.

### Nguyen Tuan Thinh
**Cloud Engineer Trainee**

Cloud Engineer in training, sharing hands-on experience with AWS security services.

### Nguyen Do Thanh
**Cloud Engineer**

Cloud Engineer with experience in deploying and operating secure cloud infrastructure.

### Thinh Lam
**FCJer**

First Cloud Journey member, sharing learning experiences and security best practices application.

### Viet Nguyen
**FCJer**

First Cloud Journey member with experience in AWS security implementation.

### Mendel Grabski (Long)
**ex Head of Security & DevOps - Cloud Security Solution Architect**

Security expert with experience leading Security & DevOps teams, currently serving as Cloud Security Solution Architect.

### Quang Tinh Truong
**AWS Community Builder - Platform Engineer at TymeX**

AWS Community Builder and Platform Engineer at TymeX, specializing in security architecture and platform engineering.

---

## Event Purpose

The "AWS Well-Architected Security Pillar" workshop was organized with the following objectives:

- Provide comprehensive knowledge about 5 AWS Security pillars
- Guide best practices for Identity & Access Management
- Introduce detection and continuous monitoring strategies
- Practice infrastructure and data protection
- Build incident response playbooks
- Share common pitfalls and Vietnamese enterprise realities
- Provide learning path guidance for AWS Security Specialty

---

## Highlights

### Pillar 1 - Identity & Access Management

#### Modern IAM Architecture

**IAM Fundamentals:**
- Users, Roles, Policies
- Avoiding long-term credentials
- Principle of least privilege

**IAM Identity Center:**
- Single Sign-On (SSO)
- Permission sets
- Centralized access management

**Multi-Account Security:**
- Service Control Policies (SCP)
- Permission boundaries
- Cross-account access patterns

**Security Best Practices:**
- Multi-Factor Authentication (MFA)
- Credential rotation
- AWS IAM Access Analyzer

**Mini Demo:** Validate IAM Policy + simulate access

---

### Pillar 2 - Detection

#### Detection & Continuous Monitoring

**AWS Security Services:**
- **CloudTrail:** Organization-level logging
- **GuardDuty:** Threat detection
- **Security Hub:** Centralized security findings

**Comprehensive Logging:**
- VPC Flow Logs
- Application Load Balancer logs
- S3 access logs
- CloudWatch Logs

**Alerting & Automation:**
- EventBridge rules
- Automated responses
- Security incident notifications

**Detection-as-Code:**
- Infrastructure monitoring rules
- Automated compliance checks

---

### Pillar 3 - Infrastructure Protection

#### Network & Workload Security

**VPC Security:**
- Network segmentation
- Private vs public subnet placement
- VPC endpoints

**Security Controls:**
- **Security Groups:** Stateful firewall
- **Network ACLs:** Stateless firewall
- Application patterns and best practices

**Advanced Protection:**
- **AWS WAF:** Web Application Firewall
- **AWS Shield:** DDoS protection
- **Network Firewall:** Advanced filtering

**Workload Protection:**
- EC2 security basics
- ECS/EKS security configurations
- Container security

---

### Pillar 4 - Data Protection

#### Encryption, Keys & Secrets

**AWS KMS (Key Management Service):**
- Key policies
- Grants management
- Automatic key rotation

**Encryption Strategies:**
- **At-rest encryption:**
  - Amazon S3
  - Amazon EBS
  - Amazon RDS
  - DynamoDB
- **In-transit encryption:**
  - TLS/SSL
  - VPN connections

**Secrets Management:**
- **AWS Secrets Manager:** Automatic rotation
- **Systems Manager Parameter Store:** Configuration management
- Rotation patterns and best practices

**Data Governance:**
- Data classification
- Access guardrails
- Compliance requirements

---

### Pillar 5 - Incident Response

#### IR Playbook & Automation

**Incident Response Lifecycle:**
- Preparation
- Detection & Analysis
- Containment
- Eradication
- Recovery
- Post-Incident Activity

**Practical Playbooks:**

1. **Compromised IAM Key:**
   - Detection methods
   - Immediate actions
   - Key rotation procedures

2. **S3 Public Exposure:**
   - Identifying exposed buckets
   - Remediation steps
   - Prevention measures

3. **EC2 Malware Detection:**
   - Detection via GuardDuty
   - Instance isolation
   - Forensics collection

**Forensics & Evidence:**
- Snapshot creation
- Instance isolation
- Evidence collection procedures
- Chain of custody

**Automated Response:**
- Lambda functions for auto-remediation
- Step Functions workflows
- EventBridge integration

---

### Wrap-Up & Q&A

**5 Pillars Summary:**
- Identity & Access Management
- Detection
- Infrastructure Protection
- Data Protection
- Incident Response

**Common Pitfalls:**
- Overly permissive IAM policies
- Insufficient logging
- Lack of encryption
- No incident response plan

**Vietnamese Enterprise Reality:**
- Compliance requirements
- Budget constraints
- Skills gap challenges

**Security Learning Roadmap:**
- AWS Certified Security - Specialty
- AWS Certified Solutions Architect - Professional
- Hands-on practice resources

---

## Knowledge Gained

### 1. Identity & Access Management

**Modern IAM Practices:**
- Deep understanding of IAM roles vs users
- Avoiding long-term credentials
- Implementing least privilege principle

**IAM Identity Center:**
- Centralized SSO solution
- Permission sets for multi-account
- Corporate directory integration

**Advanced IAM:**
- Service Control Policies (SCP) for organization-wide controls
- Permission boundaries to limit maximum permissions
- IAM Access Analyzer to identify unintended access

**Security Hardening:**
- MFA enforcement strategies
- Credential rotation automation
- Session policies

### 2. Detection & Monitoring

**Security Services Integration:**
- **CloudTrail:** Audit trail for all API calls
- **GuardDuty:** ML-based threat detection
- **Security Hub:** Aggregated security findings

**Comprehensive Logging Strategy:**
- VPC Flow Logs for network traffic analysis
- Application logs (ALB, CloudFront)
- S3 access logs
- Database audit logs

**Automated Detection:**
- EventBridge rules for real-time alerting
- Detection-as-Code approach
- Custom detection rules

**Monitoring Best Practices:**
- Log retention policies
- Log analysis with CloudWatch Insights
- Security metrics and KPIs

### 3. Infrastructure Protection

**Network Security:**
- VPC segmentation strategies
- Public vs private subnet design
- VPC endpoints for private connectivity

**Layered Security:**
- Security Groups: Instance-level protection
- NACLs: Subnet-level protection
- When to use which tool

**Advanced Protection Services:**
- **AWS WAF:** Protection against web exploits
- **AWS Shield:** DDoS mitigation
- **Network Firewall:** Stateful inspection

**Workload Security:**
- EC2 security best practices
- Container security (ECS/EKS)
- Patch management

### 4. Data Protection

**Encryption Fundamentals:**
- Encryption at-rest for all data stores
- Encryption in-transit with TLS
- Key management best practices

**AWS KMS:**
- Customer managed keys vs AWS managed keys
- Key policies and grants
- Automatic rotation
- Multi-region keys

**Secrets Management:**
- Secrets Manager for database credentials
- Parameter Store for configuration
- Automatic rotation patterns

**Data Classification:**
- Sensitive data identification
- Access controls based on classification
- Compliance requirements (GDPR, PCI-DSS)

### 5. Incident Response

**IR Framework:**
- AWS incident response lifecycle
- Preparation importance
- Playbook development

**Practical Playbooks:**
- **Compromised IAM Key:** Detection, rotation, impact assessment
- **S3 Public Exposure:** Identification, remediation, prevention
- **EC2 Malware:** Isolation, forensics, cleanup

**Forensics:**
- Evidence collection procedures
- Snapshots and memory dumps
- Chain of custody maintenance

**Automation:**
- Lambda-based auto-remediation
- Step Functions workflows
- Integration with ticketing systems

---

## Personal Experience

### Overall Impression

The Security Pillar workshop was a morning session packed with valuable content. Unlike the previous two workshops (AI/ML and DevOps), this one focused on security - a critical aspect that's often overlooked.

### Format and Structure

**Half-day format:**
- Concentrated content in 3.5 hours
- Fast-paced but well-structured
- Each pillar covered systematically

**5 Pillars Approach:**
- Logical flow from IAM → Detection → Infrastructure → Data → IR
- Each pillar builds on previous ones
- Comprehensive coverage of security landscape

### Pillar 1: IAM - Foundation of Security

**Key Takeaways:**
- IAM is the foundation of AWS security
- Roles over users - clear best practice
- IAM Identity Center is a game-changer for multi-account

**Mini Demo:**
- IAM Policy Simulator very useful
- Validate permissions before deployment
- Troubleshooting access issues

**Practical Insights:**
- Long-term credentials = security risk
- Permission boundaries prevent privilege escalation
- Access Analyzer identifies unintended access

### Pillar 2: Detection - Know What's Happening

**Security Services:**
- **CloudTrail:** Must-have for auditing
- **GuardDuty:** Impressive ML-based threat detection
- **Security Hub:** Valuable centralized view

**Logging Strategy:**
- Log everything, analyze selectively
- VPC Flow Logs for network forensics
- Application logs for business logic

**Automation:**
- EventBridge for real-time response
- Interesting Detection-as-Code approach
- Automated alerting reduces response time

### Pillar 3: Infrastructure Protection - Defense in Depth

**Network Security:**
- VPC segmentation critical
- Private subnets by default
- VPC endpoints reduce internet exposure

**Security Groups vs NACLs:**
- Security Groups: Stateful, preferred
- NACLs: Stateless, subnet-level
- Layered approach best

**Advanced Services:**
- **WAF:** Protect against OWASP Top 10
- **Shield:** DDoS protection included
- **Network Firewall:** Advanced filtering

### Pillar 4: Data Protection - Protect What Matters

**Encryption:**
- Encrypt everything at-rest
- TLS for all in-transit
- No excuses with AWS KMS

**KMS Deep Dive:**
- Key policies powerful but complex
- Automatic rotation recommended
- Multi-region keys for DR

**Secrets Management:**
- Secrets Manager for sensitive data
- Automatic rotation critical
- Parameter Store for non-sensitive config

**Data Classification:**
- Know your data
- Apply appropriate controls
- Compliance-driven approach

### Pillar 5: Incident Response - Be Prepared

**IR Playbooks:**
- Preparation prevents panic
- Documented procedures essential
- Practice makes perfect

**Practical Scenarios:**
1. **Compromised IAM Key:**
   - Clear detection methods
   - Step-by-step remediation
   - Prevention measures

2. **S3 Public Exposure:**
   - Common mistake
   - Quick remediation
   - Preventive controls

3. **EC2 Malware:**
   - GuardDuty detection
   - Isolation procedures
   - Forensics collection

**Automation:**
- Powerful Lambda auto-remediation
- Step Functions for complex workflows
- Significantly reduce response time

### Common Pitfalls Discussion

**Overly Permissive Policies:**
- "*" in policies dangerous
- Least privilege hard but necessary
- Regular policy reviews

**Insufficient Logging:**
- Can't detect what you don't log
- Storage costs vs security value
- Log retention policies

**No IR Plan:**
- Panic during incidents
- Slow response time
- Lack of documentation

### Vietnamese Enterprise Reality

**Challenges:**
- Budget constraints for security tools
- Skills gap in security
- Growing compliance requirements

**Opportunities:**
- AWS Free Tier for many security services
- Available training resources
- Community support

**Recommendations:**
- Start with IAM and logging
- Incremental security improvements
- Leverage AWS managed services

### Comparison with Previous Workshops

**AI/ML Workshop:**
- Cutting-edge technology
- Innovation-focused
- Future-oriented

**DevOps Workshop:**
- Operational excellence
- Automation-focused
- Efficiency-driven

**Security Workshop:**
- Risk mitigation
- Protection-focused
- Compliance-driven

**Integration:**
- Security enables innovation
- DevOps needs security
- All three pillars essential

### Challenges

- Many services and concepts in short time
- Security complexity initially overwhelming
- Limited hands-on practice due to time constraint
- Need more real-world scenarios

### Highlights

- Comprehensive coverage of security pillars
- Immediately applicable practical playbooks
- Valuable real-world pitfalls discussion
- Clear learning roadmap provided
- Focus on Vietnamese enterprise context

### Next Steps

**Immediate Actions:**
- Review IAM policies in projects
- Enable CloudTrail and GuardDuty
- Implement encryption at-rest
- Document IR procedures

**Short-term Goals:**
- Complete security audit of current infrastructure
- Implement automated detection rules
- Practice IR playbooks
- Enable Security Hub

**Long-term Goals:**
- AWS Certified Security - Specialty
- Build comprehensive security framework
- Contribute to security culture
- Mentor others on AWS security

---

## Conclusion

The "AWS Well-Architected Security Pillar" workshop provided a comprehensive framework for AWS security. Covering 5 critical pillars - IAM, Detection, Infrastructure Protection, Data Protection, and Incident Response - the workshop equipped participants with the knowledge and tools necessary to build secure applications on AWS.

Security is not an afterthought but a fundamental requirement. This workshop emphasized the importance of a security-first mindset and provided practical guidance for implementing security best practices.

Combined with knowledge from the AI/ML and DevOps workshops, I now have a holistic understanding of the AWS platform:
- **AI/ML:** Innovation and intelligent applications
- **DevOps:** Efficient delivery and operations
- **Security:** Protection and compliance

These three workshops together form a complete picture of modern cloud engineering on AWS. The Security workshop was particularly valuable as it ensures that innovation and efficiency don't compromise security and compliance.

The half-day format, though short, was content-dense and immediately applicable. This is an essential foundation for any AWS professional, and I highly recommend it for anyone working with AWS infrastructure.
