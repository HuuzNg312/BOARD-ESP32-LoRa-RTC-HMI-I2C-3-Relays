# BOARD-ESP32-LoRa-RTC-HMI-I2C-3-Relays

> **🎉 Chia sẻ cá nhân: Đây là mạch hoàn chỉnh đầu tiên tôi tự hàn! (My very first self-soldered PCB)**

**From LAB to LIFE** - AIoT Semiconductor

Dự án phát triển Module KIT ESP32 đa năng, tích hợp kết nối không dây tầm xa (LoRa), điều khiển thiết bị ngoại vi mạnh mẽ và giao tiếp đa chuẩn. Sản phẩm được thiết kế và phát triển bởi team AIoT Semiconductor thuộc trường Đại học Sư phạm Kỹ thuật TP.HCM (HCMUTE).

## 🚀 Tính năng nổi bật (Key Features)

Dựa trên thiết kế phần cứng và danh sách linh kiện, module sở hữu các thông số ấn tượng:

### 1. Kết nối & Truyền thông
* **Vi xử lý trung tâm:** ESP32 (Hỗ trợ WiFi & Bluetooth).
* **Mạng không dây LoRa:** Kết nối tầm xa trong khoảng cách **1 - 1.5km**.
* **Giao tiếp HMI:** Cổng kết nối chuyên dụng cho màn hình HMI.
* **Giao thức mở rộng:**
    * Cổng I2C hỗ trợ cả hai mức điện áp **3.3V và 5V**.
    * Cổng UART kết nối cảm biến.

### 2. Điều khiển & Ngoại vi
* **Relay Output:** Tích hợp **3 kênh Relays** (Omron G5NB-1A-E 5VDC) cho phép điều khiển tắt/mở thiết bị tải dòng cao.
* **Real-Time Clock (RTC):** Sử dụng IC **DS3231N** độ chính xác cao, kèm pin backup CR1220 đảm bảo thời gian thực hoạt động liên tục.
* **Lưu trữ:** Tích hợp khe cắm thẻ nhớ **MicroSD** phục vụ datalogging.
* **Cách ly tín hiệu:** Sử dụng Optoisolator **EL357N-G** để bảo vệ mạch điều khiển.

### 3. Nguồn điện (Power)
* **Dải điện áp đầu vào rộng:** 6V - 24V DC.
* **Mạch giảm áp hiệu suất cao:** Sử dụng IC **TPS5430DDAR** cho dòng ra lên tới **3A**, đảm bảo nguồn ổn định cho toàn hệ thống và các module mở rộng.

---

## 👨‍💻 Thông tin tác giả (Authors)

Sản phẩm được thiết kế và kiểm tra bởi đội ngũ kỹ sư từ **AIoT Semiconductor Lab**:

* **Thiết kế (Designed by):** Nguyễn Văn Thái, Hoàng Long & AI.
* **Kiểm tra (Checked by):** Nguyễn Trung Thảo, L.T.Quốc Uy.
* **Giảng viên hướng dẫn:** GVC.TS. Nguyễn Văn Thái.
    * **Đơn vị:** Bộ môn Điều khiển tự động, Khoa Điện-Điện tử, HCMUTE.
    * **Liên hệ:** nguyenvanthai@hcmute.edu.vn | 0902 80 7576.

---

## 🤝 Lời cảm ơn (Acknowledgments)

Tô xin gửi lời cảm ơn chân thành đến:
* **AIoT Semiconductor Lab**: Đã cung cấp cơ sở vật chất và môi trường nghiên cứu tuyệt vời.
* **Trường ĐH Sư phạm Kỹ thuật TP.HCM (HCMUTE)**: Đã tạo điều kiện hỗ trợ phát triển các sản phẩm công nghệ ứng dụng thực tiễn "From LAB to LIFE".

---
*Release Date: 18/01/2025*
