# 🚗 Đua Xe – Brick Game

Game đua xe pixel art cổ điển lấy cảm hứng từ Brick Game huyền thoại, chạy hoàn toàn trên trình duyệt — không cần cài đặt, không cần internet.

---

## 🎮 Cách chơi

- Lái xe của bạn (màu **trắng**) tránh các xe ngược chiều (màu xanh đậm)
- Mỗi xe vượt qua được = **+10 điểm**
- Tốc độ tăng dần theo thời gian — càng trụ lâu càng khó
- Va chạm vào xe địch → **Game Over**

---

## 🕹️ Điều khiển

| Thiết bị | Hành động |
|---|---|
| 📱 Điện thoại | Nút **◀ ▶** trên màn hình |
| ⌨️ Bàn phím | `←` `→` hoặc `A` `D` |
| ⏸️ Tạm dừng | Nút **PAUSE** hoặc phím `P` / `Escape` |
| ▶️ Bắt đầu | Nút **BẮT ĐẦU** hoặc phím `Enter` |

---

## ⚡ Tính năng

- **Toàn màn hình** — tự động co giãn theo mọi kích thước màn hình
- **Tốc độ tăng liên tục** theo thời gian thực, không phải theo bậc
- **Đường rộng 2 làn** với dải phân cách — luôn có khoảng trống để lách
- **Xe địch thưa** — spawn xen kẽ trái/phải để đảm bảo lách được
- **Phân biệt xe** — xe người chơi màu trắng, xe địch màu xanh đậm
- **Lưu điểm cao** trong phiên chơi
- **Hiệu ứng LCD** — nền xanh lá, scanline, pixel art chuẩn Brick Game
- **Giữ nút** trên mobile để di chuyển liên tục

---

## 🚀 Chạy game

Chỉ cần mở file `brick-race.html` bằng bất kỳ trình duyệt nào:

```
# Mở trực tiếp
Nhấp đúp vào file brick-race.html

# Hoặc kéo thả vào cửa sổ trình duyệt
```

Không cần server, không cần kết nối mạng.

---

## 🛠️ Công nghệ

- **HTML5 Canvas** — render pixel grid
- **Vanilla JavaScript** — game loop, collision detection, input handling
- **CSS3** — layout toàn màn hình, responsive, hiệu ứng nút bấm
- **Google Fonts** — Press Start 2P (font pixel art)

---

## 📁 Cấu trúc file

```
brick-race.html   ← Toàn bộ game trong 1 file duy nhất
README.md         ← File này
```

---

*Được tạo bởi Oops Hano — chạy tốt trên Chrome, Safari, Firefox, Edge.*
