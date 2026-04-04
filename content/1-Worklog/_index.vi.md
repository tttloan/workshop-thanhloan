---
title: "Nhật ký công việc"
date: 2025-01-01
weight: 1
chapter: false
pre: " <b> 1. </b> "
---

{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}

Trong phần này, tôi sẽ ghi lại chi tiết quá trình thực hiện đồ án của mình trong vòng **12 tuần**. Mỗi tuần sẽ phản ánh các cột mốc quan trọng từ việc nghiên cứu đề tài, phân tích hệ thống, phát triển backend/frontend đến việc triển khai hạ tầng trên AWS.

Tóm tắt nội dung các tuần như sau:

**Tuần 1:** [Lần đầu lên "mây" với FCAJ Bootcamp](1.1-week1/) - Kick-off FCAJ, lập team, setup worklog, AWS IAM (tạo user, group, role, policy cho user và service).

**Tuần 2:** [Tìm hiểu mạng & kết nối](1.2-week2/) - Tìm hiểu VPC, EC2, Session Manager và các hình thức kết nối (VPC peering, hybrid, SSH, SSM connection, endpoint).

**Tuần 3:** [Backup & Chi phí](1.3-week3/) - Tạo backup plan, budget, CLI, tìm hiểu về chi phí và cách tối ưu chi phí.

**Tuần 4:** [S3 & Static Web](1.4-week4/) - S3, cài đặt Static Web bằng S3 + brainstorm topic project.

**Tuần 5:** [Giám sát & Bảo mật](1.5-week5/) - AWS Cloudtrail, Cloudwatch, Grafana, WAF (các biện pháp giám sát, trực quan hóa log và tường lửa).

**Tuần 6:** [IaC & Container](1.6-week6/) - Tìm hiểu IaC (Cloudformation + Terraform), Docker và AWS ECR.

**Tuần 7:** [Hạ tầng & CI/CD](1.7-week7/) - Dùng IaC (Terraform) build hạ tầng đơn giản cho dự án (ASG + ALB + Cloudflare resolve DNS) + tìm hiểu CI/CD.

**Tuần 8:** [Packer & Hạ tầng backend](1.8-week8/) - Tìm hiểu và thực hành sử dụng Packer để đồng độ OS qua việc snapshot AMI và sử dụng user data để đồng bộ version, package, lên kế hoạch vẽ architect, dùng CI/CD tạo hạ tầng backend, network và monitor.

**Tuần 9:** [Native AWS & Front-end](1.9-week9/) - Thay Cloudflare bằng Route53 tăng tính native AWS, tìm hiểu Amplify và hosting Front-end, thay JWT thủ công qua Cognito để tích hợp thêm việc quản lí user pool, user group, viết workshop.

**Tuần 10:** [Hoàn thiện kiến trúc](1.10-week10/) - Hoàn thiện kiến trúc CD/CD, AWS architect của dự án, tối ưu luồng sử lí từ client đến server, hoàn thiện workshop.

**Tuần 11:** [Tối ưu & Pentest](1.11-week11/) - Tối ưu chi phí các dịch vụ, cải thiện report, lên kế hoạch và pentest ứng dụng.

**Tuần 12:** [Thuyết trình](1.12-week12/) - Làm slide thuyết trình, test lại mọi tính năng của project, rehearsal và thuyết trình kết thúc bootcamp FCAJ.
