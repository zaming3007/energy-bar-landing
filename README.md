# EnergyBoost Landing Page

Một landing page hiện đại và đẹp mắt cho sản phẩm thanh năng lượng EnergyBoost, được xây dựng bằng HTML, CSS và JavaScript thuần.

## 🌟 Tính năng

### Thiết kế
- **Responsive Design**: Tương thích hoàn hảo trên mọi thiết bị (desktop, tablet, mobile)
- **Moderent màu xanh lá tự nhiên
- **Smooth Animations**: Hiệu ứng mượt mà khi n UI/UX**: Thiết kế hiện đại với gradiscroll và hover
- **Interactive Elements**: Các thành phần tương tác thân thiện với người dùng

### Sections
1. **Header**: Navigation bar cố định với logo và menu
2. **Hero Section**: Banner chính với call-to-action
3. **Products**: Showcase 4 sản phẩm energy bar khác nhau
4. **Benefits**: Lợi ích của sản phẩm với icon đẹp mắt
5. **Nutrition**: Thông tin dinh dưỡng với số liệu thống kê
6. **Testimonials**: Đánh giá từ khách hàng
7. **CTA**: Call-to-action cuối trang
8. **Footer**: Thông tin liên hệ và social media

### Tính năng JavaScript
- **Mobile Navigation**: Menu hamburger cho mobile
- **Smooth Scrolling**: Cuộn mượt giữa các section
- **Scroll Effects**: Header thay đổi khi scroll
- **Add to Cart**: Chức năng thêm sản phẩm vào giỏ hàng
- **Notifications**: Hệ thống thông báo đẹp mắt
- **Counter Animation**: Hiệu ứng đếm số cho thống kê dinh dưỡng
- **Intersection Observer**: Animation khi element xuất hiện
- **Image Error Handling**: Xử lý lỗi hình ảnh

## 🚀 Cách sử dụng

### 1. Mở trực tiếp
Chỉ cần mở file `index.html` trong trình duyệt web.

### 2. Sử dụng Live Server (Khuyến nghị)
```bash
# Nếu bạn có VS Code với Live Server extension
# Hoặc sử dụng Python
python -m http.server 8000

# Hoặc sử dụng Node.js
npx http-server
```

## 📁 Cấu trúc file

```
energy-bar-landing/
├── index.html          # File HTML chính
├── styles.css          # File CSS styling
├── script.js           # File JavaScript
└── README.md           # Hướng dẫn sử dụng
```

## 🎨 Màu sắc chủ đạo

- **Primary Green**: `#2d8f47` - Màu xanh lá chính của brand
- **Secondary Green**: `#4caf50` - Màu xanh lá phụ
- **Light Green**: `#81c784` - Màu xanh lá nhạt cho accent
- **Dark Green**: `#1b5e20` - Màu xanh đậm cho footer
- **Light Gray**: `#f8f9fa` - Màu nền section

## 📱 Responsive Breakpoints

- **Desktop**: > 768px
- **Tablet**: 768px - 480px  
- **Mobile**: < 480px

## 🖼️ Hình ảnh

Landing page sử dụng hình ảnh chất lượng cao từ Unsplash:
- Hình ảnh thanh năng lượng đa dạng
- Hình ảnh khách hàng cho testimonials
- Hình ảnh dinh dưỡng cho nutrition section

## ⚡ Tối ưu hóa

### Performance
- **Lazy Loading**: Tải hình ảnh khi cần thiết
- **Debounced Scroll**: Tối ưu sự kiện scroll
- **CSS Animations**: Sử dụng CSS thay vì JavaScript cho animation
- **Minified Resources**: Có thể minify CSS/JS cho production

### SEO
- **Semantic HTML**: Sử dụng các thẻ HTML có ý nghĩa
- **Meta Tags**: Đầy đủ meta tags cho SEO
- **Alt Text**: Mô tả cho tất cả hình ảnh
- **Structured Data**: Có thể thêm JSON-LD cho rich snippets

## 🛠️ Tùy chỉnh

### Thay đổi màu sắc
Chỉnh sửa các biến CSS trong file `styles.css`:
```css
:root {
    --primary-color: #2d8f47;
    --secondary-color: #4caf50;
    --accent-color: #81c784;
}
```

### Thêm sản phẩm mới
Thêm HTML trong section `.products-grid`:
```html
<div class="product-card">
    <div class="product-image">
        <img src="your-image.jpg" alt="Product Name">
    </div>
    <div class="product-info">
        <h3>Tên sản phẩm</h3>
        <p>Mô tả sản phẩm</p>
        <div class="product-price">Giá</div>
        <button class="btn btn-product">Thêm vào giỏ</button>
    </div>
</div>
```

### Thay đổi thông tin liên hệ
Chỉnh sửa trong footer section:
```html
<div class="contact-info">
    <p><i class="fas fa-phone"></i> Số điện thoại của bạn</p>
    <p><i class="fas fa-envelope"></i> Email của bạn</p>
    <p><i class="fas fa-map-marker-alt"></i> Địa chỉ của bạn</p>
</div>
```

## 🔧 Tích hợp

### Google Analytics
Thêm tracking code vào `<head>`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

### Facebook Pixel
Thêm Facebook Pixel code để tracking conversion.

### Payment Gateway
Tích hợp với các cổng thanh toán như:
- VNPay
- MoMo
- ZaloPay
- PayPal

## 📞 Hỗ trợ

Nếu bạn cần hỗ trợ hoặc có câu hỏi:
- Email: support@energyboost.vn
- Phone: 1900-1234
- Website: www.energyboost.vn

## 📄 License

Dự án này được phát hành dưới MIT License. Bạn có thể tự do sử dụng và chỉnh sửa cho mục đích thương mại.

---

**Được tạo với ❤️ cho EnergyBoost Brand** 