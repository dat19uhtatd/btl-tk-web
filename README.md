# DỰ ÁN: QUẢN LÝ LỊCH HỌC

**Bài tập lớn — Môn: Thiết kế Web**  
Ngôn ngữ: HTML, CSS, JavaScript  
Giao diện hiển thị: Tiếng Việt

---

## 📌 Giới thiệu
Dự án **Quản lý Lịch học** là một ứng dụng web đơn giản giúp người dùng (sinh viên hoặc giáo viên) dễ dàng:
- Quản lý **thời khóa biểu**
- Thêm và theo dõi **bài tập**
- Quản lý **thông báo cá nhân**
- Xem **thống kê trực quan** bằng biểu đồ
- Lưu trữ dữ liệu cục bộ trên trình duyệt qua `localStorage`

Giao diện hiện đại, thân thiện, sử dụng **Chart.js** để hiển thị biểu đồ.

---

## ✨ Tính năng chính
- **Quản lý Lịch học**
  - Thêm / hiển thị / xóa buổi học theo ngày & khung giờ.
  - Lưu trữ tự động bằng `localStorage`.
- **Quản lý Bài tập**
  - Thêm bài tập theo môn và hạn nộp.
  - Đánh dấu đã hoàn thành / chưa hoàn thành.
- **Quản lý Thông báo**
  - Tạo thông báo có ngày nhắc.
  - Hiển thị danh sách thông báo sắp tới.
- **Thống kê**
  - Tổng số lịch học, bài tập hoàn thành/không hoàn thành.
  - Biểu đồ dạng cột & tròn (Chart.js).
- **Cài đặt**
  - Lưu tên & vai trò.
  - Bật/tắt thông báo desktop.
  - Xóa toàn bộ dữ liệu cục bộ.

---

## Công nghệ sử dụng

| Thành phần | Công nghệ |
|-------------|------------|
| Giao diện | HTML5, CSS3 (Flexbox, Grid, Gradient UI) |
| Hiệu ứng & Logic | JavaScript (thuần) |
| Lưu trữ | LocalStorage |
| Biểu đồ | [Chart.js](https://www.chartjs.org/) |
| Icon | [Font Awesome](https://fontawesome.com/) |


---


## 🚀 Cách chạy project (local)
1. Clone repo:
```bash
git clone https://github.com/dat19uhtatd/btl-tk-web.git
cd btl-tk-web
Mở file trangchu.html trực tiếp trên trình duyệt hoặc chạy server đơn giản:

bash
Sao chép mã
# Dùng Python (port 8080)
python -m http.server 8080
# -> truy cập: http://localhost:8080/trangchu.html
⚙️ Quy trình làm việc với mã nguồn (Git workflow)
Tuân thủ quy trình này để tránh xung đột và giúp team dễ quản lý:

1. Pull trước khi bắt đầu
bash
Sao chép mã
git pull origin main
2. Tạo branch mới (mỗi task / feature một branch)
bash
Sao chép mã
# tạo branch và chuyển sang branch đó
git checkout -b feature/my-feature-name
3. Làm việc, commit, push lên remote branch
bash
Sao chép mã
git add .
git commit -m "Mô tả rõ thay đổi, ví dụ: add: login form validation"
git push origin feature/my-feature-name
4. Tạo Pull Request (PR)
Tạo PR trên GitHub từ feature/my-feature-name → main.

Ghi mô tả PR rõ ràng: mục tiêu, thay đổi chính, cách test.

Tuyệt đối không push trực tiếp lên main.

✅ Lưu ý về code style & quy ước
Comment rõ ràng, ngắn gọn, giúp người đọc nắm nhanh logic.

Code phải có trình tự, dễ đọc, tách module rõ ràng.

Đặt tên class theo chuẩn BEM: block__element--modifier.

Ví dụ:

card, card__title, card__title--highlight

Ưu tiên tiếng Anh cho tên class / biến; tránh trộn lẫn tiếng Việt & tiếng Anh.

Tách CSS theo module: mỗi page / component 1 file CSS trong /css.

Dùng assets/css/base.css để đặt reset, biến CSS (colors, spacing, font-size) và các quy tắc chung.

🔧 Ví dụ nhanh — BEM & comment
HTML:

html
Sao chép mã
<!-- block: timetable -->
<div class="timetable">
  <div class="timetable__row">
    <div class="timetable__cell timetable__cell--highlight">07:00 - 08:30</div>
  </div>
</div>
JS comment mẫu:

js
Sao chép mã
// addClass: thêm lịch học mới vào scheduleData và lưu vào localStorage
function addClass(event) {
  // validate form
  // cập nhật scheduleData
  // saveData()
  // render lại UI
}
👨‍💻 Thông tin thực hiện
Họ và tên: Phan Tiến Đạt

Lớp: CNTT3-K65

Môn học: Thiết kế Web

Trường: Đại Học GTVT

