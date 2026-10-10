# [Bài tập] Tạo Trang Đăng Ký Người Dùng

Dự án bài tập thực hành thiết kế giao diện **Trang Đăng Ký Người Dùng (User Registration Page)** chuyên nghiệp bằng cách kết hợp **Bootstrap Forms**, **Bootstrap Carousel** và **Bootstrap Grid System**, tối ưu hóa giao diện người dùng (UI/UX) và tuân thủ nguyên tắc hạn chế viết CSS mới, ưu tiên sử dụng các lớp có sẵn của Bootstrap 5.

---

## 🎯 Mục Tiêu Bài Tập

- Luyện tập và áp dụng thành thạo các thành phần của **Bootstrap Forms**: `form-control`, `input-group`, `form-label`, `form-text`, `btn-primary`.
- Sử dụng **Bootstrap Carousel** để hiển thị hình ảnh và nội dung quảng bá các lợi ích của dịch vụ.
- Tận dụng **Bootstrap Grid** (`row`, `col-lg-6`, `g-0`) để tạo bố cục phân chia 2 cột đối xứng hiện đại (Split Layout).
- Đảm bảo giao diện hiển thị mượt mà trên cả thiết bị di động (Mobile) lẫn máy tính (Desktop).

---

## 🏗️ Bố Cục Và Thành Phần Giao Diện

Trang web bao gồm 2 phân vùng chính trong một thẻ Card lớn bo góc (`rounded-4 shadow-lg`):

```plaintext
Trang Đăng Ký Người Dùng
│
├── Cột Trái (Col-lg-6): Bootstrap Carousel (Lợi ích dịch vụ)
│   ├── Slide 1: Bứt phá năng suất làm việc (Tự động hóa, đồng bộ tức thì)
│   ├── Slide 2: Bảo mật cấp doanh nghiệp (Mã hóa 256-bit, uptime 99.99%)
│   ├── Slide 3: Hợp tác nhóm không giới hạn (Chia sẻ tài nguyên, hỗ trợ 24/7)
│   └── Điều hướng: Carousel Indicators + Prev/Next Buttons
│
└── Cột Phải (Col-lg-6): Bootstrap Form (Form đăng ký tài khoản)
    ├── Tiêu đề & giới thiệu ngắn
    ├── 1. Họ và tên: input-group với icon Font Awesome
    ├── 2. Email: input-group với định dạng email hợp lệ
    ├── 3. Mật khẩu: input-group kèm nút ẩn/hiện mật khẩu
    ├── 4. Xác nhận mật khẩu: input-group kèm kiểm tra trùng khớp thời gian thực
    ├── Checkbox đồng ý Điều khoản dịch vụ & Chính sách bảo mật
    └── Nút Submit: btn-primary kích thước lớn (btn-lg w-100)
```

---

## 💡 Các Lớp Bootstrap Chính Được Sử Dụng

| Thành phần | Lớp Bootstrap sử dụng | Mục đích |
| :--- | :--- | :--- |
| **Grid & Bố cục** | `.container`, `.row`, `.col-12`, `.col-lg-6`, `.g-0`, `.d-flex`, `.align-items-center` | Tạo layout chia đôi màn hình responsive |
| **Card & Container** | `.card`, `.border-0`, `.shadow-lg`, `.rounded-4`, `.overflow-hidden` | Bo cong viền và tạo đổ bóng cao cấp |
| **Carousel** | `.carousel`, `.slide`, `.carousel-fade`, `.carousel-inner`, `.carousel-item`, `.carousel-indicators`, `.carousel-caption` | Slideshow tự động chuyển động với hiệu ứng fade |
| **Form Controls** | `.form-control`, `.input-group`, `.input-group-text`, `.form-label`, `.form-text`, `.form-check` | Chuẩn hóa các trường nhập liệu |
| **Buttons & Badges** | `.btn`, `.btn-primary`, `.btn-lg`, `.w-100`, `.badge`, `.rounded-pill` | Nút hành động nổi bật và huy hiệu chủ đề |

---

## 📱 Khả Năng Tương Thích & Responsive

- **Desktop (≥ 992px)**: Hiển thị 2 cột đối xứng hài hòa: bên trái là Carousel minh họa lợi ích, bên phải là form đăng ký.
- **Mobile & Tablet (< 992px)**: Các cột tự động xếp chồng (stacking) mượt mà, form co giãn tự nhiên, các nút chạm dễ dàng thao tác trên màn hình cảm ứng.

---

## 🚀 Hướng Dẫn Mở Dự Án

1. **Xem trực tiếp**: Nhấp đúp vào tệp [index.html](file:///d:/BaiTapGithub/index.html).
2. **Xem qua Live Server**: Chuột phải vào `index.html` trong IDE và chọn **Open with Live Server** (`http://127.0.0.1:5500/index.html`).

---

## 👨‍💻 Thông Tin Học Viên

- **Học viên**: dtc245200059
- **Email**: dtc245200059@ictu.edu.vn
- **Bài tập**: Tạo Trang Đăng Ký Người Dùng với Bootstrap Forms & Carousel
