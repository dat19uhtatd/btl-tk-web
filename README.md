#  DỰ ÁN: QUẢN LÝ LỊCH HỌC

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
Quy trình làm việc với mã nguồn
🔹 1. Clone dự án

Dùng lệnh sau để tải mã nguồn về:

git clone https://github.com/dat19uhtatd/btl-tk-web.git

🔹 2. Tạo branch mới trước khi làm việc

Luôn pull lại dự án trước khi bắt đầu:

git pull


Sau đó tạo một branch mới để làm việc (không sửa trực tiếp trên main):

git checkout -b ten-branch-cua-ban

🔹 3. Đẩy mã nguồn lên repository

Sau khi hoàn thành, thực hiện:

git add .
git commit -m "Mô tả thay đổi"
git push origin main


Tạo Pull Request (PR) trên GitHub để merge vào main.

 Tuyệt đối không push trực tiếp lên nhánh main.
 
 Lưu ý về code và style
 
 Comment rõ ràng, dễ hiểu, hỗ trợ người đọc nắm nhanh logic.
 
 Code gọn gàng, có trình tự, tách riêng từng phần rõ ràng.
 
 Đặt tên class theo chuẩn BEM (block__element--modifier), đảm bảo ý nghĩa và thống nhất.
 
 Có thể đặt tên tiếng Việt hoặc tiếng Anh (ưu tiên tiếng Anh), tránh trộn lẫn hoặc từ đồng nghĩa.
 
 Giữ nguyên cấu trúc thư mục như hiện tại để đảm bảo đồng nhất.
 
 Mỗi phần giao diện (page) nên có file CSS riêng trong thư mục /css.

👨‍💻 Thành viên thực hiện

Họ và tên: Phan Tiến Đạt

Lớp: CNTT3-K65

Môn học: Thiết kế Web

Trường: Đại Học GTVT


