---
title: "Event 2"
date: 2025-11-17
weight: 2
chapter: false
pre: " <b> 4.2. </b> "
---

# DevOps on AWS Workshop

**Date:** Monday, November 17, 2025  
**Time:** 8:30 AM - 5:00 PM  
**Location:** AWS Office

---

## Speaker Lineup

### Bao Huynh
**AWS Community Builder**

AWS Community Builder with experience in DevOps practices and cloud architecture on AWS.

### Thinh Nguyen
**AWS Community Builder**

AWS Community Builder specializing in CI/CD, automation, and infrastructure optimization.

### Vi Tran
**AWS Community Builder**

AWS Community Builder with expertise in container services and modern DevOps workflows.

---

## Event Purpose

The "DevOps on AWS" workshop was organized with the following objectives:

- Provide comprehensive knowledge about DevOps practices on AWS
- Guide building complete CI/CD pipelines
- Introduce Infrastructure as Code (IaC) with CloudFormation and CDK
- Practice deploying container services on AWS
- Learn about monitoring and observability
- Share best practices and real-world case studies
- Provide career path guidance in DevOps field

---

## Highlights

### AWS DevOps Services - CI/CD Pipeline

**Source Control:**
- AWS CodeCommit
- Git strategies: GitFlow and Trunk-based development

**Build & Test:**
- CodeBuild configuration
- Testing pipelines

**Deployment:**
- CodeDeploy with strategies:
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

**Demo:** Deploying with CloudFormation and CDK

**Discussion:** Comparing and choosing between IaC tools

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

**Demo & Case Study:** Comparing microservices deployment methods

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
- Resources and learning paths

---

## Knowledge Gained

### 1. CI/CD Pipeline with AWS DevOps Services

**Source Control & Git Strategies:**
- Understanding AWS CodeCommit and Git integration
- Comparing GitFlow vs Trunk-based development
- Best practices for branching strategies

**Build & Test Automation:**
- Configuring CodeBuild for different project types
- Setting up automated testing pipelines
- Integration and unit testing in CI/CD

**Deployment Strategies:**
- Blue/Green deployment: Zero-downtime deployments
- Canary deployment: Gradual rollout with monitoring
- Rolling updates: Suitable for stateless applications

**Pipeline Orchestration:**
- End-to-end CodePipeline automation
- Multi-stage pipelines
- Approval gates and manual interventions

### 2. Infrastructure as Code (IaC)

**AWS CloudFormation:**
- Writing and managing templates
- Stack management and dependencies
- Drift detection to identify changes outside IaC
- Nested stacks for complex architectures

**AWS CDK:**
- Using programming languages (TypeScript, Python) instead of JSON/YAML
- Reusable constructs and patterns
- Higher-level abstractions
- Testing infrastructure code

**Tool Selection:**
- When to use CloudFormation vs CDK
- Terraform comparison
- Trade-offs and use cases

### 3. Container Services

**Docker & Microservices:**
- Container fundamentals
- Microservices architecture patterns
- Containerization best practices

**Amazon ECR:**
- Private container registry
- Image scanning for security vulnerabilities
- Lifecycle policies for image management

**ECS vs EKS:**
- **ECS:** AWS-native, simpler setup, good AWS services integration
- **EKS:** Kubernetes-based, portable, suitable for multi-cloud
- Deployment strategies for each service
- Auto-scaling configurations

**AWS App Runner:**
- Simplified container deployment
- Automatic scaling
- Suitable use cases

### 4. Monitoring & Observability

**CloudWatch:**
- Custom and standard metrics
- Log aggregation from multiple sources
- Alarm configuration with SNS notifications
- Dashboard design for different stakeholders

**AWS X-Ray:**
- Distributed tracing for microservices
- Service map visualization
- Performance bottleneck identification
- Application code integration

**Observability Best Practices:**
- The three pillars: Metrics, Logs, Traces
- Alerting strategies: Avoiding alert fatigue
- Dashboard design principles
- On-call rotation and incident response

### 5. DevOps Best Practices

**Progressive Delivery:**
- Feature flags for controlled rollouts
- A/B testing strategies
- Canary analysis

**Testing Automation:**
- Test pyramid: Unit, Integration, E2E
- CI/CD integration
- Test coverage and quality gates

**Incident Management:**
- Incident response procedures
- Blameless postmortems
- Learning from failures

**Real-world Case Studies:**
- Startup: Rapid iteration with minimal resources
- Enterprise: Scaling DevOps practices across teams

---

## Personal Experience

### Overall Impression

The DevOps on AWS workshop was an intensive and practical experience. Unlike the previous AI/ML workshop, this one focused more on hands-on practices and real-world scenarios.

### CI/CD Pipeline Demo

The CI/CD pipeline demo was the morning's highlight. Seeing a complete pipeline from code commit to production deployment helped me better understand:
- How AWS DevOps services integrate together
- Automation at each stage
- Error handling and rollback strategies

Particularly impressed with the Blue/Green deployment demo - zero downtime and instant rollback capability.

### Infrastructure as Code

The IaC section opened my mind about "infrastructure as software":

**CloudFormation:**
- Templates seem verbose but powerful
- Drift detection is very useful for production environments

**AWS CDK:**
- Game changer! Writing infrastructure in familiar programming languages
- Type safety and IDE support
- Reusable constructs help standardize infrastructure

The comparison between CloudFormation and CDK helped me understand when to use which tool.

### Container Services

The containers section was very comprehensive:

**Docker Fundamentals:**
- Review of containerization concepts
- Dockerfile best practices
- Multi-stage builds

**ECS vs EKS Comparison:**
- ECS: Simpler, AWS-native, suitable for AWS-centric workloads
- EKS: Kubernetes standard, portable, higher learning curve
- Deployment demos on both platforms clearly showed differences

**App Runner:**
- Surprisingly simple! Deploy containers with just a few clicks
- Automatic scaling
- Good fit for simple containerized applications

### Monitoring & Observability

This section was very practical and immediately applicable:

**CloudWatch:**
- Custom metrics for business KPIs
- Log Insights queries are very powerful
- Dashboard design tips

**X-Ray:**
- Impressive distributed tracing visualization
- Helps identify bottlenecks in microservices architecture
- Straightforward integration

The full-stack observability demo showed the importance of monitoring in DevOps.

### Best Practices & Case Studies

**Deployment Strategies:**
- Feature flags for progressive rollout
- A/B testing integration
- Risk mitigation strategies

**Case Studies:**
- Startup case: Scrappy DevOps with limited resources
- Enterprise case: Scaling DevOps culture across organization
- Lessons learned from real failures

### Networking & Q&A

The Q&A session was very valuable:
- DevOps career pathways discussion
- AWS certification roadmap (DevOps Engineer Professional)
- Tips from practitioners
- Networking with DevOps engineers from different companies

### Challenges

- Many services and concepts in one day
- Somewhat limited hands-on time for topic complexity
- Wanted more practice with CDK
- Container orchestration needs time to master

### Highlights

- Practical, hands-on approach
- Very relatable real-world case studies
- Comprehensive coverage of DevOps lifecycle
- Speakers with deep expertise
- Good balance between theory and practice

### Comparison with AI/ML Workshop

- DevOps workshop more hands-on and practical
- AI/ML workshop more cutting-edge and exploratory
- Both valuable but different focus areas
- DevOps skills more immediately applicable

### Next Steps

After the workshop, I plan to:

**Immediate Actions:**
- Setup personal CI/CD pipeline for projects
- Practice with AWS CDK
- Implement monitoring for existing applications

**Short-term Goals:**
- Build complete DevOps pipeline for a project
- Deep dive into container orchestration (ECS/EKS)
- Practice IaC with real scenarios

**Long-term Goals:**
- AWS Certified DevOps Engineer - Professional
- Contribute to DevOps culture in team
- Build reusable IaC patterns

---

## Conclusion

The "DevOps on AWS" workshop provided a solid foundation in DevOps practices on the AWS platform. From CI/CD pipelines to container orchestration, from IaC to observability - the workshop comprehensively and practically covered the entire DevOps lifecycle.

The knowledge gained includes not just technical skills but also the mindset of automation, continuous improvement, and collaboration. Case studies and best practices from real-world scenarios were particularly valuable.

This workshop was an important next step after the AI/ML workshop, helping me better understand how to deploy and operate applications on AWS professionally and at scale. DevOps skills are essential foundations for any cloud engineer, and this workshop provided an excellent starting point.

Combined with knowledge from the previous AI/ML workshop, I now have a comprehensive understanding of both development and operations aspects of cloud applications on AWS.
