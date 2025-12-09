---
title: "Bản đề xuất"
date: 2025-12-09
weight: 2
chapter: false
pre: " <b> 2. </b> "
---

Tại phần này, bạn cần tóm tắt các nội dung trong workshop mà bạn **dự tính** sẽ làm.

# Travel Journal Platform
## Giải pháp AWS Serverless cho quản lý và chia sẻ kỷ niệm du lịch

### 1. Tóm tắt điều hành
Nền tảng Travel Journal được phát triển bởi sinh viên Đại học FPT nhằm cho phép người dùng lưu trữ, quản lý và chia sẻ ảnh, thông tin du lịch và các địa điểm họ đã ghé thăm. Nền tảng tạo ra một cộng đồng chia sẻ trải nghiệm du lịch đồng thời cung cấp giao diện trực quan cho phép người dùng xem lại hành trình của mình thông qua dòng thời gian và bản đồ tương tác. Được xây dựng trên kiến trúc AWS Serverless, nền tảng mang lại khả năng mở rộng cao, bảo mật mạnh mẽ và tối ưu hóa chi phí với ước tính chi phí hàng tháng dưới 70 USD.

### 2. Tuyên bố vấn đề
#### Vấn đề hiện tại
Du khách thiếu một nền tảng tập trung để tổ chức và lưu giữ kỷ niệm du lịch của họ. Ảnh bị phân tán trên nhiều thiết bị, thông tin vị trí bị mất theo thời gian và không có cách dễ dàng để trực quan hóa lộ trình du lịch hoặc chia sẻ trải nghiệm với cộng đồng.

#### Giải pháp
Nền tảng Travel Journal tận dụng các dịch vụ AWS Serverless để cung cấp giải pháp toàn diện. Người dùng có thể tải ảnh du lịch lên Amazon S3, với Amazon Rekognition tự động nhận diện cảnh trong ảnh. Siêu dữ liệu và ghi chú du lịch được lưu trữ trong Amazon DynamoDB, trong khi Amazon Location Service trực quan hóa lộ trình du lịch trên bản đồ tương tác. Nền tảng sử dụng AWS Lambda và API Gateway để xử lý backend, với pipeline xử lý bất đồng bộ thông qua Amazon SQS để phân tích ảnh. Amazon Cognito cung cấp xác thực an toàn với MFA tùy chọn, và giao diện React được phân phối toàn cầu thông qua Amazon CloudFront với bảo vệ AWS WAF.

#### Lợi ích và hoàn vốn đầu tư
Nền tảng cung cấp cho sinh viên kinh nghiệm thực tế trong việc xây dựng ứng dụng serverless cấp production theo các nguyên tắc AWS Well-Architected Framework. Nó tạo ra một mẫu kiến trúc có thể tái sử dụng cho các ứng dụng tương tự và thể hiện giải pháp đám mây hiệu quả về chi phí. Với chi phí hàng tháng ước tính dưới 70 USD và pipeline CI/CD hoàn toàn tự động, nền tảng thể hiện các thực hành DevOps hiện đại đồng thời mang lại giá trị thực cho người dùng muốn lưu giữ và chia sẻ kỷ niệm du lịch của họ.

### 3. Kiến trúc giải pháp
Travel Journal được xây dựng sử dụng kiến trúc serverless hoàn toàn trên AWS, được tối ưu hóa cho khả năng mở rộng, hiệu quả chi phí và đơn giản hóa vận hành. Nội dung frontend tĩnh được lưu trữ trên Amazon S3 và phân phối toàn cầu thông qua Amazon CloudFront, với AWS WAF và ACM cung cấp bảo mật TLS và bảo vệ chống lại các mối đe dọa web phổ biến.

Người dùng tương tác với nền tảng thông qua ứng dụng web dựa trên React để tải ảnh, thêm ghi chú du lịch, gắn thẻ vị trí và xem bản đồ tương tác. Tất cả các tương tác backend được xử lý thông qua Amazon API Gateway, định tuyến các yêu cầu đã xác thực (qua Amazon Cognito) đến các hàm AWS Lambda. Ảnh được tải lên được lưu trữ trong Amazon S3, nơi các sự kiện tải lên kích hoạt Amazon SQS để điều phối xử lý bất đồng bộ. Lambda workers tiêu thụ các thông điệp này, phân tích ảnh thông qua Amazon Rekognition và lưu trữ kết quả trong Amazon DynamoDB.

### Dịch vụ AWS sử dụng
- **Amazon S3**: Lưu trữ ảnh đã tải lên và nội dung frontend tĩnh
- **Amazon CloudFront**: Phân phối nội dung toàn cầu với độ trễ thấp
- **AWS WAF & ACM**: Tường lửa ứng dụng web và quản lý chứng chỉ TLS
- **Amazon Cognito**: Xác thực người dùng với MFA tùy chọn
- **Amazon API Gateway**: Quản lý endpoint API RESTful
- **AWS Lambda**: Tính toán serverless cho logic nghiệp vụ
- **Amazon SQS**: Hàng đợi tin nhắn cho xử lý ảnh bất đồng bộ
- **Amazon DynamoDB**: Cơ sở dữ liệu NoSQL cho siêu dữ liệu và dữ liệu người dùng
- **Amazon Rekognition**: Phát hiện cảnh ảnh được hỗ trợ bởi AI
- **Amazon Location Service**: Trực quan hóa bản đồ tương tác và định vị địa lý
- **Amazon CloudWatch**: Giám sát, ghi log và cảnh báo
- **Amazon SNS**: Thông báo và cảnh báo hệ thống
- **AWS KMS**: Quản lý khóa mã hóa
- **AWS CodePipeline & CodeBuild**: Tự động hóa CI/CD

### Thiết kế thành phần
- **Frontend**: Ứng dụng React được lưu trữ trên S3, phân phối qua CloudFront
- **Xác thực**: Amazon Cognito quản lý đăng ký, đăng nhập và MFA của người dùng
- **Lớp API**: API Gateway định tuyến yêu cầu đến các hàm Lambda
- **Lưu trữ ảnh**: S3 lưu trữ ảnh đã tải lên với mã hóa khi lưu trữ
- **Xử lý bất đồng bộ**: Hàng đợi SQS kích hoạt Lambda workers để phân tích Rekognition
- **Lưu trữ dữ liệu**: DynamoDB lưu trữ siêu dữ liệu du lịch, ghi chú và thẻ vị trí
- **Trực quan hóa bản đồ**: Amazon Location Service hiển thị lộ trình du lịch và vị trí được gắn thẻ
- **Giám sát**: CloudWatch theo dõi các chỉ số hiệu suất và kích hoạt cảnh báo SNS

### 4. Triển khai kỹ thuật
**Các giai đoạn triển khai**
Dự án tuân theo framework Agile Scrum qua 8 sprint 2 tuần (tổng cộng 12 tuần):

- **Đánh giá (Tuần 1-4)**: Onboarding nhóm, đào tạo dịch vụ AWS (S3, Lambda, API Gateway, DynamoDB, Cognito, SQS, CloudFront, Rekognition, CloudWatch), quy trình Git/GitHub và khám phá yêu cầu
- **Thiết kế kiến trúc & Lập kế hoạch (Tuần 5)**: Phân tích use case, lặp lại thiết kế kiến trúc theo AWS Well-Architected Framework, định nghĩa phạm vi MVP và lập kế hoạch sprint
- **Thiết lập hạ tầng cơ bản (Tuần 6)**: Cấu hình IAM, MFA, CloudTrail, AWS Config, tạo các dịch vụ cốt lõi (S3, DynamoDB, API Gateway, Cognito, SQS), thiết lập CloudFront + ACM + WAF, xây dựng pipeline CI/CD và viết Infrastructure as Code sử dụng CloudFormation
- **Phát triển Backend (Tuần 7-8)**: Phát triển Lambda + API Gateway cho tải ảnh và quản lý chuyến đi, triển khai pipeline xử lý S3 → SQS → Lambda, tích hợp Rekognition, tối ưu hóa hiệu suất và chi phí
- **Phát triển Frontend (Tuần 8-9)**: Xây dựng giao diện React cho tải ảnh, dòng thời gian và trang chuyến đi, tích hợp xác thực Cognito, triển khai bản đồ tương tác sử dụng Amazon Location Service, triển khai lên S3 + CloudFront
- **Kiểm thử & Go-live (Tuần 10-11)**: Kiểm thử chức năng và tích hợp, cấu hình giám sát và cảnh báo CloudWatch, thực hiện kiểm thử tải, sửa lỗi và ổn định MVP
- **Bàn giao (Tuần 12)**: Chuẩn bị tài liệu, phiên chuyển giao kiến thức, demo cuối cùng và bàn giao dự án

**Yêu cầu kỹ thuật**
- **Frontend**: React, MapLibre/Leaflet cho bản đồ, AWS Location Maps SDK
- **Backend**: Hàm Lambda Node.js, API Gateway REST APIs
- **Hạ tầng**: AWS CDK hoặc CloudFormation cho IaC
- **CI/CD**: GitHub làm kho mã nguồn, CodePipeline và CodeBuild cho tự động hóa
- **Bảo mật**: Chính sách IAM least-privilege, mã hóa KMS, Cognito với MFA, quy tắc WAF
- **Giám sát**: CloudWatch Logs, Metrics, Alarms, X-Ray cho truy vết phân tán

### 5. Lộ trình & Mốc triển khai
**Lộ trình dự án (12 tuần)**

| Giai đoạn | Thời gian | Mốc chính |
|-----------|-----------|-----------|
| Đánh giá | Tuần 1-4 | Báo cáo sẵn sàng của nhóm, tóm tắt kiến thức AWS, tài liệu yêu cầu |
| Thiết kế kiến trúc | Tuần 5 | Sơ đồ kiến trúc cuối cùng, tài liệu thiết kế giải pháp, kế hoạch sprint |
| Hạ tầng cơ bản | Tuần 6 | Môi trường AWS sẵn sàng, pipeline CI/CD hoạt động, template IaC hoàn chỉnh |
| Phát triển Backend | Tuần 7-8 | Backend API v1, pipeline Rekognition hoạt động, DynamoDB được cấu trúc |
| Phát triển Frontend | Tuần 8-9 | React frontend v1, tính năng bản đồ và tải lên hoạt động, triển khai CloudFront |
| Kiểm thử & Go-live | Tuần 10-11 | Báo cáo kiểm thử, MVP ổn định, giám sát và cảnh báo được cấu hình |
| Bàn giao | Tuần 12 | Tài liệu hoàn chỉnh, phiên chuyển giao kiến thức, demo cuối cùng |

### 6. Ước tính ngân sách
**Chi phí hạ tầng (Ước tính hàng tháng)**

Dựa trên các giả định sử dụng vừa phải:
- 5.000-10.000 lượt tải ảnh lên mỗi tháng
- Kích thước ảnh trung bình: 2-4 MB
- Triển khai trong một AWS Region duy nhất
- CloudFront: 50-100 GB/tháng lưu lượng ra
- DynamoDB: Chế độ dung lượng On-Demand
- CloudWatch Logs: Lưu giữ 30 ngày

**Chi phí hàng tháng ước tính: Dưới 70 USD**

Các yếu tố chi phí chính:
- **Amazon S3**: Lưu trữ và yêu cầu cho ảnh và nội dung tĩnh
- **Amazon Rekognition**: Chi phí phân tích mỗi ảnh
- **Amazon CloudFront**: Phân phối nội dung toàn cầu
- **AWS Lambda**: Thời gian tính toán cho xử lý
- **Amazon DynamoDB**: Dung lượng đọc/ghi theo yêu cầu
- **Amazon Location Service**: Hiển thị bản đồ và mã hóa địa lý
- **Các dịch vụ khác**: API Gateway, SQS, CloudWatch, SNS (chi phí tối thiểu)

**Chi phí phát triển**

| Nguồn lực | Giá (USD/giờ) | Tổng giờ | Tổng chi phí |
|-----------|---------------|----------|--------------|
| Solutions Architect (1) | $20 | 44 | $880 |
| Engineers - FE/BE/DevOps (4) | $12 | 228 | $2,736 |
| QA Engineer | $8 | 16 | $128 |
| **Tổng** | | **288** | **$3,744** |

### 7. Đánh giá rủi ro
#### Các rủi ro chính và giảm thiểu

**Vượt chi phí**
- **Rủi ro**: Chi phí Rekognition có thể vượt dự báo nếu lượt tải ảnh tăng đột biến
- **Giảm thiểu**: Triển khai cảnh báo AWS Budget, tối ưu hóa kích thước ảnh trước khi xử lý, đặt cảnh báo CloudWatch cho ngưỡng chi phí
- **Tác động**: Trung bình | **Xác suất**: Thấp

**Lỗ hổng bảo mật**
- **Rủi ro**: Chính sách IAM cấu hình sai hoặc S3 bucket bị lộ
- **Giảm thiểu**: Áp dụng chính sách IAM least-privilege, bật AWS Config để giám sát tuân thủ, kiểm tra bảo mật định kỳ
- **Tác động**: Cao | **Xác suất**: Thấp

**Vấn đề hiệu suất**
- **Rủi ro**: Tải ảnh chậm hoặc hiển thị bản đồ chậm do độ trễ mạng
- **Giảm thiểu**: Sử dụng CloudFront để phân phối toàn cầu, tối ưu hóa nén ảnh, triển khai tải tiến trình
- **Tác động**: Trung bình | **Xác suất**: Trung bình

**Độ chính xác Rekognition**
- **Rủi ro**: Kết quả phát hiện cảnh không chính xác ảnh hưởng đến trải nghiệm người dùng
- **Giảm thiểu**: Đặt ngưỡng độ tin cậy, cho phép sửa thủ công, cung cấp cơ chế phản hồi người dùng
- **Tác động**: Thấp | **Xác suất**: Trung bình

#### Kế hoạch dự phòng
- Template CloudFormation cho phép rollback nhanh các thay đổi hạ tầng
- Dead Letter Queue (DLQ) bảo toàn các thông điệp thất bại để điều tra
- Cảnh báo CloudWatch kích hoạt thông báo SNS để phản ứng sự cố ngay lập tức

### 8. Kết quả kỳ vọng

#### Tiêu chí thành công dự án
- **Uptime**: 99% khả dụng nền tảng thông qua kiến trúc serverless
- **Bảo mật**: Xác thực an toàn qua Cognito với MFA tùy chọn, mã hóa khi lưu trữ và truyền tải
- **Chi phí**: Chi phí hạ tầng hàng tháng dưới 70 USD
- **Tự động hóa**: 100% tự động hóa CI/CD cho build, test và triển khai
- **Giám sát**: Cảnh báo CloudWatch trong vòng 1 phút khi có lỗi hoặc vượt ngưỡng
- **Độ chính xác**: 95%+ độ chính xác trong hiển thị vị trí được gắn thẻ của người dùng trên bản đồ

#### Cải tiến kỹ thuật
- Kinh nghiệm thực tế với kiến trúc serverless AWS cấp production
- Hiểu biết về các nguyên tắc AWS Well-Architected Framework
- Kiến thức thực tế về tự động hóa CI/CD và thực hành DevOps
- Kinh nghiệm với phát triển frontend hiện đại (React) và backend (Lambda)

#### Giá trị dài hạn
- Mẫu kiến trúc có thể tái sử dụng cho các ứng dụng serverless tương tự
- Tài liệu toàn diện và runbook vận hành
- Nền tảng cho các cải tiến trong tương lai (ứng dụng di động, tính năng xã hội, đề xuất AI)
- Dự án portfolio thể hiện kỹ năng phát triển cloud-native
