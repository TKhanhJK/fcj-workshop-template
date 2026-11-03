---
title: "Worklog Tuần 2"
date: 2026-11-03
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu tuần 2:

* Hiểu về AWS Identity and Access Management (IAM) và vai trò của IAM trong việc bảo mật tài nguyên AWS.
* Nắm vững các khái niệm cơ bản về Amazon Virtual Private Cloud (VPC) và mạng trong AWS.
* Học cách tạo và cấu hình một VPC tùy chỉnh với Public Subnet và Private Subnet.
* Hiểu cách các EC2 instance giao tiếp trong VPC và kết nối ra Internet.
* Học cách quản lý tài nguyên mạng AWS thông qua cả AWS Management Console và AWS CLI.
* Áp dụng các phương pháp bảo mật cơ bản của AWS, bao gồm Security Groups, Network ACLs, IAM Roles và nguyên tắc đặc quyền tối thiểu (Principle of Least Privilege).

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Tìm hiểu về AWS Identity and Access Management (IAM). <br> - Nắm vững các khái niệm: <br>&emsp; + IAM Users và Groups <br>&emsp; + IAM Roles <br>&emsp; + IAM Policies <br>&emsp; + Xác thực đa yếu tố Multi-Factor Authentication (MFA) <br>&emsp; + Nguyên tắc đặc quyền tối thiểu (Principle of Least Privilege) <br> - **Thực hành:** <br>&emsp; + Khám phá IAM Dashboard. <br>&emsp; + Rà soát IAM Users, Roles và Policies. <br>&emsp; + Kiểm tra cấu hình MFA. | 03/11/2026 | — | [AWS Study Group – IAM](https://cloudjourney.awsstudygroup.com/vi/) |
| 3 | - Tìm hiểu các kiến thức cơ bản về Amazon VPC. <br> - Nắm vững các khái niệm: <br>&emsp; + VPC và CIDR <br>&emsp; + Public và Private Subnets <br>&emsp; + Availability Zones (AZ) <br>&emsp; + Internet Gateway (IGW) <br>&emsp; + Route Tables <br>&emsp; + NAT Gateway <br> - **Thực hành:** <br>&emsp; + Khám phá Default VPC. <br>&emsp; + Rà soát các thành phần mạng VPC hiện có. <br>&emsp; + Vẽ sơ đồ kiến trúc VPC cơ bản. | 04/11/2026 | — | [AWS Study Group – VPC](https://cloudjourney.awsstudygroup.com/vi/) |
| 4 | - Học cách tạo và cấu hình một custom VPC. <br> - Hiểu về định tuyến mạng (network routing) và cấu hình subnet. <br> - **Thực hành:** <br>&emsp; + Tạo custom VPC (CIDR: 10.0.0.0/16). <br>&emsp; + Tạo Public Subnet (10.0.1.0/24). <br>&emsp; + Tạo Private Subnet (10.0.2.0/24). <br>&emsp; + Tạo và gắn Internet Gateway vào VPC. <br>&emsp; + Cấu hình Route Tables cho public subnet. <br>&emsp; + Tìm hiểu Security Groups và Network ACLs. | 05/11/2026 | — | [The First Cloud Journey](https://cloudjourney.awsstudygroup.com/vi/) |
| 5 | - Học cách triển khai các EC2 instance bên trong custom VPC. <br> - Hiểu mối liên hệ giữa EC2 và mạng VPC. <br> - Tìm hiểu về IAM Roles dành cho EC2. <br> - **Thực hành:** <br>&emsp; + Khởi tạo EC2 instance trong Public Subnet. <br>&emsp; + Cấu hình các rule cho Security Group. <br>&emsp; + Kết nối tới EC2 instance qua SSH. <br>&emsp; + Tìm hiểu cách IAM Roles cấp quyền cho EC2 instance. <br>&emsp; + Kiểm tra kết nối mạng. | 06/11/2026 | — | [AWS Study Group – EC2 and IAM Roles](https://cloudjourney.awsstudygroup.com/vi/) |
| 6 | - Ôn tập các khái niệm AWS IAM và VPC. <br> - Phân biệt sự khác nhau giữa Security Groups và Network ACLs. <br> - Thực hành quản lý tài nguyên VPC bằng AWS CLI. <br> - **Thực hành:** <br>&emsp; + Liệt kê VPCs, Subnets và Route Tables bằng AWS CLI. <br>&emsp; + Truy xuất thông tin EC2 instance. <br>&emsp; + Xác minh cấu hình mạng và kết nối. <br>&emsp; + Rà soát cấu hình bảo mật. <br>&emsp; + Dọn dẹp các tài nguyên AWS không sử dụng. | 07/11/2026 | — | [AWS Study Group – The First Cloud Journey](https://cloudjourney.awsstudygroup.com/vi/) |

### Kết quả đạt được tuần 2:

* **Nền tảng AWS IAM:**
  * Hiểu rõ vai trò của IAM trong việc quản lý quyền truy cập và bảo mật tài nguyên AWS.
  * Phân biệt rõ sự khác nhau giữa IAM Users, Groups, Roles và Policies.
  * Nắm vững cơ chế MFA và nguyên tắc đặc quyền tối thiểu (Principle of Least Privilege).

* **Nền tảng mạng AWS (AWS Networking):**
  * Hiểu rõ khái niệm và mục đích của Amazon VPC.
  * Nắm vững các thành phần mạng chính:
    * VPC và dải mạng CIDR.
    * Public và Private Subnets.
    * Cổng Internet Gateway (IGW).
    * Bảng định tuyến (Route Tables).
    * NAT Gateway.
    * Security Groups và Network ACLs.

* **Thực hành triển khai VPC:**
  * Khám phá cấu hình Default VPC trên AWS.
  * Tạo và cấu hình thành công một custom VPC.
  * Cấu hình phân chia public và private subnets.
  * Gắn Internet Gateway và cấu hình bảng định tuyến kết nối Internet.
  * Kiểm thử kết nối mạng cơ bản thành công.

* **Thực hành EC2 & IAM Role:**
  * Khởi tạo thành công EC2 instance bên trong custom VPC.
  * Cấu hình Security Groups và kết nối thành công qua SSH.
  * Tìm hiểu và gán IAM Roles cho EC2 instance để cấp quyền an toàn.
  * Thực hành xử lý và kiểm tra kết nối mạng (network troubleshooting).

* **Thực hành với AWS CLI:**
  * Truy xuất thông tin về VPCs, subnets và route tables bằng dòng lệnh.
  * Quản lý và kiểm tra trạng thái tài nguyên AWS thông qua AWS CLI.
  * Nâng cao kỹ năng kết hợp linh hoạt giữa AWS Management Console và AWS CLI.

* **Kỹ năng & Kiến thức tổng hợp:**
  * Nâng cao hiểu biết về kiến trúc mạng, bảo mật và quản lý hạ tầng đám mây trên AWS.
  * Đạt được kinh nghiệm thực tế trong việc thiết kế và cấu hình hạ tầng mạng cơ bản trên Cloud.
