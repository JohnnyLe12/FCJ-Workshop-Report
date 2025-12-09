---
title: "Proposal"
date: 2025-12-09
weight: 2
chapter: false
pre: " <b> 2. </b> "
---
{{% notice warning %}}
⚠️ **Note:** The information below is for reference purposes only. Please **do not copy verbatim** for your report, including this warning.
{{% /notice %}}

In this section, you need to summarize the contents of the workshop that you **plan** to conduct.

# Travel Journal Platform
## AWS Serverless Solution for Travel Memory Management and Sharing

### 1. Executive Summary
The Travel Journal platform is developed by FPT University students to enable users to store, manage, and share photos, travel information, and locations they have visited. The platform creates a community for sharing travel experiences while providing a visual interface that allows users to review their journeys through timelines and interactive maps. Built on AWS Serverless architecture, the platform offers high scalability, strong security, and optimized cost efficiency with an estimated monthly cost under USD 70.

### 2. Problem Statement
#### What's the Problem?
Travelers lack a centralized platform to organize and preserve their travel memories. Photos are scattered across devices, location information is lost over time, and there's no easy way to visualize travel routes or shay.

#### The Solution
The Travel Journal platform leverages AWS Serverless services to provide a comprehensive solution. Users can upload travel photos to Amazon S3, with Amazon Rekognition automatically identifying scenes in images. Travel metadata and notes are stored in Amazon DynamoDB, while Amazon Location Service visualizes travel routes on interactive maps. The platform uses AWS Lambda and API Gateway for backend processing, with an asynchronous processing pipeline via Amazon SQS for image analysis. Amazon Cognito provides secure authentication with optional MFA, and the React-based frontend is delivered globally through Amazon Clo

#### Benefits and Return on Investmen
The platform provides students with hands-on experience building production-grade serverless applications following AWS Well-Architected Framework principles. It creates a reusable architecture pattern for similar applications and demonstrates cost-effective cloud solutions. With estimated monthly costs under USD 70 and a fully automated CI/CD pipeline, the platform showcases modern DevOps practices while delivering real value to users who want to preserve and share their travel memories.

### 3. Solution Architecture
Travel Journal is built using a fully serverless architecture on AWS, optimized for scalability, cost efficiency, and simplified operations. Static frontend content is hosted on Amazon S3 and delivered globally through Amazon CloudFront, with AWS WAF and ACM providing TLS security and protection against common web threats.

Users interact with the platform via a React-based web application to upload images, add travel notes, tag locations, and view interactive maps. All backend interactions are processed through Amazon API Gateway, which routes authenticated requests (via Amazon Cognito) to AWS Lambda functions. Uploaded images are stored in Amazon S3, where upload events trigger Amazon SQS to orchestrate asynchronous processing. Lambda workers consume these messages, analyze images through Amazon Rekognition, and store results in Amazon DynamoDB.

### AWS Services Used
- **Amazon S3**: Stores uploaded images and hosts static frontend content
- **Amazon CloudFront**: Global content delivery with low latency
- **AWS WAF & ACM**: Web application firewall and TLS certificate management
- **Amazon Cognito**: User authentication with optional MFA
- **Amazon API Gateway**: RESTful API endpoint management
- **AWS Lambda**: Serverless compute for business logic
- **Amazon SQS**: Message queue for asynchronous image processing
- **Amazon DynamoDB**: NoSQL database for metadata and user data
- **Amazon Rekognition**: AI-powered image scene detection
- **Amazon Location Service**: Interactive map visualization and geolocation
- **Amazon CloudWatch**: Monitoring, logging, and alerting
- **Amazon SNS**: System notifications and alerts
- **AWS KMS**: Encryption key management
- **AWS CodePipeline & CodeBuild**: CI/CD automation

### Component Design
- **Frontend**: React application hosted on S3, delivered via CloudFront
- **Authentication**: Amazon Cognito manages user registration, login, and MFA
- **API Layer**: API Gateway routes requests to Lambda functions
- **Image Storage**: S3 stores uploaded photos with encryption at rest
- **Asynchronous Processing**: SQS queues trigger Lambda workers for Rekognition analysis
- **Data Storage**: DynamoDB stores travel metadata, notes, and location tags
- **Map Visualization**: Amazon Location Service displays travel routes and tagged locations
- **Monitoring**: CloudWatch tracks performance metrics and triggers SNS alerts

### 4. Technical Implementation
**Implementation Phases**
The project follows an Agile Scrum framework over 8 two-week sprints (12 weeks total):

- **Assessment (Week 1-4)**: Team onboarding, AWS service training (S3, Lambda, API Gateway, DynamoDB, Cognito, SQS, CloudFront, Rekognition, CloudWatch), Git/GitHub workflow, and requirements discovery
- **Architecture Design & Planning (Week 5)**: Use case analysis, architecture design iterations following AWS Well-Architected Framework, MVP scope definition, and sprint planning
- **Base Infrastructure Setup (Week 6)**: Configure IAM, MFA, CloudTrail, AWS Config, create core services (S3, DynamoDB, API Gateway, Cognito, SQS), set up CloudFront + ACM + WAF, build CI/CD pipeline, and write Infrastructure as Code using CloudFormation
- **Backend Development (Week 7-8)**: Develop Lambda + API Gateway for image upload and trip management, implement S3 → SQS → Lambda processing pipeline, integrate Rekognition, optimize performance and costs
- **Frontend Development (Week 8-9)**: Build React UI for image upload, timeline, and trip pages, integrate Cognito authentication, implement interactive maps using Amazon Location Service, deploy to S3 + CloudFront
- **Testing & Go-live (Week 10-11)**: Functional and integration testing, configure CloudWatch monitoring and alarms, conduct load testing, bug fixing and MVP stabilization
- **Handover (Week 12)**: Prepare documentation, knowledge transfer sessions, final demo and project handover

**Technical Requirements**
- **Frontend**: React, MapLibre/Leaflet for maps, AWS Location Maps SDK
- **Backend**: Node.js Lambda functions, API Gateway REST APIs
- **Infrastructure**: AWS CDK or CloudFormation for IaC
- **CI/CD**: GitHub as source repository, CodePipeline and CodeBuild for automation
- **Security**: IAM least-privilege policies, KMS encryption, Cognito with MFA, WAF rules
- **Monitoring**: CloudWatch Logs, Metrics, Alarms, X-Ray for distributed tracing

### 5. Timeline & Milestones
**Project Timeline (12 Weeks)**

| Phase | Timeline | Key Milestones |
|-------|----------|----------------|
| Assessment | Week 1-4 | Team readiness report, AWS knowledge summary, requirements document |
| Architecture Design | Week 5 | Final architecture diagram, solution design document, sprint plan |
| Base Infrastructure | Week 6 | AWS environment ready, CI/CD pipeline operational, IaC templates complete |
| Backend Development | Week 7-8 | Backend API v1, Rekognition pipeline operational, DynamoDB structured |
| Frontend Development | Week 8-9 | React frontend v1, map and upload features functional, CloudFront deployment |
| Testing & Go-live | Week 10-11 | Test report, MVP stable, monitoring and alerting configured |
| Handover | Week 12 | Complete documentation, knowledge transfer sessions, final demo |

### 6. Budget Estimation
**Infrastructure Costs (Estimated Monthly)**

Based on moderate usage assumptions:
- 5,000-10,000 image uploads per month
- Average image size: 2-4 MB
- Single AWS Region deployment
- CloudFront: 50-100 GB/month outbound traffic
- DynamoDB: On-Demand capacity mode
- CloudWatch Logs: 30-day retention

**Estimated Monthly Cost: Under USD 70**

Key cost drivers:
- **Amazon S3**: Storage and requests for images and static content
- **Amazon Rekognition**: Per-image analysis charges
- **Amazon CloudFront**: Global content delivery
- **AWS Lambda**: Compute time for processing
- **Amazon DynamoDB**: On-demand read/write capacity
- **Amazon Location Service**: Map rendering and geocoding
- **Other Services**: API Gateway, SQS, CloudWatch, SNS (minimal costs)

**Development Costs**

| Resource | Rate (USD/hour) | Total Hours | Total Cost |
|----------|----------------|-------------|------------|
| Solutions Architect (1) | $20 | 44 | $880 |
| Engineers - FE/BE/DevOps (4) | $12 | 228 | $2,736 |
| QA Engineer | $8 | 16 | $128 |
| **Total** | | **288** | **$3,744** |

### 7. Risk Assessment
#### Key Risks and Mitigation

**Cost Overruns**
- **Risk**: Rekognition costs may exceed projections if image uploads spike
- **Mitigation**: Implement AWS Budget alerts, optimize image sizes before processing, set CloudWatch alarms for cost thresholds
- **Impact**: Medium | **Probability**: Low

**Security Vulnerabilities**
- **Risk**: Misconfigured IAM policies or exposed S3 buckets
- **Mitigation**: Apply least-privilege IAM policies, enable AWS Config for compliance monitoring, regular security audits
- **Impact**: High | **Probability**: Low

**Performance Issues**
- **Risk**: Slow image uploads or map rendering due to network latency
- **Mitigation**: Use CloudFront for global delivery, optimize image compression, implement progressive loading
- **Impact**: Medium | **Probability**: Medium

**Rekognition Accuracy**
- **Risk**: Inaccurate scene detection results affecting user experience
- **Mitigation**: Set confidence thresholds, allow manual corrections, provide user feedback mechanisms
- **Impact**: Low | **Probability**: Medium

#### Contingency Plans
- CloudFormation templates enable quick rollback of infrastructure changes
- Dead Letter Queue (DLQ) preserves failed messages for investigation
- CloudWatch alarms trigger SNS notifications for immediate incident response

### 8. Expected Outcomes

#### Project Success Criteria
- **Uptime**: 99% platform availability through serverless architecture
- **Security**: Secure authentication via Cognito with optional MFA, encryption at rest and in transit
- **Cost**: Monthly infrastructure costs under USD 70
- **Automation**: 100% CI/CD automation for build, test, and deployment
- **Monitoring**: CloudWatch alerts within 1 minute of errors or threshold breaches
- **Accuracy**: 95%+ accuracy in displaying user-tagged locations on maps

#### Technical Improvements
- Hands-on experience with production-grade AWS serverless architecture
- Understanding of AWS Well-Architected Framework principles
- Practical knowledge of CI/CD automation and DevOps practices
- Experience with modern frontend (React) and backend (Lambda) development

#### Long-term Value
- Reusable architecture pattern for similar serverless applications
- Comprehensive documentation and operational runbooks
- Foundation for future enhancements (mobile apps, social features, AI recommendations)
- Portfolio project demonstrating cloud-native development skills
