---
title: "Worklog Tuần 5"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

* Nắm vững cơ chế phân quyền, quản lý định danh (IAM) và bảo mật dữ liệu (KMS) trên AWS.
* Thực hành tự động hóa tài nguyên (dùng Lambda quản lý EC2, tích hợp Slack) và giám sát hệ thống (CloudTrail, Athena).

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Tìm hiểu và thực hành cấu hình bảo mật cơ bản, thiết lập môi trường AWS an toàn ban đầu. | 18/05/2026 | 18/05/2026 | <https://000018.awsstudygroup.com/> |
| 3 | - Khởi tạo VPC, Security Group, EC2 và thiết lập Webhook gửi thông báo về Slack. <br> - Viết IAM Role cho Lambda. Tạo các hàm Lambda để tự động tắt (Stop) và bật (Start) EC2. | 19/05/2026 | 19/05/2026 | <https://000027.awsstudygroup.com/> <br> <br> <https://000022.awsstudygroup.com/> |
| 4 | - Tạo IAM User, thiết lập Policy/Role và thử tính năng Switch Roles.  <br> - Truy cập console đa Region, kiểm tra sự chặt chẽ của Policy khi thiếu Tag hợp lệ. | 20/05/2026 | 20/05/2026 | <https://000028.awsstudygroup.com/> |
| 5 | - Tạo Restriction Policy, tài khoản IAM Limited User và kiểm thử giới hạn. <br> - Tạo Policy, Group, S3 Bucket và mã hóa với AWS KMS. Thiết lập AWS CloudTrail và dùng Amazon Athena truy vấn nhật ký. <br> - Thực hiện kiểm tra và chia sẻ dữ liệu đã được mã hóa trên không gian lưu trữ S3. | 21/05/2026 | 21/05/2026 | <https://000030.awsstudygroup.com/> <br> <br> <https://000033.awsstudygroup.com/> |
| 6 | - Khởi tạo IAM Group, IAM Users, kiểm tra quyền hạn. Tạo Admin IAM Role và chuyển đổi vai trò (Switch role), giới hạn Switch role theo IP và thời gian, dọn dẹp tài nguyên. <br> - Khởi tạo EC2, S3 bucket, tạo người dùng IAM mới và Access Key. Sử dụng Access Key và giải pháp bảo mật hơn bằng cách dùng IAM Role gán cho EC2. | 22/05/2026 | 22/05/2026 | <https://000044.awsstudygroup.com/> <br> <br> <https://000048.awsstudygroup.com/> |

### Kết quả đạt được tuần 5:

* Thao tác thuần thục việc cấp quyền và quản lý tài khoản qua IAM (Policy, Role, Switch Roles).
* Tự động hóa thành công việc Stop/Start máy chủ EC2 bằng Lambda và cấu hình nhận thông báo qua Slack.
* Cấu hình mã hóa bảo mật dữ liệu an toàn với KMS và biết cách truy vấn nhật ký hoạt động bằng CloudTrail, Athena.



