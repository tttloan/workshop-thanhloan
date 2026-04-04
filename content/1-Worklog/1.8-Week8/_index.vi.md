---
title: "Tuần 8: Packer & Hạ tầng backend"
date: 2025-02-19
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}

### Mục tiêu tuần 8:
* Xây dựng module quản lý và báo cáo kết quả thi của sinh viên.
* Tích hợp dịch vụ gửi thông báo tự động (Amazon SES).
* Tối ưu hóa hiệu năng truy xuất dữ liệu từ MongoDB.

### Các công việc cần triển khai trong tuần này:
| Thứ | Ngày | Công việc |
| --- | --- | --- |
| 2 | 23/02 | Tìm hiểu Packer và quy trình build AMI snapshot. |
| 3 | 24/02 | Thực hành tạo AMI và đồng bộ OS thông qua snapshot. |
| 4 | 25/02 | Sử dụng user data để đồng bộ version và package. |
| 5 | 26/02 | Lên kế hoạch vẽ AWS architect cho hệ thống. |
| 6 | 27/02 | Thiết kế CI/CD tạo hạ tầng backend và network. |
| 7 | 28/02 | Bổ sung monitoring cho hạ tầng từ CI/CD. |
| CN | 01/03 | Tổng kết tuần, rà soát các bước chuẩn hóa AMI. |

### Kết quả đạt được tuần 8:
* Hệ thống có khả năng quản lý và xuất dữ liệu báo cáo chuyên nghiệp.
* Tự động hóa quy trình thông báo kết quả thi qua Email.
* Tốc độ truy xuất dữ liệu tăng đáng kể nhờ tích hợp Redis Caching.
