---
title: "Worklog Tuần 2"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu tuần 2:

* Nắm vững kiến thức mạng cơ bản trên AWS (VPC, Subnet, Route Table, Internet Gateway).
* Thiết lập bảo mật cấp độ mạng với Network ACL và Security Group.
* Kết nối và định tuyến mạng giữa nhiều VPC thông qua VPC Peering và Transit Gateway.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu kiến trúc mạng cơ bản: <br> &emsp; + Khởi tạo VPC & Subnets  <br>     &emsp; + Cấu hình Internet Gateway                                                                              | 27/04/2026   | 27/04/2026      | <https://000003.awsstudygroup.com/> |
| 3   | - Phân quyền và bảo mật mạng: <br> &emsp; + Cấu hình Network ACLs <br> &emsp; + Setup Route Table Outbound                  | 28/04/2026   | 28/04/2026      | <https://000003.awsstudygroup.com/> |
| 4   | - Thực hành truy cập bảo mật: - Khởi tạo tài nguyên và kết nối: + Tạo EC2 Instance Connect Endpoint <br> &emsp; + Connect Remote Desktop Gateway (RDGW) và test kết quả   | 29/04/2026   | 29/04/2026      | <https://000010.awsstudygroup.com/> |
| 5   | - Khởi tạo tài nguyên và kết nối: <br> &emsp; + Tạo EC2 instances ở 2 VPC khác nhau <br> &emsp; + Thực hành VPC Peering, test ping và dọn dẹp | 30/04/2026   | 30/04/2026      | <https://000019.awsstudygroup.com/> |
| 6   | - Tạo Transit Gateway và các Attachments <br> - Cấu hình Route Tables kết nối 4 VPC, ping test và dọn dẹp tài nguyên                                                                                | 01/05/2026   | 01/05/2026      | <https://000020.awsstudygroup.com/> |


### Kết quả đạt được tuần 2:

* Phân biệt rõ sự khác nhau và cấu hình thành công Security Group, Network ACL.
* Setup thông tuyến an toàn bằng EC2 Connect Endpoint và RDGW mà không cần public IP.
* Triển khai kết nối VPC Peering (2 VPC) và AWS Transit Gateway đóng vai trò làm Cloud Router trung tâm (4 VPC).




