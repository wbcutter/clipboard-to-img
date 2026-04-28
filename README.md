# 📸 Clipboard to IMG - Dán Ảnh, Xuất JPG Trong Tích Tắc

Công cụ web đơn giản nhất để **dán ảnh từ clipboard bằng 1 nút bấm** và xuất ra file **JPG** ngay lập tức. Tự động chuyển nền trong suốt của PNG thành nền trắng, không cần mở Photoshop hay Photopea.

🌐 **Live Demo:** [https://wbcutter.github.io/clipboard-to-img/](https://wbcutter.github.io/clipboard-to-img/)

## ✨ Tính năng chính

*   **📋 Dán ảnh 1 nút bấm:** Bấm nút "Dán từ Clipboard & Xem trước" → cho phép quyền (lần đầu) → ảnh hiện ra ngay. Hỗ trợ cả điện thoại và máy tính.
*   **🖼️ Xử lý PNG trong suốt:** Tự động đổ nền **trắng** khi xuất JPG (tránh bị nền đen khó chịu).
*   **💾 Xuất JPG chất lượng:** Có thanh trượt tuỳ chỉnh chất lượng từ 60% → 100%, cân bằng giữa dung lượng và độ nét.
*   **🔒 Hỏi quyền 1 lần duy nhất:** Sau khi bạn cho phép, các lần dán sau không cần xin phép lại.
*   **📐 Giữ nguyên kích thước:** Xuất ảnh đúng kích thước gốc, không bị resize mờ.
*   **🎨 Giao diện tối giản:** Dark mode, responsive, hiển thị rõ ràng kích thước ảnh sau khi dán.
*   **📱 Hoạt động trên điện thoại:** Bấm nút → chọn ảnh từ thư viện / chụp mới hoặc dán → xử lý ngay.

## 🎯 Dùng để làm gì?

| Nhu cầu | Cách dùng |
|---------|-----------|
| Chụp màn hình → xuất JPG | Chụp màn hình (PrtSc) → mở web → bấm "Dán từ Clipboard" → xuất JPG |
| Lấy ảnh từ web/Zalo/Telegram | Copy ảnh → mở web → bấm nút dán → xuất |
| Chuyển PNG trong suốt sang JPG | Copy file PNG → bấm nút dán → web tự fill nền trắng → xuất |
| Làm việc trên điện thoại | Chụp ảnh hoặc copy ảnh → bấm nút → chọn từ clipboard → xuất |

## 🕹️ Cách sử dụng

### 📱 Trên điện thoại (iPhone / Android)
1. Mở web bằng Chrome / Safari
2. **Copy ảnh** (chụp màn hình hoặc sao chép ảnh từ web)
3. Bấm nút **"📋 Dán từ Clipboard & Xem trước"**
4. Lần đầu trình duyệt hỏi quyền → bấm **"Cho phép"**
5. Ảnh hiện ra → bấm **"⬇️ Xuất JPG (Tải file ngay)"**
6. Chọn nơi lưu ảnh

> ⚠️ Lưu ý iOS: Sau khi bấm "Cho phép", có thể cần bấm thêm nút "Dán" trong popup.

### 🖥️ Trên máy tính (Windows / Mac)
1. Mở web bằng Chrome / Edge / Firefox
2. **Copy ảnh** (`Ctrl+C` hoặc chuột phải → Sao chép hình ảnh)
3. Bấm nút **"📋 Dán từ Clipboard & Xem trước"**
4. Lần đầu trình duyệt hỏi quyền → bấm **"Cho phép"**
5. Ảnh hiện ra → bấm **"Xuất JPG"** → file tự động tải về

## 📦 Cài đặt & chạy local

Vì đây là một trang HTML thuần túy, bạn có thể chạy trực tiếp mà không cần server.

```bash
git clone https://github.com/wbcutter/clipboard-to-img.git
cd clipboard-to-img
# Mở file index.html bằng trình duyệt (double-click)
