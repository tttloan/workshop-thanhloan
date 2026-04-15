---
title: "Event 3"
date: 2024-04-11
weight: 1
chapter: false
pre: " <b> 4.3. </b> "
---

# Bài thu hoạch "Cloud Mastery Series #3: Security"

### Thông tin sự kiện

- **Tên sự kiện**: Cloud Mastery Series #3: Security
- **Thời gian**: 09:00 – 12:00, April 11, 2026
- **Địa điểm**: FPTU - Hall Academic A
- **Vai trò**: Attendee

### Tóm tắt báo cáo

Buổi workshop "Cloud Mastery Series #3: Security" mang đến góc nhìn thực tế về cách xây dựng và vận hành hệ thống AWS an toàn hơn thông qua nhiều lớp bảo vệ, từ mạng, ứng dụng đến quản trị định danh và quyền truy cập.

### Mục tiêu sự kiện

- Hướng dẫn thiết lập và quản lý lưu lượng an toàn trong VPC thông qua Subnet, NAT Gateway, Security Group và NACL.
- Giới thiệu các giải pháp bảo vệ tầng ứng dụng và mạng lưới trước các cuộc tấn công khai thác web và DDoS.
- Triển khai quản lý định danh và quyền truy cập (IAM) theo các tiêu chuẩn bảo mật nâng cao.

### Diễn giả

- Lam An Thinh – DataXight Security Engineer Intern
- Nguyen Phan Quoc Viet – Networking on AWS Speaker
- Lam Tuan Kiet – DevOps, chuyên gia Network & Application Protection
- Huynh Hoang Long – FCAJ Cloud Engineer Ambassador
- Dang Thi Minh Thu – FCAJ Cloud Engineer Ambassador

### Điểm nổi bật

#### VPC & Network Security

**Subnet**: Việc phân chia phân mạng giống như quyết định kích thước cho một căn phòng khi xây dựng hệ thống.

**NAT Gateway**: Một dịch vụ được AWS quản lý giúp tài nguyên trong Private Subnet kết nối ra Internet nhưng ngăn chặn Internet khởi tạo kết nối ngược lại.
- **Cơ chế NAT**: Sử dụng SNAT (Source NAT) để thay thế IP riêng của Instance bằng IP công cộng của Gateway và PAT (Port Address Translation) để phân biệt lưu lượng.

**Security Group (SG) vs. Network ACL (NACL)**:
- SG hoạt động ở cấp độ Instance (ENI), có tính chất Stateful (nhớ trạng thái kết nối)
- NACL hoạt động ở cấp độ Subnet, có tính chất Stateless và hỗ trợ cả quy tắc Allow/Deny

#### Application Protection Layers

**AWS WAF**: Bảo vệ ứng dụng khỏi các lỗ hổng như SQL Injection và Cross-Site Scripting (XSS).

**AWS Shield**: Cung cấp hai cấp độ bảo vệ chống DDoS: Standard (miễn phí) và Advanced (nâng cao).

**AWS Firewall Manager**: Quản lý tập trung các chính sách bảo mật cho nhiều tài khoản AWS khác nhau.

#### Identity and Access Management (IAM)

**Nguyên tắc Least Privilege**: Chỉ cấp quyền tối thiểu cần thiết và tránh sử dụng ký tự "*" trong các Policy.

**Công cụ quản trị**: Sử dụng SCP để kiểm soát quyền tối đa trong tổ chức và Permission Boundary để giới hạn quyền cho từng User/Role cụ thể.

**Credential Security**: Khuyến khích sử dụng MFA, thay đổi mật khẩu định kỳ và dùng thông tin xác thực ngắn hạn từ STS thay vì Access Key dài hạn.

### Kết quả rút ra

- **Triết lý Zero Trust**: Luôn xác thực mọi kết nối, không mặc định tin tưởng bất kỳ lưu lượng nào.
- **Thiết kế phân lớp**: Bảo mật hiệu quả nhất khi được triển khai nhiều lớp, từ lớp Instance (SG), lớp Subnet (NACL) đến lớp ứng dụng (WAF).
- **Quản trị tập trung**: Việc sử dụng SSO và Firewall Manager giúp duy trì tính nhất quán về bảo mật trong môi trường đa tài khoản.

### Ứng dụng vào công việc

- **Tối ưu dự án EduTrust**: Áp dụng tư duy phân đoạn mạng (Segmentation) rõ ràng cho các tài nguyên để luồng dữ liệu sạch và an toàn hơn.
- **Rà soát quyền truy cập**: Kiểm tra lại các Policy của nhóm phát triển để loại bỏ các quyền dư thừa, đảm bảo tuân thủ nguyên tắc Least Privilege.
- **Bảo vệ dịch vụ công cộng**: Cân nhắc tích hợp AWS WAF trước Application Load Balancer (ALB) để ngăn chặn các cuộc tấn công web phổ biến.

### Trải nghiệm sự kiện

Buổi Workshop mang lại cái nhìn thực tế và toàn diện về bảo mật đám mây:

- **Demo trực quan**: Các ví dụ về cơ chế Stateless của NACL (phải mở cổng Ephemeral 1024-65535 cho lưu lượng phản hồi) giúp hiểu sâu hơn về luồng mạng.
- **Tính kết nối cao**: Việc kết hợp giữa Networking, Quản lý định danh và Firewall giúp mình hình dung được bức tranh bảo mật tổng thể thay vì chỉ là các công cụ rời rạc.

### Bài học rút ra

- Bảo mật phải được thiết kế ngay từ đầu (Security by Design), không phải là yếu tố bổ sung sau khi hệ thống đã chạy.
- Hiểu rõ sự khác biệt giữa Stateful và Stateless là chìa khóa để xử lý các sự cố mất kết nối mạng trong VPC.
- Sử dụng các công cụ tự động như IAM Access Analyzer để phát hiện các tài nguyên đang bị chia sẻ công khai ngoài ý muốn.

### Tổng kết

Workshop Cloud Mastery Series #3 đã cung cấp nền tảng vững chắc để mình có thể thiết kế các hệ thống trên AWS an toàn và có khả năng mở rộng tốt hơn, đặc biệt là trong việc quản trị rủi ro cho dự án EduTrust.

