# 🌾 GODEW VALLEY - HƯỚNG DẪN CHƠI

## 📖 MỤC ĐÍCH TRÒ CHƠI
Quản lý trang trại của bạn: trồng cây, chăm sóc đất, câu cá, chiến đấu với quái thú, xây dựng máy tự động và tương tác với các nhân vật.

---

## 🎮 ĐIỀU KHIỂN CƠ BẢN

### Di Chuyển
| Phím | Chức năng |
|------|---------|
| **W** | Đi lên |
| **A** | Đi trái |
| **S** | Đi xuống |
| **D** | Đi phải |
| **Space** | Hành động / Dùng công cụ / Tương tác |

### Menu
| Phím | Chức năng |
|------|---------|
| **ESC** | Đóng menu |

---

## 🛠️ HỆ THỐNG CÔNG CỤ

### Chuyển Công Cụ
| Phím | Chức năng |
|------|---------|
| **E** | Công cụ tiếp theo → |
| **Q** | Công cụ trước đó ← |

**Thứ tự công cụ:** `Axe → Hoe → Sword → Water → Fish → Seed`

### Chọn Hạt Giống
| Phím | Chức năng |
|------|---------|
| **C** | Hạt tiếp theo |

**Loại hạt:** `Tomato → Corn → Pumpkin → Wheat`

---

## ⚒️ CÔNG CỤ CHÍNH

### 1. **HOE (Cuốc)** - Chuẩn Bị Đất
- **Dùng cho:** Chuyển đất cỏ thành đất chuẩn bị
- **Cách dùng:** Chọn công cụ Hoe, đứng trên đất cỏ, nhấn Space
- **Lợi ích:** Đất chuẩn bị có thể được trồng hạt
- **Tưới nước:** Mưa tự động tưới nước các đất chuẩn bị

### 2. **SEED (Hạt Giống)** - Trồng Cây
- **Loại hạt:**
  - 🍅 **Tomato** - Tốc độ trồng: Trung bình (0.6), Tối đa bị chết: 3 lần
  - 🌽 **Corn** - Tốc độ trồng: Nhanh (1.0), Tối đa bị chết: 2 lần
  - 🎃 **Pumpkin** - Tốc độ trồng: Chậm (0.3), Tối đa bị chết: 3 lần
  - 🌾 **Wheat** - Tốc độ trồng: Nhanh (1.0), Tối đa bị chết: 3 lần

- **Cách dùng:** 
  1. Chọn công cụ Seed
  2. Chọn loại hạt bằng C
  3. Đứng trên đất chuẩn bị trống
  4. Nhấn Space để trồng

- **Xem tiến độ:** Nhấn N để hiện thông tin cây (N key)

### 3. **WATER (Tưới Nước)** - Tưới Nước Thủ Công
- **Cách dùng:** Chọn công cụ Water, nhấn Space trên đất hoặc cây
- **Tác dụng:** Tăng tốc độ tăng trưởng cây
- **Ghi chú:** Nếu mưa ngày hôm sau, cây sẽ được tưới tự động

### 4. **AXE (Rìu)** - Chặt Cây & Tấn Công
- **Chặt cây:**
  - Cây có 3 máu chứi
  - Mỗi lần chặt: 2-4 gỗ + táo
  - Cây sẽ mọc lại táo vào ngày tiếp theo

- **Tấn công quái:**
  - Dùng để đánh quái Slime Blob
  - Gây sát thương và đẩy lùi quái

### 5. **SWORD (Kiếm)** - Vũ Khí Chiến Đấu
- **Cách dùng:** Chọn công cụ Sword, nhấn Space để tấn công
- **Tác dụng:** Tấn công quái Slime Blob
- **Phạm vi:** 20 pixel xung quanh nhân vật

### 6. **FISH (Câu Cá)** - Câu Cá
- **Điều kiện:** Chỉ hoạt động tại các ô nước (bờ biển)
- **Cách dùng:** Chọn công cụ Fish, nhấn Space tại ô nước
- **Kết quả:** Câu được 2-4 cá mỗi lần
- **Lợi ích:** Tích lũy cá phục vụ xây dựng máy

---

## 🏗️ CHẾ ĐỘ XÂY DỰNG (BUILD MODE)

### Kích Hoạt/Tắt
| Phím | Chức năng |
|------|---------|
| **M** | Bật/tắt Build Mode |

### Trong Build Mode
| Phím | Chức năng |
|------|---------|
| **E** | Máy tiếp theo → |
| **Q** | Máy trước đó ← |
| **Space** | Đặt máy tại vị trí hiện tại |

---

## ⚙️ MÁY TỰ ĐỘNG (MACHINES)

### 1. **SPRINKLER (Vòi Tưới)** - Tưới Tự Động
- **Chi phí:** 30 Cà chua + 20 Lúa mì
- **Tác dụng:** Tưới nước tự động 8 ô đất xung quanh
- **Phạm vi:** 3x3 cell (tâm là vị trí đặt)
- **Hoạt động:** Hàng ngày

### 2. **FISHER (Người Câu Cá)** - Câu Cá Tự Động
- **Chi phí:** 25 Gỗ + 15 Cá
- **Tác dụng:** Sản xuất 2-4 cá hàng ngày
- **Điều kiện:** Phải đặt tại bờ biển/ô nước
- **Lợi ích:** Tiết kiệm thời gian câu cá thủ công

### 3. **SCARECROW (Bù Nhìn)** - Bắn Quái Tự Động
- **Chi phí:** 15 Bí ngô + 15 Ngô
- **Tác dụng:** Tự động bắn vào quái Slime Blob gần đó
- **Vũ khí:** Phát bắn từ kiếm (projectiles)
- **Lợi ích:** Bảo vệ cây khỏi quái ăn cây

### 4. **DELETE (Xóa)** - Gỡ Máy
- **Chi phí:** Miễn phí
- **Cách dùng:** Chọn DELETE trong build mode, nhấn Space trên máy cần xóa
- **Tác dụng:** Gỡ bỏ máy đã đặt

---

## 🏠 TƯƠNG TÁC VỚI VẬT THỂ

### Giường Ngủ (Bed)
| Phím | Chức năng |
|------|---------|
| **Space** | Ngủ trên giường |

**Tác dụng:**
- ⏭️ Tiến tới ngày tiếp theo
- 💤 Đặt lại chu kỳ tăng trưởng cây
- 🔄 Kích hoạt lại máy tự động
- 👹 Quái Slime Blob xuất hiện

### TV Set (Bộ Truyền Hình)
| Phím | Chức năng |
|------|---------|
| **Space** | Xem dự báo thời tiết |

**Tác dụng:**
- ☀️ Xem trời sẽ nắng hay mưa ngày mai
- 🌧️ Kế hoạch tưới nước cho hợp lý

---

## 👥 TƯƠNG TÁC VỚI NHÂN VẬT

### Gọi Tương Tác
| Phím | Chức năng |
|------|---------|
| **Space** | Tương tác với NPC gần đó |

### Cửa Hàng Mũ (HAT SHOP)
- **Chức năng:** Thay đổi kiểu nhân vật
- **NPC:** Một số nhân vật bán mũ
- **Ghi chú:** Phục vụ tùy chỉnh nhân vật

### Cửa Hàng Chính (MAIN SHOP)
- **Chức năng:** Mua máy xây dựng
- **NPC:** Người bán chính
- **Chi phí:** Sử dụng trồng trọt, câu cá, chặt cây

---

## 🎨 KHÁC

### Thay Kiểu Nhân Vật
| Phím | Chức năng |
|------|---------|
| **T** | Đổi kiểu nhân vật |

### Xem Thông Tin Cây
| Phím | Chức năng |
|------|---------|
| **N** | Bật/tắt thông tin cây (Plant Diagnostics) |

**Thông tin hiển thị:**
- 📊 Trạng thái sức khỏe cây
- 📈 Giai đoạn tăng trưởng
- 💧 Tình trạng tưới nước

### Tiến Ngày Nhanh
| Phím | Chức năng |
|------|---------|
| **Tab** | Ngủ (vào giường) |

---

## 🔄 VÒNG LẶP CHƠI HÀNG NGÀY

1. **Sáng:** Di chuyển quanh trang trại
2. **Cuốc & Trồng:** Chuẩn bị đất, trồng hạt
3. **Tưới Nước:** Tưới cây (nếu không có mưa)
4. **Câu Cá/Chặt Cây:** Thu thập tài nguyên
5. **Chiến Đấu:** Đánh quái Slime Blob
6. **Xây Dựng:** Đặt máy tự động
7. **Tương Tác:** Nói chuyện với NPC, cả mua bán
8. **Đi Ngủ:** Nhấn Tab hoặc Space trên giường để tiến sang ngày tiếp theo

---

## 📊 THỐNG KÊ CÂY

### Tốc Độ Tăng Trưởng
| Cây | Tốc độ | Ghi chú |
|-----|--------|--------|
| 🌽 Corn | 1.0 (Nhanh) | Quá nhanh, ít chịu được chết |
| 🌾 Wheat | 1.0 (Nhanh) | Quá nhanh |
| 🍅 Tomato | 0.6 (Trung bình) | Cân bằng |
| 🎃 Pumpkin | 0.3 (Chậm) | Tăng trưởng lâu, xứng đáng chi phí |

### Sức Chịu Đựng
| Cây | Tối đa bị chết | Lợi ích |
|-----|---|---|
| Corn | 2 lần | Nhanh nhưng dễ bị gây hại |
| Wheat | 3 lần | Bản đồ đó cầu |
| Tomato | 3 lần | Ổn định |
| Pumpkin | 3 lần | Cân bằng |

---

## ⚠️ NGUY HIỂM

### Quái Slime Blob
- **Xuất hiện:** Hàng ngày sau khi ngủ
- **Hành động:** Di chuyển và ăn cây
- **Cách đối phó:**
  - ⚔️ Dùng Sword hoặc Axe để tấn công
  - 🏗️ Đặt Scarecrow để tự động bắn
  - 🌾 Vệ sinh - xóa cây nếu cần thiết

---

## 💡 CHIẾN LƯỢC CHƠI

### Để Bắt Đầu
1. Cuốc 3-4 ô đất
2. Trồng hạt ngô (nhanh nhất)
3. Tưới nước hàng ngày
4. Thu hoạch khi chín

### Để Có Tài Nguyên Nhanh
1. **Gỗ:** Chặt cây liên tục (3 HP/cây)
2. **Cá:** Câu cá ở bờ biển
3. **Cây trồng:** Trồng ngoài ra

### Để Xây Dựng Máy
1. Thu thập: 30 Cà chua + 20 Lúa mì (Sprinkler)
2. Bật Build Mode (M)
3. Chọn máy (E/Q)
4. Đặt (Space)

### Để Chiến Thắng
1. Thu thập đủ tài nguyên
2. Xây đủ máy tự động
3. Quản lý cây tốt (tránh chết > tối đa)
4. Bảo vệ cây khỏi quái

---

## ❓ THẮC MẮC THƯỜNG GẶP

**Q: Cây chết sao?**
A: Quái Slime ăn cây hoặc cây không được tưới nước quá lâu.

**Q: Làm sao vệ sinh cây?**
A: Dùng Sword/Axe tấn công quái, hoặc đặt Scarecrow.

**Q: Nước ở đâu?**
A: Tưới bằng công cụ Water hoặc chờ mưa.

**Q: Tài nguyên không đủ?**
A: Trồng thêm, câu thêm, chặt thêm cây.

**Q: Máy hoạt động sao?**
A: Máy tự động hoạt động hàng ngày sau khi ngủ.

---

## 🎯 MỤC TIÊU CUỐI CÙNG
Xây dựng một trang trại phát triển với:
- ✅ Máy tự động hoạt động
- ✅ Cây trồng bền bỉ
- ✅ Không bị quái tấn công
- ✅ Thu thập tài nguyên liên tục

---

**Chúc bạn chơi vui! 🌾🎮**
