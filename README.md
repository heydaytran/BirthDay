# HBD Surprise (QR + Canvas Video-like Effect)
## Cách dùng nhanh
1) Thay ảnh trong **assets/friend.jpg** bằng ảnh của bạn ấy (đặt cùng tên file).
2) Mở **index.html** để xem thử hiệu ứng: chạm/bấm để bắt đầu, confetti, ảnh hiện dần bằng hạt.
3) Deploy lên GitHub Pages/Netlify/Vercel để có URL công khai.
4) Mở `qr/qr.html` → nhập URL vừa deploy → tạo mã QR → lưu hình QR và gửi cho bạn ấy.

### Tuỳ biến nhanh
- Đổi tên & lời chúc ngay trong `index.html`:
  ```js
  const FRIEND_NAME = "Trần Văn Thịnh";
  const MESSAGE = "Chúc bạn luôn khoẻ mạnh...";
  ```

### Gợi ý host (GitHub Pages)
- Tạo repo mới, upload toàn bộ thư mục này (giữ nguyên cấu trúc).
- Vào Settings → Pages → chọn Branch: `main` (hoặc `master`) → `/root` → Save.
- Đợi vài phút, bạn sẽ có URL dạng: `https://<username>.github.io/<repo>/`.

> Lưu ý: Mã QR nên trỏ tới **URL online**, không trỏ file cục bộ.

Chúc bạn có một món quà độc đáo ✨
