---
title: "Worklog Tuần 3"
date: 2025-09-10
weight: 1
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:

* Tìm hiểu các phương pháp kết nối giữa các VPC và mạng on-premises:
  * VPC Peering - kết nối trực tiếp giữa hai VPC
  * Transit Gateway - kết nối tập trung cho nhiều VPC
  * Direct Connect Gateway - kết nối chuyên dụng từ on-premises
  * VPN Site-to-Site - kết nối VPN từ mạng on-premises
  * VPN Client-to-Site - kết nối VPN cho máy khách cá nhân

* Nắm vững các loại Load Balancer trong AWS:
  * Application Load Balancer (ALB)
  * Network Load Balancer (NLB)
  * Classic Load Balancer (CLB)
  * Gateway Load Balancer (GWLB)

* Thực hành tạo và cấu hình EC2 instances với các tính năng advanced.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2   | - Học về VPC Peering <br> - Học về Transit Gateway | 15/09/2025 | 15/09/2025 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> <br> <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Học về Direct Connect Gateway <br> - Học về VPN Site to Site: <br>&emsp; + Virtual Private Gateway <br>&emsp; + Customer Gateway <br> - Học về VPN Client to Site | 23/09/2025 | 23/09/2025 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> <br> <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Học về Elastic Load Balancing: <br>&emsp; + Application Load Balancer <br>&emsp; + Network Load Balancer <br>&emsp; + Classic Load Balancer <br>&emsp; + Gateway Load Balancer | 24/09/2025 | 24/09/2025 | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i> <br> <https://cloudjourney.awsstudygroup.com/> |
| 5   | - **Thực hành:** <br>&emsp; + Tạo và cấu hình EC2 instance <br>&emsp; + Kiểm tra kết nối giữa các instance | 25/09/2025 | 25/09/2025 | <https://000003.awsstudygroup.com/> |
| 6   | - **Thực hành:** <br>&emsp; + Tạo Multi-AZ NAT Gateway <br>&emsp; + Tạo EC2 Instance Connect Endpoint | 26/09/2025 | 26/09/2025 | <https://000003.awsstudygroup.com/> |


### Kết quả đạt được tuần 3:

* **Hiểu rõ các phương pháp kết nối VPC nâng cao:**
  * **VPC Peering:** Biết cách kết nối trực tiếp giữa hai VPC để cho phép lưu lượng mạng riêng tư
  * **Transit Gateway:** Hiểu cách sử dụng Transit Gateway làm trung tâm kết nối cho nhiều VPC và mạng on-premises
  * **Direct Connect Gateway:** Nắm rõ cách thiết lập kết nối chuyên dụng từ mạng on-premises đến AWS

* **Nắm vững các phương pháp VPN trên AWS:**
  * **VPN Site-to-Site:** Hiểu cách kết nối toàn bộ mạng on-premises với VPC
    * Virtual Private Gateway (VGW)
    * Customer Gateway (CGW)
  * **VPN Client-to-Site:** Biết cách cho phép máy khách cá nhân kết nối an toàn đến VPC

* **Thành thạo về Elastic Load Balancing:**
  * **Application Load Balancer (ALB):** Hiểu cách sử dụng cho các ứng dụng web, có khả năng định tuyến theo URL/hostname
  * **Network Load Balancer (NLB):** Biết cách sử dụng cho lưu lượng ultra-high performance và low latency
  * **Classic Load Balancer (CLB):** Hiểu loại load balancer cơ bản cho các ứng dụng legacy
  * **Gateway Load Balancer (GWLB):** Nắm rõ cách sử dụng cho các appliance ảo

* **Thực hành thành công với EC2:**
  * Tạo và cấu hình EC2 instances với các cài đặt phù hợp
  * Kiểm tra kết nối mạng giữa các EC2 instances
  * Triển khai Multi-AZ architecture để đảm bảo high availability
  * Tạo NAT Gateway cho phép instances kết nối ra ngoài
  * Sử dụng EC2 Instance Connect Endpoint để truy cập an toàn

* **Kiến thức tổng hợp:**
  * Hiểu cách thiết kế hạ tầng kết nối phức tạp trên AWS
  * Nắm rõ cách lựa chọn phương pháp kết nối phù hợp cho từng trường hợp
  * Biết cách cân bằng tải và tối ưu hóa performance của ứng dụng



