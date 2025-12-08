---
title: "Worklog Tuần 6"
date: 2025-09-10
weight: 1
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6:

* Thực hành triển khai AWS Backup để bảo vệ dữ liệu
* Thực hành VM Import/Export để di chuyển máy ảo giữa on-premises và AWS
* Triển khai File Storage Gateway để kết nối storage on-premises với AWS
* Tham gia nhóm dự án và đề xuất ý tưởng
* Xác định chủ đề dự án nhóm: Travel Guide Web App

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2   | - **Thực hành:** Triển khai AWS Backup cho hệ thống <br>&emsp; + Tạo Backup plan <br>&emsp; + Thiết lập thông báo | 13/10/2025 | 13/10/2025 | <https://000013.awsstudygroup.com/vi/> |
| 3   | - **Thực hành:** VM Import/Export <br>&emsp; + Import máy ảo vào AWS <br>&emsp; + Export EC2 Instance từ AWS | 14/10/2025 | 14/10/2025 | <https://000014.awsstudygroup.com/vi/> |
| 4   | - **Thực hành:** Triển khai File Storage Gateway <br>&emsp; + Tạo Storage Gateway <br>&emsp; + Tạo File Shares <br>&emsp; + Kết nối File Shares ở máy On-premise | 15/10/2025 | 15/10/2025 | <https://000024.awsstudygroup.com/vi/> |
| 5   | - Tham gia vào nhóm và đề xuất ý tưởng cho dự án của nhóm | 16/10/2025 | 16/10/2025 | <https://www.datacamp.com/blog/top-aws-projects> |
| 6   | - **Proposal:** Quyết định làm về một web app với chủ đề Travel Guide. | 17/10/2025 | 17/10/2025 | |


### Kết quả đạt được tuần 6:

* **Triển khai thành công AWS Backup:**
  * Tạo Backup plan với các quy tắc sao lưu tự động
  * Cấu hình backup vault để lưu trữ các bản sao lưu
  * Thiết lập thông báo qua SNS khi backup hoàn thành hoặc thất bại
  * Hiểu cách restore dữ liệu từ backup
  * Nắm rõ các best practices về backup strategy

* **Thực hành thành công VM Import/Export:**
  * Import máy ảo từ môi trường on-premises vào AWS dưới dạng AMI hoặc EC2 instance
  * Hiểu các yêu cầu và giới hạn khi import VM (định dạng file, kích thước, OS)
  * Export EC2 instance từ AWS về môi trường on-premises
  * Nắm rõ quy trình di chuyển workload giữa các môi trường

* **Triển khai File Storage Gateway:**
  * Tạo và cấu hình Storage Gateway trong môi trường hybrid
  * Tạo File Shares để chia sẻ dữ liệu giữa on-premises và S3
  * Kết nối File Shares từ máy on-premises thông qua SMB/NFS protocol
  * Hiểu cách dữ liệu được đồng bộ giữa local cache và S3
  * Nắm rõ use cases của Storage Gateway trong kiến trúc hybrid

* **Khởi động dự án nhóm:**
  * Tham gia nhóm và làm quen với các thành viên
  * Đề xuất và thảo luận các ý tưởng dự án
  * Quyết định chủ đề dự án: Travel Guide Web Application
  * Xác định phạm vi và mục tiêu của dự án
  * Bắt đầu lên kế hoạch cho các giai đoạn phát triển


