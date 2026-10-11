# 🎧 AirPods Max — Trải nghiệm sắc màu

<p align="center">
  <strong>Một landing page giới thiệu Apple AirPods Max với hiệu ứng trình chiếu màu sắc sống động.</strong>
</p>

<p align="center">
  <img alt="HTML" src="https://img.shields.io/badge/HTML5-landing%20page-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img alt="CSS" src="https://img.shields.io/badge/CSS3-responsive%20design-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-animated%20slider-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
</p>

> **Âm thanh đỉnh cao. Sắc màu cá tính.**  
> Trang giới thiệu sản phẩm tối giản, hiện đại, nơi hình ảnh tai nghe và phông nền chuyển màu nhịp nhàng để tạo nên trải nghiệm thị giác nổi bật.

---

## 📑 Mục lục

- [Giới thiệu](#-giới-thiệu)
- [Nội dung trên website](#-nội-dung-trên-website)
- [Tính năng nổi bật](#-tính-năng-nổi-bật)
- [Công nghệ sử dụng](#-công-nghệ-sử-dụng)
- [Cấu trúc dự án](#-cấu-trúc-dự-án)
- [Cách chạy dự án](#-cách-chạy-dự-án)
- [Tùy chỉnh nội dung](#-tùy-chỉnh-nội-dung)
- [Tác giả](#-tác-giả)

## ✨ Giới thiệu

Đây là trang landing page giới thiệu **Apple AirPods Max Wireless Over-Ear Headphones**. Điểm nhấn của giao diện là bộ ảnh sản phẩm năm màu kết hợp với nền chuyển sắc tương ứng. Slide tự động thay đổi, làm nổi bật từng màu tai nghe bằng hiệu ứng mờ và chuyển động.

Giao diện được xây dựng bằng HTML, CSS và JavaScript thuần; không cần framework hay bước biên dịch.

## 🛍️ Nội dung trên website

| Hạng mục | Nội dung |
| --- | --- |
| Sản phẩm | Apple AirPods Max Wireless Over-Ear Headphones |
| Mô tả | Active Noise Cancelling, Transparency Mode, Spatial Audio, Digital Crown for Volume Control; Bluetooth Headphones for iPhone |
| Giá hiển thị | **$699.99** |
| Các phiên bản màu | Xanh lá, xanh dương, đỏ, trắng và đen |
| Liên kết mạng xã hội | Instagram, Facebook và Twitter |

## 🚀 Tính năng nổi bật

- **Trình chiếu tự động:** ảnh sản phẩm và màu nền lần lượt chuyển sau mỗi 3 giây.
- **Hiệu ứng chuyển cảnh:** ảnh hiện tại được làm rõ; ảnh kế tiếp, ảnh trước đó và các ảnh còn lại có trạng thái hiển thị riêng.
- **Phối màu đồng bộ:** mỗi phiên bản tai nghe đi kèm một nền chuyển sắc phù hợp.
- **Thiết kế responsive:** bố cục và kích thước nội dung thích ứng với màn hình máy tính bảng và điện thoại.
- **Giao diện tập trung vào sản phẩm:** tên, mô tả, giá và biểu tượng mạng xã hội được đặt cạnh hình ảnh tai nghe.
- **Không cần cài đặt thư viện:** chỉ dùng HTML, CSS và JavaScript thuần.

## 🧰 Công nghệ sử dụng

- **HTML5** — cấu trúc nội dung trang.
- **CSS3** — bố cục, responsive, màu nền chuyển sắc và hiệu ứng chuyển cảnh.
- **JavaScript (Vanilla)** — điều khiển trạng thái và thời gian chuyển slide.
- **Google Fonts — Montserrat** — kiểu chữ của giao diện.

## 📁 Cấu trúc dự án

```text
.
├── index.html          # Nội dung và cấu trúc landing page
├── style.css           # Giao diện, hiệu ứng và breakpoint responsive
├── script.js           # Logic trình chiếu ảnh và nền
└── Images/
    ├── logo.svg
    ├── green.png
    ├── blue.png
    ├── red.png
    ├── white.png
    ├── black.png
    ├── instagram.svg
    ├── facebook.svg
    └── twitter.svg
```

## ▶️ Cách chạy dự án

### Mở trực tiếp

Mở `index.html` bằng trình duyệt. Vì trang sử dụng tài nguyên trong thư mục `Images`, hãy giữ nguyên cấu trúc thư mục của dự án.

### Chạy bằng VS Code Live Server

1. Mở thư mục dự án trong VS Code.
2. Cài tiện ích **Live Server** nếu máy chưa có.
3. Nhấp chuột phải vào `index.html`, chọn **Open with Live Server**.

## 🎨 Tùy chỉnh nội dung

- **Tên sản phẩm, mô tả, giá:** sửa nội dung trong `index.html`.
- **Ảnh sản phẩm:** thay các ảnh tương ứng trong `Images/`; giữ tên tệp hiện tại hoặc cập nhật đường dẫn trong `index.html`.
- **Màu nền:** chỉnh các giá trị `radial-gradient` trong phần `#backgrounds` của `index.html`.
- **Thời gian chuyển slide:** thay `3000` trong `setInterval(updateSlider, 3000)` ở `script.js` (đơn vị: mili giây).
- **Kiểu chữ, kích thước và breakpoint:** chỉnh trong `style.css`.
- **Liên kết mạng xã hội:** thay `href="#"` trong `index.html` bằng đường dẫn trang tương ứng.

## 👤 Tác giả

**Lê Phú An**

---

<p align="center">
  <strong>AirPods Max — chọn sắc màu của bạn, tận hưởng không gian âm thanh của riêng mình.</strong>
</p>
