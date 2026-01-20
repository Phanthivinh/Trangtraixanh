# Bộ Tư Liệu Website "Trang Trại Nông Nghiệp Sạch"

## Thông Điệp Chính
- Trang trại nông nghiệp sạch, nuôi trồng tự nhiên
- Vật nuôi và cây trồng sử dụng thức ăn từ ngô, thóc
- Không hóa chất, không độc hại, không thức ăn công nghiệp
- Cảm giác: **an tâm – bền vững – đáng tin – gần gũi thiên nhiên**

## Bảng Màu Nhận Diện
| Màu | Mã Hex | Sử dụng |
|-----|--------|---------|
| Xanh lá chủ đạo | `#588157` | Màu nền, nút CTA, tiêu đề |
| Xanh đậm | `#3A5A40` | Điểm nhấn, footer, header |

---

## Cấu Trúc Thư Mục

```
farm_website_assets/
├── hero/
│   └── hero-banner.jpg       ← Ảnh banner trang chủ
├── sections/
│   ├── ao-ca.jpg             ← Khu vực ao cá
│   ├── vuon-rau.jpg          ← Khu vực vườn rau
│   ├── vuon-hoa.jpg          ← Khu vực vườn hoa
│   └── hoa-hong.jpg          ← Chi tiết hoa hồng
├── products/
│   ├── rau-sach.jpg          ← Ảnh sản phẩm rau
│   └── ca-ao.jpg             ← Ảnh sản phẩm cá
└── video/
    ├── 7449766853466.mp4     ← Video 1 (19MB)
    ├── 7449767086852.mp4     ← Video 2 (24MB)
    ├── 7449767239156.mp4     ← Video 3 (15MB)
    └── 7449807999892.mp4     ← Video 4 (9MB) - ĐỀ XUẤT cho web
```

---

## Chi Tiết Từng Ảnh

### 1. Hero Banner (`hero/hero-banner.jpg`)
- **Nội dung**: Vườn hoa cánh bướm rộng, hướng xa với lối đi
- **Kích thước**: 731 KB
- **Sử dụng**: Làm ảnh nền chính trang chủ
- **Lưu ý**: 
  - Crop theo tỷ lệ 16:9
  - Thêm overlay gradient để đặt tiêu đề
  - Điều chỉnh tông màu xanh theo `#588157`

### 2. Ảnh Section (Khu Vực Trang Trại)

| File | Nội dung | Kích thước | Text đề xuất |
|------|----------|------------|--------------|
| `ao-ca.jpg` | Ao cá với người chăm sóc | 217 KB | "Ao cá sạch – Nuôi tự nhiên" |
| `vuon-rau.jpg` | Nhiều luống rau xanh tươi | 455 KB | "Vườn rau sạch – Không hóa chất" |
| `vuon-hoa.jpg` | Vườn hoa cánh bướm rộng | 752 KB | "Không gian xanh – Gần gũi thiên nhiên" |
| `hoa-hong.jpg` | Hoa hồng nhạt trong vườn | 242 KB | Trang trí hoặc section phụ |

### 3. Ảnh Sản Phẩm

| File | Nhãn chữ đề xuất |
|------|------------------|
| `rau-sach.jpg` | "Rau sạch – Không độc hại" |
| `ca-ao.jpg` | "Cá ao sạch – Nuôi tự nhiên" |

### 4. Video Nền Trang Chủ

**Đề xuất sử dụng**: `7449807999892.mp4` (9MB) – Kích thước nhỏ nhất, tải nhanh

**Yêu cầu xử lý**:
- Cắt thành 6-8 giây
- Chuyển cảnh chậm, mượt
- Không chèn chữ, không hiệu ứng phức tạp
- Nén thêm nếu cần để tối ưu tải trang

---

## Lưu Ý Quan Trọng

> ⚠️ **THIẾU ẢNH VẬT NUÔI**
> 
> Thư mục hiện tại KHÔNG có:
> - Ảnh gà thả vườn
> - Ảnh ngỗng thả vườn
> - Ảnh trứng sản phẩm
> 
> Cần bổ sung nếu muốn đầy đủ nội dung theo yêu cầu ban đầu.

---

## Hướng Dẫn Sử Dụng Trên Website

### Hero Section
```html
<section class="hero" style="background-image: url('hero/hero-banner.jpg')">
  <div class="overlay">
    <h1>Trang Trại Nông Nghiệp Sạch</h1>
    <p>An tâm – Bền vững – Gần gũi thiên nhiên</p>
  </div>
</section>
```

### CSS Màu Nhận Diện
```css
:root {
  --primary-green: #588157;
  --dark-green: #3A5A40;
}
```

---

*Tạo ngày: 20/01/2026*
