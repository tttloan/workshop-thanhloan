---
title: "Tuần 5: Giám sát & Bảo mật"
date: 2025-01-29
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---
{{% notice warning %}}
⚠️ **Lưu ý:** Các thông tin dưới đây chỉ nhằm mục đích tham khảo, vui lòng **không sao chép nguyên văn** cho bài báo cáo của bạn kể cả warning này.
{{% /notice %}}

### Mục tiêu tuần 5:
* Nghiên cứu tích hợp mô hình YOLO để giám sát camera phòng thi.
* Thiết kế kiến trúc AI Agentic Workflow cho chatbot hỗ trợ học tập.
* Thực hiện thử nghiệm nhận diện vật thể cơ bản (điện thoại, khuôn mặt).

### Các công việc cần triển khai trong tuần này:
| Thứ | Ngày | Công việc |
| --- | --- | --- |
| 2 | 02/02 | Bật và cấu hình AWS CloudTrail cho auditing. |
| 3 | 03/02 | Thiết lập CloudWatch log/metrics và alarm cơ bản. |
| 4 | 04/03 | Kết nối Grafana để trực quan hóa log/metrics. |
| 5 | 05/02 | Xây dựng dashboard giám sát theo service. |
| 6 | 06/02 | Tìm hiểu và cấu hình WAF bảo vệ lớp ứng dụng. |
| 7 | 07/02 | Kiểm thử rule WAF và cảnh báo bất thường. |
| CN | 08/02 | Tổng kết tuần, chuẩn hóa quy trình monitoring. |

### Kết quả đạt được tuần 5:
* Xác định được mô hình YOLO phù hợp cho việc giám sát thi.
* Kiến trúc Chatbot đa tác vụ (Multi-agent) đã được định hình rõ nét.
* Hiểu rõ cơ chế capture frame và gửi dữ liệu ảnh từ trình duyệt.
