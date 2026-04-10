# Lab 01 Answers
## CIA & Risk: Hệ thống lưu điểm

**Họ và tên:** Đỗ Tiến Sơn

**MSSV:** 1871020508

**Lớp/Nhóm:** CNTT 18-01

---

## 1. Assets
Liệt kê ít nhất 2 assets cần bảo vệ.

- Asset 1: Dữ liệu sinh viên
- Asset 2: Hệ thống server lưu trữ và xử lý dữ liệu
- Asset 3 (nếu có):Tài khoản đăng nhập của giảng viên và quản trị viên

---

## 2. Mapping CIA
Ghép từng sự cố với CIA.

- Sự cố A ->Confidentiality
- Sự cố B ->Integrity
- Sự cố C ->Availability

---

## 3. Phân tích sự cố B
- Threat:Hacker hoặc người dùng nội bộ cố tình chỉnh sửa điểm.
- Vulnerability:Hệ thống không kiểm tra quyền truy cập chặt chẽ, 
                thiếu xác thực hoặc phân quyền rõ ràng.
- Mitigation:Áp dụng phân quyền người dùng, 
             xác thực nhiều lớp (2FA), 
             ghi log hoạt động và kiểm tra định kỳ dữ liệu.

---

## 4. Reflection
Viết 5-7 dòng.
Qua bài lab này, em hiểu rõ hơn về mô hình CIA trong bảo mật thông tin gồm bảo mật, toàn vẹn và sẵn sàng. Mỗi yếu tố đều rất quan trọng và có liên quan chặt chẽ với nhau trong hệ thống thực tế. Nếu thiếu một trong ba yếu tố thì hệ thống sẽ dễ gặp rủi ro. Ví dụ như nếu không đảm bảo toàn vẹn thì dữ liệu điểm có thể bị sửa sai, gây ảnh hưởng lớn. Ngoài ra, em cũng nhận ra việc xác định tài sản và phân tích rủi ro là bước rất quan trọng khi xây dựng hệ thống.
---

## 5. Bonus Flag
`FIT4012{A-?-B-?-C-?}`

Flag của em:
FIT4012{A-C-B-I-C-A}
