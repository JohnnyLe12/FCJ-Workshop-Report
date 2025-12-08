---
title: "Worklog Tuần 8"
date: 2025-09-10
weight: 1
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:

* Tìm hiểu về các khái niệm Database và các dịch vụ database của AWS
* Nắm vững Amazon RDS, Aurora, ElastiCache và Redshift
* Thực hành triển khai Amazon RDS với backup và restore
* Ôn tập và củng cố kiến thức cho kỳ thi giữa kỳ
* Hoàn thành kỳ thi giữa kỳ

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2   | -  Học về Database Concept <br> -  Học về Amazon RDS <br> -  Học về Amazon Aurora <br> -  Học về Amazon ElastiCache <br> -  Học về Amazon Redshift | 27/10/2025 | 27/10/2025 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> <br> <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Thực hành: Amazon Relational Database Service (Amazon RDS) <br>&emsp; + Tạo các services cần thiết: VPC, EC2 Security Group, RDS Security Group, DB Subnet Group <br>&emsp; + Tạo EC2 instance <br>&emsp; + Tạo RDS database instance <br>&emsp; + Triển khai ứng dụng <br>&emsp; + Backup và restore | 28/10/2025 | 28/10/2025 | <https://000005.awsstudygroup.com/vi/> |
| 4   | - Tập trung ôn tập và củng cố kiến thức cho kỳ thi giữa kì | 29/10/2025 | 29/10/2025 | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Tập trung ôn tập và củng cố kiến thức cho kỳ thi giữa kì | 30/10/2025 | 30/10/2025 | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Thi giữa kì | 31/10/2025 | 31/10/2025 |  |


### Kết quả đạt được tuần 8:

* **Nắm vững các khái niệm Database:**
  * Hiểu về Relational Database (RDBMS) và NoSQL Database
  * Biết sự khác biệt giữa OLTP và OLAP workloads
  * Nắm rõ các khái niệm: normalization, indexing, transactions, ACID properties

* **Hiểu sâu về các dịch vụ Database của AWS:**
  * **Amazon RDS:** Dịch vụ relational database được quản lý hoàn toàn
    * Hỗ trợ nhiều database engines: MySQL, PostgreSQL, MariaDB, Oracle, SQL Server
    * Multi-AZ deployment cho high availability
    * Read replicas cho scaling reads
    * Automated backups và manual snapshots
  * **Amazon Aurora:** Database tương thích MySQL/PostgreSQL với hiệu năng cao
    * Tốc độ nhanh hơn 5x MySQL và 3x PostgreSQL
    * Auto-scaling storage
    * Aurora Serverless cho workloads không thường xuyên
  * **Amazon ElastiCache:** In-memory caching service
    * Hỗ trợ Redis và Memcached
    * Cải thiện performance của ứng dụng
  * **Amazon Redshift:** Data warehouse cho phân tích dữ liệu lớn
    * Columnar storage
    * Massively parallel processing (MPP)

* **Thực hành thành công với Amazon RDS:**
  * Tạo VPC và các thành phần mạng cần thiết
  * Tạo EC2 Security Group và RDS Security Group với các rules phù hợp
  * Tạo DB Subnet Group cho Multi-AZ deployment
  * Tạo EC2 instance làm application server
  * Tạo RDS database instance với cấu hình tối ưu
  * Triển khai ứng dụng kết nối đến RDS
  * Thực hiện backup database (automated và manual snapshot)
  * Restore database từ snapshot
  * Hiểu về RDS maintenance windows và parameter groups

* **Hoàn thành kỳ thi giữa kỳ:**
  * Ôn tập và củng cố kiến thức về các dịch vụ AWS đã học
  * Nắm vững các khái niệm: VPC, EC2, S3, RDS, IAM, CloudFormation
  * Hiểu về best practices và use cases của từng dịch vụ
  * Hoàn thành kỳ thi giữa kỳ thành công


