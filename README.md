# 🔐 Offline TOTP Authenticator

TOTP Authenticator đơn giản, **chạy hoàn toàn offline** bằng HTML + JS thuần.  
Không yêu cầu cài đặt, không gửi dữ liệu ra mạng – chỉ cần mở file `.html` trong trình duyệt là dùng được.

## ✅ Tính năng chính

- 👥 Nhóm tài khoản theo mục (accordion có thể thu gọn)
- 🔍 Tìm kiếm theo tên hoặc nhóm
- ➕ Thêm tài khoản qua input hoặc quét ảnh QR
- 🕒 Hiển thị mã OTP (6 chữ số) tự động cập nhật mỗi 30s
- ⏳ Đếm ngược thời gian còn lại
- 📋 Nút **Copy OTP** nhanh
- ❌ Nút **Xoá tài khoản**
- 💾 Lưu trữ cục bộ bằng `localStorage` (không phụ thuộc backend)
- 📦 Chạy hoàn toàn offline, không cần internet

## 🚀 Cách dùng

1. Clone repo hoặc tải file `authenticator.html`
2. Mở bằng trình duyệt (Chrome, Edge, Firefox đều được)
3. Thêm tài khoản bằng cách:
   - Nhập tay `secret` (hoặc dán URI otpauth://)
   - Hoặc bấm **"Quét QR ảnh"** để nhận từ ảnh QR

## 🛡 Bảo mật

- Chạy **hoàn toàn cục bộ**  
- Mã nguồn đơn giản, dễ đọc, dễ kiểm chứng  
- Không có kết nối mạng, không lưu trữ từ xa

---

> **Tip**: Có thể dùng bản này để thay thế Google Authenticator, Authy, hoặc dùng trên máy tính làm giải pháp 2FA phụ.

---
