
[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/H8V-fdC0)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=24142667&assignment_repo_type=AssignmentRepo)
Bài tập lớn Lập trình trên thiết bị di động

# 💰 BudgetBuddy - Ứng Dụng Quản Lý Chi Tiêu Thông Minh

## 📌 Giới Thiệu
BudgetBuddy là một ứng dụng quản lý tài chính cá nhân dành cho nền tảng Android. Ứng dụng giúp người dùng dễ dàng ghi chép các khoản thu/chi, phân loại theo danh mục, theo dõi biểu đồ thống kê trực quan và cập nhật tin tức tài chính theo thời gian thực.

## 🚀 Công Nghệ Sử Dụng
- **Ngôn ngữ:** Kotlin
- **Giao diện:** Jetpack Compose (Material Design 3)
- **Kiến trúc:** MVVM (Model - View - ViewModel) + Repository Pattern
- **Cơ sở dữ liệu Local:** Room Database (SQLite)
- **Lưu trữ cài đặt:** Jetpack DataStore Preferences
- **Gọi mạng (API):** Retrofit & Gson
- **Xử lý bất đồng bộ:** Kotlin Coroutines & Flow
- **Tải ảnh:** Coil

## ⭐ Tính Năng Chính
1. **Quản lý Thu/Chi:** Thêm, sửa, xóa giao dịch tài chính.
2. **Quản lý Danh Mục:** Tùy biến phân loại dòng tiền, cảnh báo giới hạn ngân sách.
3. **Thống Kê:** Tự động tính toán số dư khả dụng, tổng thu chi, hiển thị biểu đồ phần trăm (Pie Chart).
4. **Tin Tức Tài Chính:** Lấy tin tức thị trường tự động từ Internet thông qua NewsAPI.
5. **Cơ chế an toàn:** Tự động dọn dẹp "giao dịch mồ côi" khi xóa danh mục, sao lưu dữ liệu (Backup/Restore) định dạng JSON.
6. **Cá nhân hóa:** Hỗ trợ chế độ Sáng/Tối (Dark Mode).

## 🛠️ Hướng Dẫn Cài Đặt (Dành cho Developer)
1. Clone dự án về máy tính qua Git hoặc tải mã nguồn (ZIP).
2. Mở dự án bằng **Android Studio** (Bản mới nhất có hỗ trợ Jetpack Compose).
3. Đợi Gradle đồng bộ (Sync) và cài đặt các thư viện cần thiết.
4. Bấm **Run (Shift + F10)** để chạy trên máy ảo hoặc thiết bị thật.

## 📱 Build file APK
File cài đặt APK nằm tại đường dẫn: `app-debug.apk`

---
*Dự án thực hiện bởi Nhóm 5*
>>>>>>> 633567f (Em nộp bài hoàn thiện của nhóm số 5 CT1B)
