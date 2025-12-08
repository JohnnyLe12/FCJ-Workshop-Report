---
title: "Worklog Tuần 4"
date: 2025-09-10
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---

### Mục tiêu tuần 4:

* Tìm hiểu về Route 53 - dịch vụ DNS và quản lý tên miền trên AWS
* Nắm vững AWS CloudFormation - công cụ Infrastructure as Code (IaC) để tự động hóa triển khai tài nguyên
* Tìm hiểu về AWS Directory Service - dịch vụ quản lý danh bạ tập trung
* Tìm hiểu về AWS Quick Starts - các mẫu triển khai nhanh
* Thực hành thiết lập Hybrid DNS với Route 53 Resolver
* Thực hành thiết lập VPC Peering với kích hoạt Cross-Peer DNS
* Thực hành triển khai AWS Transit Gateway (TGW) với các attachment và route tables

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2   | - Học về Route 53 <br> - Tìm hiểu về AWS Quick Starts <br> - Tìm hiểu về AWS CloudFormation <br> - Tìm hiểu về AWS Directory Service | 29/09/2025 | 29/09/2025 | <https://000010.awsstudygroup.com/vi/> <br> <https://000037.awsstudygroup.com/vi/> |
| 3   | - **Thực hành:** Thiết lập Hybrid DNS với Route 53 Resolver <br>&emsp; + Tạo keypair <br>&emsp; + Khởi tạo CloudFormation Template <br>&emsp; + Cấu hình Security Group <br>&emsp; + Kết nối đến máy chủ Remote Desktop Gateway (RDGW) <br>&emsp; + Triển khai Microsoft AD <br>&emsp; + Thiết lập DNS <br>&emsp; + Dọn dẹp tài nguyên | 30/09/2025 | 30/09/2025 | <https://000010.awsstudygroup.com/vi/> |
| 4   | - **Thực hành:** Thiết lập VPC Peering <br>&emsp; + Khởi tạo CloudFormation Template <br>&emsp; + Tạo Security Group và EC2 Instance <br>&emsp; + Cập nhật Network ACL <br>&emsp; + Tạo kết nối Peering <br>&emsp; + Kích hoạt Cross-Peer DNS <br>&emsp; + Dọn dẹp tài nguyên | 01/10/2025 | 01/10/2025 | <https://000019.awsstudygroup.com/vi/> |
| 5   | - Tìm hiểu thêm về Transit Gateway (TGW): <br>&emsp; + TGW Attachment <br>&emsp; + TGW Policy Tables <br>&emsp; + TGW Route Tables <br>&emsp; + TGW Multicast | 02/10/2025 | 02/10/2025 | <https://000020.awsstudygroup.com/vi/> |
| 6   | - **Thực hành:** Tổng quan về AWS Transit Gateway <br>&emsp; + Khởi tạo CloudFormation Template <br>&emsp; + Tạo Transit Gateway <br>&emsp; + Tạo Transit Gateway Attachment <br>&emsp; + Tạo Transit Gateway Route Table <br>&emsp; + Thêm Transit Gateway Routes vào VPC Route Tables <br>&emsp; + Dọn dẹp tài nguyên | 03/10/2025 | 03/10/2025 | <https://000020.awsstudygroup.com/vi/> |


### Kết quả đạt được tuần 4:

* **Nắm vững các dịch vụ DNS và quản lý trên AWS:**
  * **Route 53:** Hiểu cách sử dụng dịch vụ DNS được quản lý hoàn toàn bởi AWS
  * **Route 53 Resolver:** Biết cách thiết lập Hybrid DNS để kết nối DNS on-premises và AWS
  * Hiểu cách quản lý tên miền và các bản ghi DNS

* **Hiểu sâu về Infrastructure as Code (IaC):**
  * **AWS CloudFormation:** Nắm rõ cách sử dụng template để tự động hóa và quản lý tài nguyên AWS
  * Biết cách viết template CloudFormation để triển khai các kiến trúc phức tạp
  * Hiểu các thành phần chính: Resources, Parameters, Outputs, Conditions

* **Tìm hiểu về quản lý tài nguyên:**
  * **AWS Directory Service:** Hiểu cách sử dụng dịch vụ quản lý danh bạ tập trung
  * **AWS Quick Starts:** Biết cách tận dụng các mẫu triển khai nhanh có sẵn

* **Thực hành thành công Hybrid DNS Setup:**
  * Tạo keypair cho Remote Desktop Gateway (RDGW)
  * Triển khai CloudFormation template để tự động hóa cấu hình
  * Cấu hình Security Groups phù hợp
  * Triển khai Microsoft AD trên AWS
  * Thiết lập DNS Resolver cho kết nối Hybrid
  * Dọn dẹp tài nguyên sau khi hoàn thành

* **Thực hành thành công VPC Peering:**
  * Tạo Security Groups và EC2 instances cho các VPC
  * Cập nhật Network ACL để cho phép lưu lượng
  * Tạo kết nối VPC Peering giữa các VPC
  * Kích hoạt Cross-Peer DNS resolution
  * Kiểm tra kết nối giữa các VPC

* **Thực hành thành công Transit Gateway:**
  * Hiểu các thành phần Transit Gateway: Attachments, Route Tables, Routes
  * Triển khai Transit Gateway bằng CloudFormation
  * Tạo Transit Gateway attachments cho VPC
  * Cấu hình Transit Gateway route tables
  * Thêm routes vào VPC route tables để định tuyến thông qua TGW
  * Kiểm tra kết nối qua Transit Gateway

* **Kiến thức tổng hợp:**
  * Biết cách chọn giữa VPC Peering và Transit Gateway cho các trường hợp khác nhau
  * Hiểu cách thiết lập kiến trúc mạng phức tạp với đa VPC
  * Có khả năng tự động hóa triển khai bằng CloudFormation