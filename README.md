# 📱 Ứng Dụng & Widget Theo Dõi Thói Quen + Việc Cần Làm Hôm Nay (Android)

Ứng dụng Android Native (Kotlin) siêu nhẹ, đi kèm **Home Screen Widget** luôn hiển thị trên màn hình chính điện thoại để bạn nhìn thấy ngay tiến độ mỗi khi mở máy và **bấm tích chọn hoàn thành trực tiếp ngay trên màn hình chính** mà không cần mở ứng dụng.

---

## ✨ Tính năng nổi bật

1. **Widget Luôn Hiện Trên Màn Hình Chính (Home Screen Widget)**:
   - Hiển thị ngày hôm nay và tổng quan tiến độ: `🔥 Thói quen: X/Y • 📌 Việc hôm nay: A/B`.
   - Danh sách cuộn trực tiếp ngay trên màn hình chính.
   - **Tích chọn 1 chạm ngay trên Widget**: Chạm vào bất kỳ dòng nào trên Widget để chuyển trạng thái `⬜ Chưa làm` ↔ `✅ Đã làm` ngay lập tức (kèm gạch ngang chữ khi đã hoàn thành).
2. **Phân biệt rõ 2 mục**:
   - **🔥 Thói quen cố định hằng ngày (Habits)**: Tự động làm mới trạng thái mỗi khi sang ngày mới (`00:00`), đồng thời giữ nguyên lịch sử các ngày trước.
   - **📌 Việc cần làm hôm nay (To-Do)**: Các công việc phát sinh trong ngày. Việc chưa xong sẽ được giữ lại; việc đã xong từ hôm trước sẽ tự ẩn đi khi sang ngày mới.
3. **Thống kê Chuỗi ngày liên tiếp (Streak) & Lịch sử 7 ngày**:
   - Tự động tính **Chuỗi hiện tại (`🔥 X ngày`)**, **Kỷ lục dài nhất (`🏆 Y ngày`)**, và thanh **Lịch sử 7 ngày gần nhất (`T2:✓  T3:·  ...`)**.

---

## 🚀 Cách lấy file cài đặt `.apk` tự động bằng GitHub Actions (Không cần cài phần mềm vào máy tính)

Vì dự án đã được cấu hình sẵn file tự động hóa `.github/workflows/build-apk.yml`, bạn chỉ cần đưa thư mục này lên GitHub để đám mây của GitHub tự động đóng gói file `.apk` cho bạn:

### Bước 1: Tạo kho chứa (Repository) trên GitHub
1. Truy cập [github.com/new](https://github.com/new) và đăng nhập tài khoản GitHub của bạn.
2. Đặt tên Repository (ví dụ: `habit-widget-app`), chọn **Public** (hoặc Private), tích chọn **Add a README file**, rồi bấm **Create repository**.

### Bước 2: Tải mã nguồn lên
1. Trong trang Repository vừa tạo, bấm nút **Add file** ➔ **Upload files**.
2. Mở thư mục `d:\Obsidian Vault\HabitWidgetApp` trên máy tính của bạn.
3. **Quan trọng**: Bật hiển thị thư mục ẩn trong Windows Explorer (View -> Show -> Hidden items) để thấy thư mục `.github`, sau đó **kéo thả toàn bộ các file và thư mục bên trong `HabitWidgetApp`** (gồm `.github`, `app`, `build.gradle.kts`, `settings.gradle.kts`, `gradle.properties`) vào trang web GitHub.
4. Bấm nút màu xanh **Commit changes** ở cuối trang.

### Bước 3: Tải file `.apk` về điện thoại
1. Trên trang GitHub của bạn, bấm vào tab **Actions** (ở thanh menu trên cùng).
2. Bạn sẽ thấy tiến trình **Build Android APK** đang chạy (mất khoảng 2–3 phút để hoàn tất với dấu tích xanh ✅).
3. Bấm vào tiến trình vừa chạy xong, kéo xuống mục **Artifacts** ở cuối trang và bấm tải **`HabitWidget-APK`** về.
4. Giải nén file `.zip` vừa tải sẽ có file **`app-debug.apk`** — gửi file này qua Zalo / Google Drive vào điện thoại Android và bấm cài đặt!

---

## 📌 Cách đưa Widget ra màn hình chính điện thoại

Sau khi cài đặt ứng dụng lên điện thoại:
- **Cách 1 (Nhanh nhất)**: Mở ứng dụng **Thói Quen & Việc Hôm Nay** ➔ Bấm nút màu xanh **"📌 Ghim Widget Ra Màn Hình Chính"** ngay đầu ứng dụng.
- **Cách 2 (Thủ công)**: Nhấn giữ vào khoảng trống trên màn hình chính điện thoại ➔ Chọn **Tiện ích (Widgets)** ➔ Tìm **Thói Quen & Việc Hôm Nay** và kéo thả ra màn hình chính (có thể kéo giãn kích thước tùy ý).
