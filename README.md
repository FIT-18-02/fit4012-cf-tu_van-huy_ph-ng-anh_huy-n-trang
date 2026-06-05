
# Bài Tập Lớn: CF11 - Broken Authentication (Xác Thực Bị Lỗi)
**Môn học:** FIT4012 Cyber Fortress  
**Sinh viên thực hiện:** Phạm Anh Tú, Nguyễn Văn Huy, Phạm Phương Anh, Dương Thị Huyền Trang
**Lớp:** CNTT 18 - 02  

---

## 1. Giới thiệu đề tài
Dự án giả lập một Hệ thống Quản lý Bài tập cục bộ (Local App) nhằm minh họa lỗ hổng **Broken Authentication** thuộc danh mục OWASP Top 10, cụ thể bao gồm hai lỗi logic phổ biến:
- Không giới hạn số lần đăng nhập sai (Thiếu Rate Limiting/Lockout) dẫn đến nguy cơ bị tấn công Brute-force đoán mật khẩu.
- Đăng xuất không hủy phiên (Session) trên Server, cho phép kẻ tấn công tái sử dụng Session token để truy cập trái phép.

## 2. Công cụ sử dụng
- Ngôn ngữ: Python 3
- Framework: Flask (Backend & Session Management)
- Giao diện: Bootstrap 5 (Responsive UI)

## 3. Cấu trúc thư mục nộp bài
```text
CF11-Broken-Authentication/
├── README.md
├── threat-model.md
├── ethics-safe-use.md
├── slides/
│   └── cyber-fortress-slides.pdf
├── demo/
│   └── app.py
└── evidence/
    ├── before.png
    ├── after.png
    └── logs.txt
=======
[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/EKjMbdn6)
Mô tả đề tài, công cụ, cách chạy demo, tài khoản giả lập nếu có.
>>>>>>> 467e36a1007971eda4e50dc9c9cc1b59b609c416
**## 4. Chấm Điểm của nhóm 1 cho **
link exel chấm: https://onedrive.live.com/:x:/g/personal/E2EDEF1D54857181/IQA6-xFkixM0Qb4I6HUqFakmAbPb_9xTMVsnebNdcxo_2tg?resid=E2EDEF1D54857181!s6411fb3a138b4134be08e8752a15a926&ithint=file%2Cxlsx&e=AzKUwz&migratedtospo=true&redeem=aHR0cHM6Ly8xZHJ2Lm1zL3gvYy9lMmVkZWYxZDU0ODU3MTgxL0lRQTYteEZraXhNMFFiNEk2SFVxRmFrbUFiUGJfOXhUTVZzbmViTmRjeG9fMnRnP2U9QXpLVXd6


