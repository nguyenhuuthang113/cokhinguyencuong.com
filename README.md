# 🏭 Website Cơ Khí Xây Dựng Nguyễn Cường

<div align="center">

![Logo Nguyễn Cường](assets/images/logo/logo3D_rmbg.png)

**Website chuyên nghiệp cho Công ty TNHH Cơ Khí Xây Dựng Nguyễn Cường**

_Chuyên sản xuất khuôn gạch và gia công cơ khí chính xác_

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

</div>

---

## 📋 Mục lục

- [Giới thiệu](#-giới-thiệu)
- [Tính năng nổi bật](#-tính-năng-nổi-bật)
- [Công nghệ sử dụng](#-công-nghệ-sử-dụng)
- [Cấu trúc dự án](#-cấu-trúc-dự-án)
- [Cài đặt](#-cài-đặt)
- [Các trang](#-các-trang)
- [Tùy chỉnh](#-tùy-chỉnh)
- [SEO](#-seo)
- [Responsive Design](#-responsive-design)
- [Dark Mode](#-dark-mode)
- [Thông tin liên hệ](#-thông-tin-liên-hệ)
- [License](#-license)

---

## 🎯 Giới thiệu

Website chuyên nghiệp cho **Công ty TNHH Cơ Khí Xây Dựng Nguyễn Cường** - đơn vị hàng đầu trong lĩnh vực:

- 🔩 Sản xuất khuôn gạch các loại
- ⚙️ Gia công cơ khí chính xác
- 🏗️ Thiết bị xây dựng chuyên dụng
- 🛠️ Gia công CNC, tiện, phay

Website được thiết kế hiện đại, tối ưu SEO và trải nghiệm người dùng, với đầy đủ các tính năng cần thiết cho một doanh nghiệp cơ khí chuyên nghiệp.

---

## ✨ Tính năng nổi bật

### 🎨 Giao diện

- ✅ Thiết kế hiện đại, chuyên nghiệp
- ✅ Dark/Light mode với đồng bộ localStorage
- ✅ Responsive 100% trên mọi thiết bị
- ✅ Animation mượt mà với Intersection Observer
- ✅ Material Symbols Icons

### 🚀 Hiệu năng

- ✅ Tối ưu tốc độ tải trang
- ✅ Lazy loading cho hình ảnh
- ✅ CSS được tối ưu với Tailwind CSS
- ✅ JavaScript vanilla - không dependencies nặng

### 📱 Trải nghiệm người dùng

- ✅ Navigation menu responsive
- ✅ Mobile-first design
- ✅ Smooth scroll animations
- ✅ Interactive hover effects
- ✅ Form liên hệ đầy đủ

### 🔍 SEO & Marketing

- ✅ Meta tags đầy đủ (Open Graph, Twitter Cards)
- ✅ Schema.org structured data
- ✅ Canonical URLs
- ✅ Semantic HTML
- ✅ Alt text cho tất cả hình ảnh

---

## 🛠️ Công nghệ sử dụng

| Công nghệ            | Phiên bản | Mục đích                    |
| -------------------- | --------- | --------------------------- |
| **HTML5**            | Latest    | Cấu trúc trang web          |
| **Tailwind CSS**     | 3.x       | Framework CSS utility-first |
| **JavaScript**       | ES6+      | Tương tác và logic          |
| **Material Symbols** | Latest    | Icon library                |
| **Google Fonts**     | -         | Typography (Inter)          |

### Tailwind CSS Configuration

```javascript
tailwind.config = {
  darkMode: "class",
  theme: {
    extend: {
      colors: {
        primary: "#1152d4",
        "accent-orange": "#f97316",
        "background-light": "#f6f6f8",
        "background-dark": "#101622",
      },
      fontFamily: {
        display: ["Inter", "sans-serif"],
      },
    },
  },
};
```

---

## 📁 Cấu trúc dự án

```
cokhinguyencuongcom/
│
├── index.html              # Trang chủ
├── contact.html            # Trang liên hệ
├── terms.html              # Điều khoản sử dụng
├── privacy.html            # Chính sách bảo mật
├── khach-hang.html         # Danh sách khách hàng
├── 404.html                # Trang lỗi 404
├── README.md               # File này
│
└── assets/
    └── images/
        ├── khuon/          # Hình ảnh sản phẩm khuôn gạch
        ├── logo/           # Logo công ty
        │   └── logo3D_rmbg.png
        └── products/       # Hình ảnh sản phẩm khác
```

---

## 💻 Cài đặt

### Yêu cầu

- Web browser hiện đại (Chrome, Firefox, Safari, Edge)
- Web server (Apache, Nginx, hoặc Live Server cho development)

### Hướng dẫn

1. **Clone hoặc download dự án**

   ```bash
   git clone [repository-url]
   cd cokhinguyencuongcom
   ```

2. **Chạy với Live Server (VS Code)**
   - Cài extension "Live Server"
   - Right-click vào `index.html`
   - Chọn "Open with Live Server"

3. **Hoặc chạy với Python**

   ```bash
   # Python 3
   python -m http.server 8000

   # Truy cập: http://localhost:8000
   ```

4. **Deploy lên hosting**
   - Upload toàn bộ files lên thư mục public_html
   - Đảm bảo `index.html` ở root directory
   - Cấu hình SSL certificate (khuyến nghị)

---

## 📄 Các trang

### 🏠 Trang chủ (`index.html`)

- Hero section với CTA
- Giới thiệu công ty
- Danh sách sản phẩm khuôn gạch
- Dịch vụ cơ khí
- Quy trình làm việc
- Footer premium

### 📞 Liên hệ (`contact.html`)

- Form liên hệ đầy đủ
- Thông tin công ty
- Bản đồ địa chỉ (placeholder)
- Social media links

### 👥 Khách hàng (`khach-hang.html`)

- Danh sách 14+ khách hàng/đối tác
- Statistics section
- Customer testimonials
- Responsive table với badges

### 📜 Điều khoản (`terms.html`)

- 9 sections đầy đủ
- Điều khoản sử dụng dịch vụ
- Chính sách bảo hành
- Giải quyết tranh chấp

### 🔒 Bảo mật (`privacy.html`)

- Chính sách bảo mật thông tin
- GDPR compliant
- Quyền của người dùng
- Cookie policy

### ⚠️ Lỗi 404 (`404.html`)

- Trang lỗi chuyên nghiệp
- Animation mượt mà
- Quick links hữu ích
- Dark mode support

---

## 🎨 Tùy chỉnh

### Thay đổi màu sắc

Chỉnh sửa trong phần `<script id="tailwind-config">`:

```javascript
colors: {
  primary: "#1152d4",           // Màu chủ đạo
  "accent-orange": "#f97316",   // Màu nhấn
  "background-light": "#f6f6f8", // Nền sáng
  "background-dark": "#101622",  // Nền tối
}
```

### Thay đổi thông tin công ty

Tìm và thay thế:

- `035.921.6666` → Số điện thoại mới
- `Cokhi442@gmail.com` → Email mới
- `36/2/25 Nguyễn An Ninh...` → Địa chỉ mới

### Thêm sản phẩm mới

Trong `index.html`, tìm mảng `products`:

```javascript
const products = [
  {
    title: "Tên sản phẩm",
    image: "assets/images/khuon/product-image.jpg",
    category: "Danh mục",
    description: "Mô tả sản phẩm",
  },
  // Thêm sản phẩm mới tại đây
];
```

---

## 🔍 SEO

### Meta Tags được tối ưu

Mỗi trang đều có:

- ✅ Title tag độc nhất
- ✅ Meta description hấp dẫn
- ✅ Keywords phù hợp
- ✅ Open Graph tags
- ✅ Twitter Card tags
- ✅ Canonical URL

### Schema.org Structured Data

```html
<script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Organization",
    "name": "Công ty TNHH Cơ Khí Xây Dựng Nguyễn Cường",
    "url": "https://www.cokhinguyencuong.com",
    "logo": "https://www.cokhinguyencuong.com/assets/images/logo/logo3D_rmbg.png"
  }
</script>
```

### Sitemap & Robots.txt

Tạo file `sitemap.xml`:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url>
    <loc>https://www.cokhinguyencuong.com/</loc>
    <priority>1.0</priority>
  </url>
  <url>
    <loc>https://www.cokhinguyencuong.com/contact.html</loc>
    <priority>0.8</priority>
  </url>
  <!-- Thêm các trang khác -->
</urlset>
```

---

## 📱 Responsive Design

Website tối ưu cho tất cả các thiết bị:

| Breakpoint | Width          | Target Device     |
| ---------- | -------------- | ----------------- |
| Mobile     | < 640px        | Smartphones       |
| Tablet     | 640px - 1024px | Tablets           |
| Desktop    | > 1024px       | Laptops, Desktops |

### Testing Checklist

- ✅ iPhone SE (375px)
- ✅ iPhone 12 Pro (390px)
- ✅ iPad (768px)
- ✅ iPad Pro (1024px)
- ✅ Desktop (1280px+)

---

## 🌙 Dark Mode

### Tính năng

- Toggle button ở header
- Đồng bộ qua localStorage
- Persist khi chuyển trang
- Smooth transition

### Implementation

```javascript
// Load theme on page load
(function () {
  const theme = localStorage.getItem("theme");
  if (theme === "dark") {
    document.documentElement.classList.add("dark");
  } else {
    document.documentElement.classList.add("light");
  }
})();

// Toggle và lưu preference
darkModeToggle.addEventListener("click", function () {
  const html = document.documentElement;
  if (html.classList.contains("dark")) {
    html.classList.remove("dark");
    html.classList.add("light");
    localStorage.setItem("theme", "light");
  } else {
    html.classList.remove("light");
    html.classList.add("dark");
    localStorage.setItem("theme", "dark");
  }
});
```

---

## 📞 Thông tin liên hệ

### Công ty TNHH Cơ Khí Xây Dựng Nguyễn Cường

📍 **Địa chỉ:**  
36/2/25 Nguyễn An Ninh, Khu phố Nhị Đồng 2,  
Phường Dĩ An, Thành phố Dĩ An, Bình Dương

📱 **Hotline:** [035.921.6666](tel:+84359216666)

📧 **Email:** [Cokhi442@gmail.com](mailto:Cokhi442@gmail.com)

⏰ **Giờ làm việc:** Thứ 2 - Thứ 7: 07:30 - 17:30

---

## 🔧 Support & Maintenance

### Báo lỗi

Nếu phát hiện lỗi, vui lòng:

1. Mô tả chi tiết lỗi
2. Screenshot (nếu có)
3. Thiết bị và browser đang dùng
4. Liên hệ qua email hoặc hotline

### Update Log

- **v1.0.0** (01/2026) - Ra mắt website
  - ✅ 5 trang chính
  - ✅ Dark mode
  - ✅ Responsive design
  - ✅ SEO optimization

---

## 📜 License

Copyright © 2024 **Công ty TNHH Cơ Khí Xây Dựng Nguyễn Cường**

All rights reserved.

---

<div align="center">

**Made with ❤️ for Nguyễn Cường**

_Uy tín - Chất lượng - Bền vững_

[🏠 Trang chủ](index.html) • [📞 Liên hệ](contact.html) • [👥 Khách hàng](khach-hang.html)

</div>
