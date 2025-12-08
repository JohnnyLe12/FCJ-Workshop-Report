---
title: "Event 2"
date: 2025-11-17
weight: 2
chapter: false
pre: " <b> 4.2. </b> "
---

# DevOps on AWS Workshop

**Ngày:** Thứ Hai, 17 tháng 11, 2025  
**Thời gian:** 8:30 AM - 5:00 PM  
**Địa điểm:** AWS Office

---

## Danh sách diễn giả

### Bao Huynh
**AWS Community Builder**

AWS Community Builder với kinh nghiệm về DevOps practices và cloud architecture trên AWS.

### Thinh Nguyen
**AWS Community Builder**

AWS Community Builder chuyên về CI/CD, automation và infrastructure optimization.

### Vi Tran
**AWS Community Builder**

AWS Community Builder với expertise về container services và modern DevOps workflows.

---

## Mục đích của sự kiện

Workshop "DevOps on AWS" được tổ chức nhằm mục đích:

- Cung cấp kiến thức toàn diện về DevOps practices trên AWS
- Hướng dẫn xây dựng CI/CD pipeline hoàn chỉnh
- Giới thiệu Infrastructure as Code (IaC) với CloudFormation và CDK
- Thực hành triển khai container services trên AWS
- Tìm hiểu về monitoring và observability
- Chia sẻ best practices và case studies thực tế
- Định hướng career path trong lĩnh vực DevOps

---

## Nội dung nổi bật

### AWS DevOps Services - CI/CD Pipeline

**Source Control:**
- AWS CodeCommit
- Git strategies: GitFlow và Trunk-based development

**Build & Test:**
- Cấu hình CodeBuild
- Testing pipelines

**Deployment:**
- CodeDeploy với các chiến lược:
  - Blue/Green deployment
  - Canary deployment
  - Rolling updates

**Orchestration:**
- CodePipeline automation

**Demo:** Full CI/CD pipeline walkthrough

---

### Infrastructure as Code (IaC)

**AWS CloudFormation:**
- Templates
- Stacks management
- Drift detection

**AWS CDK (Cloud Development Kit):**
- Constructs
- Reusable patterns
- Language support (TypeScript, Python, Java, etc.)

**Demo:** Deploying với CloudFormation và CDK

**Discussion:** So sánh và lựa chọn giữa các IaC tools

---

### Container Services on AWS

**Docker Fundamentals:**
- Microservices architecture
- Containerization concepts

**Amazon ECR (Elastic Container Registry):**
- Image storage
- Security scanning
- Lifecycle policies

**Amazon ECS & EKS:**
- Deployment strategies
- Auto-scaling
- Orchestration

**AWS App Runner:**
- Simplified container deployment

**Demo & Case Study:** So sánh các phương pháp triển khai microservices

---

### Monitoring & Observability

**CloudWatch:**
- Metrics collection
- Logs aggregation
- Alarms configuration
- Custom dashboards

**AWS X-Ray:**
- Distributed tracing
- Performance insights
- Bottleneck identification

**Demo:** Full-stack observability setup

**Best Practices:**
- Alerting strategies
- Dashboard design
- On-call processes

---

### DevOps Best Practices & Case Studies

**Deployment Strategies:**
- Feature flags
- A/B testing
- Progressive delivery

**Automated Testing:**
- CI/CD integration
- Test automation frameworks

**Incident Management:**
- Incident response procedures
- Postmortem analysis

**Case Studies:**
- Startup DevOps transformations
- Enterprise-scale implementations

---

### Q&A & Wrap-up

- DevOps career pathways
- AWS certification roadmap
- Resources và learning paths

---

## Kiến thức thu được

### 1. CI/CD Pipeline với AWS DevOps Services

**Source Control & Git Strategies:**
- Hiểu rõ về AWS CodeCommit và tích hợp với Git
- So sánh GitFlow vs Trunk-based development
- Best practices cho branching strategies

**Build & Test Automation:**
- Cấu hình CodeBuild cho các loại projects khác nhau
- Thiết lập testing pipelines tự động
- Integration testing và unit testing trong CI/CD

**Deployment Strategies:**
- Blue/Green deployment: Zero-downtime deployments
- Canary deployment: Gradual rollout với monitoring
- Rolling updates: Phù hợp cho các ứng dụng stateless

**Pipeline Orchestration:**
- CodePipeline automation end-to-end
- Multi-stage pipelines
- Approval gates và manual interventions

### 2. Infrastructure as Code (IaC)

**AWS CloudFormation:**
- Viết và quản lý templates
- Stack management và dependencies
- Drift detection để phát hiện changes ngoài IaC
- Nested stacks cho kiến trúc phức tạp

**AWS CDK:**
- Sử dụng programming languages (TypeScript, Python) thay vì JSON/YAML
- Constructs và patterns tái sử dụng
- Higher-level abstractions
- Testing infrastructure code

**Tool Selection:**
- Khi nào dùng CloudFormation vs CDK
- Terraform comparison
- Trade-offs và use cases

### 3. Container Services

**Docker & Microservices:**
- Container fundamentals
- Microservices architecture patterns
- Best practices cho containerization

**Amazon ECR:**
- Private container registry
- Image scanning cho security vulnerabilities
- Lifecycle policies để quản lý images

**ECS vs EKS:**
- **ECS:** AWS-native, simpler setup, tích hợp tốt với AWS services
- **EKS:** Kubernetes-based, portable, phù hợp cho multi-cloud
- Deployment strategies cho từng service
- Auto-scaling configurations

**AWS App Runner:**
- Simplified deployment cho containers
- Automatic scaling
- Use cases phù hợp

### 4. Monitoring & Observability

**CloudWatch:**
- Custom metrics và standard metrics
- Log aggregation từ multiple sources
- Alarm configuration với SNS notifications
- Dashboard design cho different stakeholders

**AWS X-Ray:**
- Distributed tracing cho microservices
- Service map visualization
- Performance bottleneck identification
- Integration với application code

**Observability Best Practices:**
- The three pillars: Metrics, Logs, Traces
- Alerting strategies: Avoid alert fatigue
- Dashboard design principles
- On-call rotation và incident response

### 5. DevOps Best Practices

**Progressive Delivery:**
- Feature flags cho controlled rollouts
- A/B testing strategies
- Canary analysis

**Testing Automation:**
- Test pyramid: Unit, Integration, E2E
- CI/CD integration
- Test coverage và quality gates

**Incident Management:**
- Incident response procedures
- Blameless postmortems
- Learning from failures

**Real-world Case Studies:**
- Startup: Rapid iteration với minimal resources
- Enterprise: Scaling DevOps practices across teams

---

## Trải nghiệm cá nhân

### Ấn tượng chung

Workshop DevOps on AWS là một trải nghiệm intensive và practical. Khác với workshop AI/ML trước đó, workshop này tập trung nhiều hơn vào hands-on practices và real-world scenarios.

### CI/CD Pipeline Demo

Phần demo về CI/CD pipeline là highlight của buổi sáng. Được thấy một pipeline hoàn chỉnh từ code commit đến production deployment giúp tôi hiểu rõ hơn về:
- Cách các AWS DevOps services tích hợp với nhau
- Automation ở mỗi stage
- Error handling và rollback strategies

Đặc biệt ấn tượng với Blue/Green deployment demo - zero downtime và khả năng rollback instant.

### Infrastructure as Code

Phần IaC mở mang tư duy về "infrastructure as software":

**CloudFormation:**
- Templates có vẻ verbose nhưng powerful
- Drift detection là tính năng rất hữu ích cho production environments

**AWS CDK:**
- Game changer! Viết infrastructure bằng programming language quen thuộc
- Type safety và IDE support
- Reusable constructs giúp standardize infrastructure

So sánh giữa CloudFormation và CDK giúp tôi hiểu khi nào nên dùng tool nào.

### Container Services

Phần containers rất comprehensive:

**Docker Fundamentals:**
- Review về containerization concepts
- Best practices cho Dockerfile
- Multi-stage builds

**ECS vs EKS Comparison:**
- ECS: Đơn giản hơn, AWS-native, phù hợp cho AWS-centric workloads
- EKS: Kubernetes standard, portable, learning curve cao hơn
- Demo deployment trên cả hai platforms giúp thấy rõ differences

**App Runner:**
- Surprisingly simple! Deploy container chỉ với vài clicks
- Automatic scaling
- Good fit cho simple containerized applications

### Monitoring & Observability

Phần này rất practical và immediately applicable:

**CloudWatch:**
- Custom metrics cho business KPIs
- Log Insights queries rất powerful
- Dashboard design tips

**X-Ray:**
- Distributed tracing visualization impressive
- Giúp identify bottlenecks trong microservices architecture
- Integration straightforward

Full-stack observability demo cho thấy tầm quan trọng của monitoring trong DevOps.

### Best Practices & Case Studies

**Deployment Strategies:**
- Feature flags cho progressive rollout
- A/B testing integration
- Risk mitigation strategies

**Case Studies:**
- Startup case: Scrappy DevOps với limited resources
- Enterprise case: Scaling DevOps culture across organization
- Lessons learned từ real failures

### Networking & Q&A

Q&A session rất valuable:
- DevOps career pathways discussion
- AWS certification roadmap (DevOps Engineer Professional)
- Tips từ practitioners
- Networking với DevOps engineers từ different companies

### Thách thức

- Nhiều services và concepts trong một ngày
- Hands-on time hơi limited cho complexity của topics
- Muốn practice nhiều hơn với CDK
- Container orchestration cần thời gian để master

### Điểm nổi bật

- Practical, hands-on approach
- Real-world case studies rất relatable
- Comprehensive coverage của DevOps lifecycle
- Speakers có deep expertise
- Good balance giữa theory và practice

### So sánh với AI/ML Workshop

- DevOps workshop more hands-on và practical
- AI/ML workshop more cutting-edge và exploratory
- Cả hai đều valuable nhưng different focus areas
- DevOps skills more immediately applicable

### Kế hoạch tiếp theo

Sau workshop, tôi có kế hoạch:

**Immediate Actions:**
- Setup personal CI/CD pipeline cho projects
- Practice với AWS CDK
- Implement monitoring cho existing applications

**Short-term Goals:**
- Build complete DevOps pipeline cho một project
- Deep dive vào container orchestration (ECS/EKS)
- Practice IaC với real scenarios

**Long-term Goals:**
- AWS Certified DevOps Engineer - Professional
- Contribute to DevOps culture trong team
- Build reusable IaC patterns

---

## Kết luận

Workshop "DevOps on AWS" cung cấp một foundation vững chắc về DevOps practices trên AWS platform. Từ CI/CD pipelines đến container orchestration, từ IaC đến observability - workshop cover toàn bộ DevOps lifecycle một cách comprehensive và practical.

Kiến thức thu được không chỉ là technical skills mà còn là mindset về automation, continuous improvement, và collaboration. Case studies và best practices từ real-world scenarios đặc biệt valuable.

Workshop này là bước tiếp theo quan trọng sau AI/ML workshop, giúp tôi hiểu rõ hơn về cách deploy và operate các applications trên AWS một cách professional và scalable. DevOps skills là foundation cần thiết cho bất kỳ cloud engineer nào, và workshop này đã cung cấp một starting point tuyệt vời.

Kết hợp với kiến thức từ AI/ML workshop trước đó, tôi giờ có một comprehensive understanding về cả development và operations aspects của cloud applications trên AWS.
