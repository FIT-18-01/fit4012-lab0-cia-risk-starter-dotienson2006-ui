# FIT4012 - Report 1 Page
## Lab 01 - CIA & Risk: Hệ thống lưu điểm

### 1. Mục tiêu bài lab
- Nhận diện tài sản cần bảo vệ trong một hệ thống thông tin đơn giản.
- Phân biệt Confidentiality, Integrity, Availability.
- Xác định threat, vulnerability, mitigation.
- Thực hành workflow GitHub cơ bản để nhận và nộp bài.

### 2. Cách làm
- Đọc bối cảnh và xác định các thành phần quan trọng của hệ thống.
- Phân tích từng sự cố theo bộ ba CIA.
- Chọn sự cố B để phân tích sâu hơn theo threat - vulnerability - mitigation.
- Hoàn thiện bài làm trong repo và commit/push lên GitHub.

### 3. Kết quả chính
**Assets:**
- Dữ liệu sinh viên
- Hệ thống server và cơ sở dữ liệu lưu trữ

**CIA mapping:**
- Sự cố A -> Confidentiality
- Sự cố B -> Integrity
- Sự cố C -> Availability

**Phân tích sự cố B:**
- Threat: Người dùng nội bộ hoặc hacker cố ý chỉnh sửa điểm.
- Vulnerability: Phân quyền chưa chặt chẽ, thiếu kiểm soát truy cập và xác thực.
- Mitigation: Áp dụng phân quyền rõ ràng, 
              xác thực nhiều lớp (2FA), 
              ghi log và kiểm tra dữ liệu thường xuyên.

### 4. Kết luận ngắn
(4-6 dòng: em học được gì từ bài lab này, phần nào khó nhất, điều gì cần chú ý khi phân tích một sự cố an toàn thông tin.)
Sau khi làm bài lab này, em hiểu rõ hơn về ba yếu tố CIA và tầm quan trọng của chúng trong hệ thống lưu điểm. Em nhận thấy nếu không kiểm soát tốt thì dữ liệu rất dễ bị sai lệch hoặc bị lộ. Phần khó nhất là xác định chính xác mỗi sự cố thuộc yếu tố nào. Qua đó, em rút ra rằng khi phân tích an toàn thông tin cần nhìn cả từ góc độ hệ thống lẫn người sử dụng để đưa ra giải pháp hợp lý.