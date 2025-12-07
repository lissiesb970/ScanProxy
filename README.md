🌐 Tool Get Proxy (Python)

Đây là công cụ đơn giản được viết bằng Python giúp bạn tự động lấy danh sách Proxy từ **[Zorohub store](https://websz12.web.app/)** thông qua API Token và lưu lại thành file `.txt` (định dạng `IP:PORT:USER:PASS`).

## 🚀 Tính năng
- Nhập Token trực tiếp khi chạy (không sợ lộ Token trong code).
- Tự động lấy toàn bộ danh sách Proxy đang hoạt động.
- Xuất kết quả ra file `list_proxy.txt` ngay tại thư mục chạy tool.
- Hỗ trợ định dạng chuẩn để import vào các tool khác: `IP:Port:User:Pass`.

## 🛠 Yêu cầu hệ thống (Prerequisites)
Để chạy được tool này, máy tính cần cài đặt:
1. **Python 3.x** (Khuyên dùng Python 3.10 trở lên).
2. Thư viện **requests**.

## 📦 Hướng dẫn cài đặt

### Bước 1: Cài đặt thư viện
Mở Command Prompt (CMD) hoặc Terminal và chạy lệnh sau để cài thư viện hỗ trợ:

```bash
pip install requests
```

### Bước 2: Vào (Dist) chạy lệnh & khởi động get proxy

```bash
python checkproxy.py 
```
### Bước 3: Nhập Token & lấy proxy 

```bash
Khi chương trình yêu cầu, dán Token của bạn vào và nhấn Enter.
Chương trình sẽ tự động kết nối và tải danh sách proxy về.
