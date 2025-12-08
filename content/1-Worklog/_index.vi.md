---
title: "Nhật ký công việc"
date: 2025-09-10
weight: 1
chapter: false
pre: " <b> 1. </b> "
---

Worklog này ghi lại hành trình thực tập **12 tuần** tại chương trình **First Cloud Journey**, trong đó tôi đã học hỏi và thực hành với các dịch vụ AWS, từ những kiến thức cơ bản đến nâng cao, đồng thời triển khai một dự án thực tế là **Travel Guide Web Application**.

### Giai đoạn 1: Nền tảng AWS (Tuần 1-4)

Trong giai đoạn đầu, tôi tập trung vào việc xây dựng nền tảng kiến thức về AWS, bao gồm các dịch vụ cốt lõi về mạng, tính toán, và cơ sở hạ tầng.

**Tuần 1:** [Làm quen với AWS và thiết lập môi trường](1.1-week1/) - Tìm hiểu về AWS, các dịch vụ cơ bản, tạo tài khoản AWS Free Tier, cấu hình IAM và AWS CLI.

**Tuần 2:** [Khám phá Amazon VPC và Networking](1.2-week2/) - Học về VPC, Subnets, Route Tables, Internet Gateway, NAT Gateway, Security Groups và Network ACLs.

**Tuần 3:** [Kết nối VPC và Load Balancing](1.3-week3/) - Tìm hiểu VPC Peering, Transit Gateway, VPN, Direct Connect và các loại Load Balancer (ALB, NLB, CLB, GWLB).

**Tuần 4:** [DNS, CloudFormation và Transit Gateway](1.4-week4/) - Thực hành với Route 53, CloudFormation (IaC), thiết lập Hybrid DNS, VPC Peering và Transit Gateway.

### Giai đoạn 2: Storage, Security và Database (Tuần 5-8)

Giai đoạn này tập trung vào các dịch vụ lưu trữ, bảo mật, và cơ sở dữ liệu, đồng thời bắt đầu dự án nhóm.

**Tuần 5:** [Storage Services và Disaster Recovery](1.5-week5/) - Học về EC2, Lightsail, EFS, FSx, S3 (Access Point, Glacier, CORS), Storage Gateway, AWS Backup và khái niệm RTO/RPO.

**Tuần 6:** [Thực hành Backup, Migration và khởi động dự án](1.6-week6/) - Triển khai AWS Backup, VM Import/Export, File Storage Gateway. Tham gia nhóm và quyết định làm dự án Travel Guide Web App.

**Tuần 7:** [S3 Advanced, FSx và Security](1.7-week7/) - Thực hành S3 Static Website với CloudFront, FSx for Windows với các tính năng enterprise. Học về IAM, Cognito, Organizations, KMS, Security Hub. Hoàn thiện sơ đồ kiến trúc dự án.

**Tuần 8:** [Database Services và thi giữa kỳ](1.8-week8/) - Học về RDS, Aurora, ElastiCache, Redshift. Thực hành triển khai RDS với backup/restore. Ôn tập và hoàn thành kỳ thi giữa kỳ.

### Giai đoạn 3: AI/ML và Messaging Services (Tuần 9-11)

Giai đoạn này tập trung vào việc tích hợp các dịch vụ AI/ML và messaging vào dự án thực tế.

**Tuần 9:** [AWS Rekognition - Computer Vision](1.9-week9/) - Tìm hiểu AWS Rekognition, triển khai tính năng Detect Labels vào dự án để phân tích hình ảnh du lịch, tối ưu hóa với label filtering.

**Tuần 10:** [Amazon SQS - Message Queue](1.10-week10/) - Học về SQS (Standard và FIFO Queue), triển khai vào dự án để xử lý ảnh bất đồng bộ, đảm bảo xử lý theo trình tự. Tham gia AWS Cloud Mastery Series #1.

**Tuần 11:** [SNS và SES - Notification Services](1.11-week11/) - Tìm hiểu SNS và SES, triển khai hệ thống gửi email cho người dùng (welcome, booking confirmation, recommendations). Tham gia AWS Cloud Mastery Series #2.

### Giai đoạn 4: Hoàn thiện và Demo (Tuần 12)

**Tuần 12:** [Testing, Bug Fixes và Hoàn thành dự án](1.12-week12/) - Kiểm tra toàn diện website và các chức năng, sửa lỗi, chuẩn bị demo, hoàn thành workshop cá nhân. Tham gia AWS Cloud Mastery Series #3.

---

### Tổng kết

Sau 12 tuần thực tập, tôi đã:
- Nắm vững các dịch vụ AWS cốt lõi: VPC, EC2, S3, RDS, Lambda, CloudFront
- Thực hành với các dịch vụ nâng cao: Rekognition, SQS, SNS, SES, Transit Gateway, CloudFormation
- Triển khai thành công dự án **Travel Guide Web Application** với kiến trúc serverless
- Tham gia các sự kiện AWS Cloud Mastery Series và networking với cộng đồng
- Hoàn thành workshop cá nhân và documentation đầy đủ