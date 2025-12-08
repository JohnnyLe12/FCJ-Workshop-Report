---
title: "Worklog Tuần 9"
date: 2025-09-10
weight: 1
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:

* Tìm hiểu về AWS Rekognition - dịch vụ AI/ML cho xử lý hình ảnh và video
* Khám phá các demo và tính năng của AWS Rekognition
* Triển khai tính năng Detect Labels vào dự án Travel Guide
* Tối ưu hóa chức năng Detect Labels với khả năng lọc labels
* Kiểm tra và đảm bảo chức năng hoạt động tốt trên website

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --------- | ------------ | --------------- | -------------- |
| 2   | - Tìm hiểu về AWS Rekognition  | 03/11/2025 | 03/11/2025 | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Kiểm tra các demo của AWS Rekogniton | 04/11/2025 | 04/11/2025 | <https://docs.aws.amazon.com/rekognition/> |
| 4   | - Bắt đầu triển khai Detect Labels của AWS Rekognition vào dự án | 05/11/2025 | 05/11/2025 |  |
| 5   | - Triển khai lại Detect Labels với chức năng lọc labels | 14/08/2025 | 06/11/2025 |  |
| 6   | - Kiểm tra chức năng Detect Labels trên website | 07/11/2025 | 07/11/2025 |  |


### Kết quả đạt được tuần 9:

* **Nắm vững AWS Rekognition:**
  * Hiểu về dịch vụ AI/ML của AWS cho computer vision
  * Biết các tính năng chính:
    * Object and scene detection (Detect Labels)
    * Facial analysis và face comparison
    * Text detection trong hình ảnh (Detect Text)
    * Content moderation
    * Celebrity recognition
    * Video analysis
  * Hiểu về confidence scores và cách sử dụng
  * Nắm rõ pricing model và best practices

* **Khám phá và test AWS Rekognition:**
  * Thử nghiệm các demo có sẵn của AWS Rekognition
  * Kiểm tra độ chính xác của các tính năng detection
  * Đánh giá khả năng áp dụng vào dự án Travel Guide
  * Hiểu về API calls và response format

* **Triển khai thành công Detect Labels vào dự án:**
  * Tích hợp AWS Rekognition SDK vào backend
  * Tạo Lambda function để xử lý hình ảnh
  * Cấu hình IAM roles và permissions cho Rekognition
  * Kết nối với S3 để lấy hình ảnh cần phân tích
  * Implement API endpoint để gọi Rekognition service

* **Tối ưu hóa chức năng Detect Labels:**
  * Triển khai lại với khả năng lọc labels theo confidence threshold
  * Thêm tính năng filter labels theo categories phù hợp với Travel Guide
  * Tối ưu hóa response time và error handling
  * Implement caching để giảm số lượng API calls
  * Xử lý các edge cases và error scenarios

* **Kiểm tra và đảm bảo chất lượng:**
  * Test chức năng Detect Labels trên website
  * Kiểm tra với nhiều loại hình ảnh khác nhau
  * Đảm bảo UI/UX hiển thị labels một cách trực quan
  * Verify performance và response time
  * Thu thập feedback để cải thiện


