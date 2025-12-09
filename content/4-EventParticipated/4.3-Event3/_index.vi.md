---
title: "Event 3"
date: 2025-11-29
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---

# AWS Well-Architected Security Pillar Workshop

**Ngày:** Thứ Bảy, 29 tháng 11, 2025  
**Thời gian:** 8:30 AM - 12:00 PM  
**Địa điểm:** AWS Vietnam Office

---

## Danh sách diễn giả

### Lê Vũ Xuân An
**AWS Cloud Club Captain (HCMU/TE)**

Captain của AWS Cloud Club tại Đại học Bách Khoa TP.HCM, chuyên về cloud architecture và security.

### Trần Đức Anh
**AWS Cloud Club Captain (SGU)**

Captain của AWS Cloud Club tại Đại học Sài Gòn, có kinh nghiệm về AWS security services.

### Trần Đoàn Công Lý
**AWS Cloud Club Captain (PTIT)**

Captain của AWS Cloud Club tại Học viện Công nghệ Bưu chính Viễn thông, chuyên về infrastructure security.

### Danh Hoàng Hiếu Nghị
**AWS Cloud Club Captain (HUFLIT)**

Captain của AWS Cloud Club tại Đại học Ngoại ngữ - Tin học TP.HCM, có expertise về cloud security practices.

### Nguyễn Tuấn Thịnh
**Cloud Engineer Trainee**

Cloud Engineer đang trong quá trình đào tạo, chia sẻ kinh nghiệm thực hành với AWS security services.

### Nguyễn Đỗ Thanh
**Cloud Engineer**

Cloud Engineer với kinh nghiệm triển khai và vận hành secure cloud infrastructure.

### Thịnh Lâm
**FCJer**

Thành viên First Cloud Journey, chia sẻ trải nghiệm học tập và áp dụng security best practices.

### Việt Nguyễn
**FCJer**

Thành viên First Cloud Journey, có kinh nghiệm về AWS security implementation.

### Mendel Grabski (Long)
**ex Head of Security & DevOps - Cloud Security Solution Architect**

Chuyên gia bảo mật với kinh nghiệm lãnh đạo Security & DevOps teams, hiện là Cloud Security Solution Architect.

### Quang Tinh Truong
**AWS Community Builder - Platform Engineer at TymeX**

AWS Community Builder và Platform Engineer tại TymeX, chuyên về security architecture và platform engineering.

---

## Mục đích của sự kiện

Workshop "AWS Well-Architected Security Pillar" được tổ chức nhằm mục đích:

- Cung cấp kiến thức toàn diện về 5 pillars của AWS Security
- Hướng dẫn best practices cho Identity & Access Management
- Giới thiệu detection và continuous monitoring strategies
- Thực hành infrastructure và data protection
- Xây dựng incident response playbooks
- Chia sẻ common pitfalls và thực tế doanh nghiệp Việt Nam
- Định hướng learning path cho AWS Security Specialty

---

## Nội dung nổi bật

### Pillar 1 - Identity & Access Management

#### Modern IAM Architecture

**IAM Fundamentals:**
- Users, Roles, Policies
- Tránh long-term credentials
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
- Application patterns và best practices

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
- Rotation patterns và best practices

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

**Tổng kết 5 Pillars:**
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

**Thực tế doanh nghiệp Việt Nam:**
- Compliance requirements
- Budget constraints
- Skills gap challenges

**Security Learning Roadmap:**
- AWS Certified Security - Specialty
- AWS Certified Solutions Architect - Professional
- Hands-on practice resources

---

## Kiến thức thu được

### 1. Identity & Access Management

**Modern IAM Practices:**
- Hiểu sâu về IAM roles vs users
- Tránh sử dụng long-term credentials
- Implement least privilege principle

**IAM Identity Center:**
- Centralized SSO solution
- Permission sets cho multi-account
- Integration với corporate directory

**Advanced IAM:**
- Service Control Policies (SCP) cho organization-wide controls
- Permission boundaries để limit maximum permissions
- IAM Access Analyzer để identify unintended access

**Security Hardening:**
- MFA enforcement strategies
- Credential rotation automation
- Session policies

### 2. Detection & Monitoring

**Security Services Integration:**
- **CloudTrail:** Audit trail cho all API calls
- **GuardDuty:** ML-based threat detection
- **Security Hub:** Aggregated security findings

**Comprehensive Logging Strategy:**
- VPC Flow Logs cho network traffic analysis
- Application logs (ALB, CloudFront)
- S3 access logs
- Database audit logs

**Automated Detection:**
- EventBridge rules cho real-time alerting
- Detection-as-Code approach
- Custom detection rules

**Monitoring Best Practices:**
- Log retention policies
- Log analysis với CloudWatch Insights
- Security metrics và KPIs

### 3. Infrastructure Protection

**Network Security:**
- VPC segmentation strategies
- Public vs private subnet design
- VPC endpoints cho private connectivity

**Layered Security:**
- Security Groups: Instance-level protection
- NACLs: Subnet-level protection
- Khi nào dùng tool nào

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
- Encryption at-rest cho all data stores
- Encryption in-transit với TLS
- Key management best practices

**AWS KMS:**
- Customer managed keys vs AWS managed keys
- Key policies và grants
- Automatic rotation
- Multi-region keys

**Secrets Management:**
- Secrets Manager cho database credentials
- Parameter Store cho configuration
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
- Snapshot và memory dumps
- Chain of custody maintenance

**Automation:**
- Lambda-based auto-remediation
- Step Functions workflows
- Integration với ticketing systems

---

## Trải nghiệm cá nhân

### Ấn tượng chung

Workshop Security Pillar là buổi morning session nhưng packed với valuable content. Khác với hai workshops trước (AI/ML và DevOps), workshop này focus vào security - một aspect critical nhưng often overlooked.

### Format và Cấu trúc

**Half-day format:**
- Concentrated content trong 3.5 giờ
- Fast-paced nhưng well-structured
- Mỗi pillar được cover systematically

**5 Pillars Approach:**
- Logical flow từ IAM → Detection → Infrastructure → Data → IR
- Mỗi pillar builds on previous ones
- Comprehensive coverage của security landscape

### Pillar 1: IAM - Foundation of Security

**Key Takeaways:**
- IAM là foundation của AWS security
- Roles over users - best practice rõ ràng
- IAM Identity Center game-changer cho multi-account

**Mini Demo:**
- IAM Policy Simulator rất useful
- Validate permissions trước khi deploy
- Troubleshooting access issues

**Practical Insights:**
- Long-term credentials = security risk
- Permission boundaries prevent privilege escalation
- Access Analyzer identifies unintended access

### Pillar 2: Detection - Know What's Happening

**Security Services:**
- **CloudTrail:** Must-have cho audit
- **GuardDuty:** ML-based threat detection impressive
- **Security Hub:** Centralized view valuable

**Logging Strategy:**
- Log everything, analyze selectively
- VPC Flow Logs cho network forensics
- Application logs cho business logic

**Automation:**
- EventBridge cho real-time response
- Detection-as-Code approach interesting
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
- No excuses với AWS KMS

**KMS Deep Dive:**
- Key policies powerful but complex
- Automatic rotation recommended
- Multi-region keys cho DR

**Secrets Management:**
- Secrets Manager cho sensitive data
- Automatic rotation critical
- Parameter Store cho non-sensitive config

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
- Lambda auto-remediation powerful
- Step Functions cho complex workflows
- Reduce response time significantly

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

### Thực tế Doanh nghiệp Việt Nam

**Challenges:**
- Budget constraints cho security tools
- Skills gap trong security
- Compliance requirements growing

**Opportunities:**
- AWS Free Tier cho many security services
- Training resources available
- Community support

**Recommendations:**
- Start with IAM và logging
- Incremental security improvements
- Leverage AWS managed services

### So sánh với Previous Workshops

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

### Thách thức

- Nhiều services và concepts trong short time
- Security complexity overwhelming initially
- Hands-on practice limited do time constraint
- Need more real-world scenarios

### Điểm nổi bật

- Comprehensive coverage của security pillars
- Practical playbooks immediately applicable
- Real-world pitfalls discussion valuable
- Clear learning roadmap provided
- Focus on Vietnamese enterprise context

### Kế hoạch tiếp theo

**Immediate Actions:**
- Review IAM policies trong projects
- Enable CloudTrail và GuardDuty
- Implement encryption at-rest
- Document IR procedures

**Short-term Goals:**
- Complete security audit của current infrastructure
- Implement automated detection rules
- Practice IR playbooks
- Enable Security Hub

**Long-term Goals:**
- AWS Certified Security - Specialty
- Build comprehensive security framework
- Contribute to security culture
- Mentor others on AWS security

---

## Kết luận

Workshop "AWS Well-Architected Security Pillar" cung cấp một comprehensive framework cho AWS security. Covering 5 critical pillars - IAM, Detection, Infrastructure Protection, Data Protection, và Incident Response - workshop trang bị knowledge và tools cần thiết để build secure applications trên AWS.

Security không phải là afterthought mà là fundamental requirement. Workshop này emphasize importance của security-first mindset và cung cấp practical guidance để implement security best practices.

Kết hợp với kiến thức từ AI/ML và DevOps workshops, tôi giờ có một holistic understanding của AWS platform:
- **AI/ML:** Innovation và intelligent applications
- **DevOps:** Efficient delivery và operations
- **Security:** Protection và compliance

Ba workshops này together form một complete picture của modern cloud engineering trên AWS. Security workshop đặc biệt valuable vì nó ensures rằng innovation và efficiency không compromise security và compliance.

Half-day format tuy ngắn nhưng content density cao và immediately applicable. Đây là foundation cần thiết cho bất kỳ AWS professional nào, và tôi highly recommend cho anyone working với AWS infrastructure.
