# WebFlex

Một trang web cá nhân theo phong cách 3D sci-fi, mô phỏng một hành lang triển lãm kỹ thuật số để giới thiệu bản thân, kỹ năng, dự án và thông tin liên hệ.

## Mô tả dự án

WebFlex là một landing page tĩnh được xây dựng bằng HTML, CSS và JavaScript, tích hợp:
- Tailwind CSS cho giao diện
- Three.js để tạo hiệu ứng không gian 3D
- Hiệu ứng tương tác, modal, âm thanh, và menu điều hướng
- Thiết kế theo phong cách cyberpunk / glassmorphism

Dự án này chủ yếu là một portfolio cá nhân được trình bày dưới dạng "hành lang triển lãm 3D" thay vì layout website truyền thống.

## Tính năng chính

- Giao diện 3D tương tác theo phong cách sci-fi
- Hệ thống di chuyển và khám phá trong không gian 3D
- Các panel/section mô tả thông tin cá nhân, kỹ năng, dự án, kinh nghiệm
- Modal hiển thị chi tiết khi tương tác
- Tích hợp âm thanh nền và hiệu ứng hộp nhạc
- Giao diện responsive cho cả desktop và mobile
- Không cần framework hay build tools

## Công nghệ sử dụng

- HTML5
- CSS3
- JavaScript
- Tailwind CSS
- Three.js
- Font Awesome
- Google Fonts

## Cấu trúc thư mục

```bash
webflex/
├── index.html          # Trang chính
├── main.html           # File dự án tương tự / sở hữu giao diện chính
├── music/
│   └── music_chill.mp3
├── README.md           # Tài liệu dự án
└── assets /           # Nếu sau này bạn thêm hình ảnh, stylesheet, JS riêng
```

## Cài đặt và chạy

Vì đây là dự án frontend tĩnh, bạn không cần cài đặt package manager hay dependency phức tạp.

### 1. Clone repository

```bash
git clone https://github.com/annguyen332005-tech/webflex.git
cd webflex
```

### 2. Mở trực tiếp trong trình duyệt

Bạn có thể mở file `index.html` hoặc `main.html` trực tiếp trong trình duyệt.

### 3. Hoặc chạy local server (khuyến nghị)

```bash
python -m http.server 8000
```

Sau đó truy cập:

```bash
http://localhost:8000
```

## Hướng dẫn sử dụng

- Di chuyển bằng phím `W`, `A`, `S`, `D` hoặc mũi tên
- Xoay góc nhìn bằng chuột
- Nhấn `Space` hoặc click để tương tác với nội dung
- Dùng menu chuyển nhanh ở góc dưới màn hình để di chuyển đến các section
- Một số khu vực đặc biệt như "hộp nhạc" có hiệu ứng âm thanh và hoạt cảnh riêng

## Ghi chú

- Dự án hiện tại là một front-end tĩnh, không có backend hoặc database
- Tất cả tài nguyên đồ họa/âm thanh đang được load từ CDN hoặc thư mục `music/`
- Nếu bạn muốn mở rộng dự án, có thể thêm:
  - section portfolio thực tế
  - form liên hệ
  - carousel dự án
  - tích hợp CMS hoặc dữ liệu JSON

## License

Dự án này hiện chưa có thông tin license cụ thể. Nếu bạn muốn công khai mã nguồn trên GitHub, hãy thêm file `LICENSE` phù hợp như MIT hoặc Apache 2.0.

## Tác giả

Tên dự án mang tính cá nhân hóa, mô tả một portfolio / personal landing page 3D của cá nhân.

Nếu bạn muốn, tôi có thể tiếp tục giúp bạn:
- tạo file `LICENSE`
- tối ưu README cho GitHub theo phong cách chuyên nghiệp hơn
- viết nội dung mô tả dự án theo tên thật của bạn
- thêm phần "Features", "Tech Stack", "Demo" cho README chuẩn công ty
