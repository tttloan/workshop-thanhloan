---
title: "Tuần 7: Hạ tầng & CI/CD"
date: 2025-02-12
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}

### Mục tiêu tuần 7:
* Thiết lập hạ tầng mạng VPC/EC2 cho hệ thống EduTrust.
* Triển khai hạ tầng dưới dạng mã (Infrastructure as Code - IaC).
* Cấu hình cân bằng tải (Load Balancer) và bảo mật SSL/HTTPS.

### Các công việc cần triển khai trong tuần này:
| Thứ | Ngày | Công việc |
| --- | --- | --- |
| 2 | 16/02 | Dùng Terraform dựng hạ tầng ASG + ALB cơ bản. |
| 3 | 17/02 | Cấu hình Cloudflare resolve DNS cho domain. |
| 4 | 18/02 | Hoàn thiện security group và health check. |
| 5 | 19/02 | Kiểm thử scale in/out cho ASG. |
| 6 | 20/02 | Tìm hiểu pipeline CI/CD cơ bản và nhu cầu dự án. |
| 7 | 21/02 | Phác thảo luồng CI/CD cho hạ tầng. |
| CN | 22/02 | Tổng kết tuần và cập nhật tài liệu hạ tầng. |

### Kết quả đạt được tuần 7:
* Hạ tầng mạng AWS được thiết lập bài bản theo mô hình chuẩn của đồ án.
* Hệ thống đạt chuẩn bảo mật HTTPS, sẵn sàng cho người dùng truy cập.
* Tự động hóa triển khai giúp quản lý tài nguyên linh hoạt hơn.
