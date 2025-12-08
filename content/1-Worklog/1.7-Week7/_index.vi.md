---
title: "Worklog Tuần 7"
date: 2025-09-10
weight: 1
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu tuần 7:

* Thực hành triển khai Amazon S3 với các tính năng nâng cao: static website, CloudFront, versioning
* Thực hành triển khai Amazon FSx for Windows với các tính năng enterprise
* Tìm hiểu về Shared Responsibility Model trong AWS
* Nắm vững AWS Identity and Access Management (IAM) và các dịch vụ bảo mật
* Hỗ trợ hoàn thiện sơ đồ kiến trúc cho dự án nhóm

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2   | - **Thực hành:** Khởi đầu với Amazon S3 <br>&emsp; + Tạo S3 Bucket và tải dữ liệu  <br>&emsp; + Bật tính năng static website  <br>&emsp; + Cấu hình Block Public Access và Public Object  <br>&emsp; + Kiểm tra Website  <br>&emsp; + Tăng tốc Static Website với Cloudfront  <br>&emsp; + Bucket Versioning  <br>&emsp; + Di chuyển Object và sao chép Object sang region khác | 20/10/2025 | 20/10/2025 | <https://000057.awsstudygroup.com/vi/> |
| 3   | - **Thực hành:** Triển khai FSx trên Windows: <br>&emsp; + Tạo môi trường thực hành <br>&emsp; + Tạo một SSD và một HDD Multi-AZ file system <br>&emsp; + Tạo file share <br>&emsp; + Kiểm tra và giám sát hiệu năng <br>&emsp; + Kích hoạt chống dữ liệu trùng lặp <br>&emsp; + Kích hoạt shadow copies <br>&emsp; + Quản lý Session người dùng và mở tệp <br>&emsp; + Kích hoạt hạn ngạch bộ nhớ của người dùng <br>&emsp; + Kích hoạt chia sẻ truy cập liên tục <br>&emsp; + Mở rộng khả năng thông lượng và dung lượng lưu trữ | 21/10/2025 | 21/10/2025 | <https://000025.awsstudygroup.com/vi/> |
| 4   | - Học về Share Responsibility Model <br> - Tìm hiểu về AWS Identity and Access Management (IAM): <br>&emsp; + Root Account <br>&emsp; + IAM là gì? <br>&emsp; + IAM Principal <br>&emsp; + IAM Policy <br>&emsp; + IAM Role | 22/10/2025 | 22/10/2025 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> <br> <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Học về Amazon Cognito <br> - Học về AWS Organization <br> - Học về Identity Center (SSO) <br> - Học về AWS KMS <br> - Học về AWS Security Hub | 23/10/2025 | 23/10/2025 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> <br> <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Proposal:** Giúp Leader hoàn thành sơ đồ kiến trúc của dự án | 24/10/2025 | 24/10/2025 | |


### Kết quả đạt được tuần 7:

* **Thành thạo Amazon S3 với các tính năng nâng cao:**
  * Tạo S3 Bucket và upload dữ liệu thành công
  * Bật tính năng Static Website Hosting để host website tĩnh
  * Cấu hình Block Public Access và Public Object policies
  * Tích hợp CloudFront để tăng tốc độ truy cập website toàn cầu
  * Kích hoạt Bucket Versioning để quản lý phiên bản object
  * Thực hiện di chuyển và sao chép object giữa các region
  * Hiểu về S3 lifecycle policies và storage classes

* **Triển khai thành công Amazon FSx for Windows:**
  * Tạo môi trường thực hành với VPC và Active Directory
  * Tạo SSD và HDD Multi-AZ file system để đảm bảo high availability
  * Tạo và quản lý file shares
  * Kiểm tra và giám sát hiệu năng file system
  * Kích hoạt data deduplication để tối ưu hóa storage
  * Kích hoạt shadow copies cho point-in-time recovery
  * Quản lý user sessions và open files
  * Kích hoạt user storage quotas
  * Kích hoạt continuously available shares
  * Mở rộng throughput capacity và storage capacity

* **Nắm vững về Security và Identity Management:**
  * **Shared Responsibility Model:** Hiểu rõ trách nhiệm bảo mật giữa AWS và khách hàng
  * **AWS IAM:** Nắm vững về quản lý danh tính và quyền truy cập
    * Root Account và best practices
    * IAM Users, Groups, Roles
    * IAM Policies (identity-based và resource-based)
    * IAM Principal
  * **Amazon Cognito:** Hiểu về dịch vụ xác thực người dùng cho ứng dụng
  * **AWS Organizations:** Biết cách quản lý nhiều tài khoản AWS
  * **Identity Center (SSO):** Hiểu về single sign-on cho AWS
  * **AWS KMS:** Nắm rõ về quản lý khóa mã hóa
  * **AWS Security Hub:** Biết cách tổng hợp và quản lý security findings

* **Đóng góp vào dự án nhóm:**
  * Hỗ trợ Leader hoàn thiện sơ đồ kiến trúc hệ thống
  * Áp dụng kiến thức về S3, CloudFront vào thiết kế dự án
  * Đề xuất các giải pháp bảo mật cho ứng dụng


