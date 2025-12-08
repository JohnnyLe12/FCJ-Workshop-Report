---
title: "Worklog Tuần 10"
date: 2025-09-10
weight: 2
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:

* Tìm hiểu về Amazon SQS (Simple Queue Service) - dịch vụ message queue
* Thực hành với các demo của SQS để hiểu cách hoạt động
* Triển khai SQS vào dự án để xử lý bất đồng bộ
* Kiểm tra tích hợp SQS giữa các Lambda functions
* Đảm bảo xử lý ảnh theo trình tự với SQS
* Tham gia sự kiện AWS Cloud Mastery Series #1

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2   | - Tìm hiểu về SQS | 10/11/2025 | 10/11/2025 | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Tìm hiểu thêm về SQS <br> - Test các demo của SQS | 11/11/2025 | 11/11/2025 | <https://cloudjourney.awsstudygroup.com/> <br> <https://000083.awsstudygroup.com/vi/> |
| 4   | - Bắt đầu triển khai SQS vào trong dự án | 12/11/2025 | 12/11/2025 |  |
| 5   | - Kiểm tra SQS giữa các chức năng lambda trong dự án | 13/11/2025 | 13/11/2025 |  |
| 6   | - Kiểm tra xử lý ảnh theo trình tự SQS | 14/11/2025 | 14/11/2025 |  |
| 7   | - Tham gia sự kiện AWS Cloud Mastery Series #1 | 15/11/2025 | 15/11/2025 | <https://luma.com/imkevnow?tk=v3n25y> |


### Kết quả đạt được tuần 10:

* **Nắm vững Amazon SQS:**
  * Hiểu về message queue và asynchronous processing
  * Biết sự khác biệt giữa Standard Queue và FIFO Queue
  * Nắm rõ các khái niệm:
    * Message retention period
    * Visibility timeout
    * Dead Letter Queue (DLQ)
    * Long polling vs Short polling
    * Message deduplication
  * Hiểu về use cases: decoupling microservices, buffering requests, load leveling

* **Thực hành với SQS demos:**
  * Test tạo và cấu hình SQS queues
  * Gửi và nhận messages qua console và CLI
  * Thử nghiệm với visibility timeout
  * Kiểm tra Dead Letter Queue functionality
  * Đánh giá performance với different queue types

* **Triển khai thành công SQS vào dự án:**
  * Tích hợp SQS vào kiến trúc serverless
  * Tạo SQS queues cho xử lý ảnh bất đồng bộ
  * Cấu hình Lambda triggers từ SQS
  * Implement message producers và consumers
  * Setup IAM permissions cho SQS access

* **Tích hợp SQS với Lambda functions:**
  * Kiểm tra flow xử lý message giữa các Lambda functions
  * Đảm bảo error handling và retry logic
  * Implement Dead Letter Queue cho failed messages
  * Monitor queue metrics: messages in flight, age of oldest message
  * Optimize batch size và concurrency settings

* **Đảm bảo xử lý ảnh theo trình tự:**
  * Sử dụng FIFO queue để đảm bảo thứ tự xử lý
  * Implement message group ID cho ordering
  * Test với multiple images upload
  * Verify kết quả xử lý đúng thứ tự
  * Handle edge cases và race conditions

* **Tham gia sự kiện AWS Cloud Mastery Series #1:**
  * Học hỏi best practices từ AWS experts
  * Networking với cộng đồng AWS
  * Cập nhật kiến thức về các dịch vụ mới
  * Áp dụng insights vào dự án


