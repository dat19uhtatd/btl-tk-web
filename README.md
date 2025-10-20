# 🌟 DỰ ÁN: QUẢN LÝ LỊCH HỌC

> **Bài tập lớn môn Thiết kế Web**  
> Ngôn ngữ: HTML, CSS, JavaScript  
> Giao diện hiển thị bằng tiếng Việt

---

##  Giới thiệu

Dự án **Quản lý Lịch học** là một ứng dụng web đơn giản giúp người dùng (sinh viên hoặc giáo viên) dễ dàng:
- Quản lý **thời khóa biểu**
- Thêm và theo dõi **bài tập**
- Quản lý **thông báo cá nhân**
- Xem **thống kê trực quan** bằng biểu đồ
- Lưu trữ dữ liệu **cục bộ** trên trình duyệt thông qua `localStorage`

Ứng dụng được thiết kế hiện đại, giao diện thân thiện, sử dụng **Chart.js** để hiển thị thống kê.

---


##  Tính năng nổi bật

###  Quản lý Lịch học
- Thêm, hiển thị và xóa các buổi học theo ngày & khung giờ.
- Lưu trữ tự động bằng **Local Storage**.
- Giao diện bảng thời khóa biểu trực quan.

###  Quản lý Bài tập
- Thêm bài tập theo môn học, thời hạn nộp.
- Đánh dấu bài tập đã hoàn thành hoặc cần làm.
- Phân loại tự động và hiển thị rõ ràng.

###  Quản lý Thông báo
- Tạo thông báo mới có ngày nhắc cụ thể.
- Hiển thị danh sách thông báo sắp tới.

###  Thống kê
- Thống kê tổng số lịch học, bài tập đã hoàn thành / chưa hoàn thành.
- Biểu đồ hiển thị bằng **Chart.js** (dạng cột và tròn).

###  Cài đặt
- Lưu thông tin cá nhân (tên, vai trò).
- Bật/tắt thông báo desktop.
- Xóa toàn bộ dữ liệu cục bộ chỉ bằng 1 cú nhấp.

---

##  Công nghệ sử dụng

| Thành phần | Công nghệ |
|-------------|------------|
| Giao diện | HTML5, CSS3 (Flexbox, Grid, Gradient UI) |
| Hiệu ứng & Logic | JavaScript (thuần) |
| Lưu trữ | LocalStorage |
| Biểu đồ | [Chart.js](https://www.chartjs.org/) |
| Icon | [Font Awesome](https://fontawesome.com/) |

---

##  Cách chạy dự án

### 🔹 Cách 1: Mở trực tiếp
1. Giải nén project.
2. Mở file `trangchu.html` trong trình duyệt.
3. Tất cả dữ liệu sẽ tự lưu vào trình duyệt của bạn.

### 🔹 Cách 2: Chạy qua server cục bộ
Nếu cần chạy trên server (để mô phỏng tốt hơn):
```bash
# Dùng Python
python -m http.server 8080

# Hoặc dùng VSCode Live Server
Truy cập: http://localhost:8080/trangchu.html

👨‍💻 Thành viên thực hiện
Họ và tên: Phan Tiến Đạt

Lớp: (Điền lớp của bạn)

Môn học: Thiết kế Web

Trường: (Tên trường của bạn)

📸 Giao diện mẫu
🔹 Trang đăng nhập
Giao diện hiện đại, hiệu ứng gradient động, có chức năng hiển thị/ẩn mật khẩu.

🔹 Trang chủ (Dashboard)
Quản lý lịch học, bài tập, thông báo và thống kê trong một giao diện thống nhất.

🧾 Ghi chú phát triển
Dự án được thiết kế với hướng Single Page Application (SPA) cơ bản.

Toàn bộ dữ liệu được lưu trực tiếp trong trình duyệt (không cần backend).

Có thể mở rộng bằng cách kết nối với cơ sở dữ liệu hoặc API thật trong tương lai.

📚 Giấy phép
Dự án dùng cho mục đích học tập và nghiên cứu – không sử dụng cho mục đích thương mại.

✨ “Thiết kế đẹp – Trải nghiệm tốt – Mã nguồn rõ ràng”
💡 Made with ❤️ by Tiến Đạt

css
Sao chép mã

---

Bạn có muốn mình **thêm phần hướng dẫn cài đặt và chạy thử bằng GitHub Pages** (để bạn nộp bài hoặc demo online) vào cuối README không?






