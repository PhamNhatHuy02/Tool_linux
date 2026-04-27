# Auto-Linux Hardening Tool

Một công cụ Bash Script mạnh mẽ được thiết kế để tự động hóa quá trình cấu hình, bảo mật và tối ưu hóa các server chạy Ubuntu. Công cụ này giúp tiết kiệm thời gian và đảm bảo các tiêu chuẩn bảo mật cơ bản cho bất kỳ hệ thống Linux mới nào.

## Các tính năng chính (Key Features)

* **Tự động cập nhật hệ thống:** Thực hiện `apt update` và `apt upgrade` để đảm bảo hệ thống luôn ở trạng thái mới nhất.
* **Thiết lập Firewall:** Tự động cài đặt và cấu hình `UFW` (Uncomplicated Firewall) với chính sách chặn kết nối đến không cần thiết.
* **Chống tấn công Brute-force:** Cài đặt sẵn `Fail2Ban` để bảo vệ server khỏi các nỗ lực đăng nhập trái phép.
* **Quản lý người dùng:** Tự động tạo user quản trị mới với quyền `sudo`, thay thế việc sử dụng tài khoản `root` trực tiếp.
* **Bảo mật SSH:** Vô hiệu hóa khả năng đăng nhập trực tiếp bằng tài khoản `root` qua SSH để tăng cường tính bảo mật.
* **Cài đặt công cụ giám sát:** Cài đặt sẵn các tiện ích cần thiết (`htop`, `net-tools`, `vim`, `git`, `curl`).

## Hướng dẫn sử dụng (Usage)

1. **Clone dự án hoặc tải file:**
   ```bash
   git clone <link-repository-cua-ban>
   cd auto-linux-setup
