<div align="center">

 

  <h1>🎓 Smart English Learning App 🚀</h1>
  
  **Ứng dụng học tiếng Anh thông minh tích hợp Quiz, Flashcards và Quản lý Lộ trình Cá nhân hóa**

  <p>
    <a href="https://flutter.dev/"><img src="https://img.shields.io/badge/Flutter-3.x-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter"/></a>
    <a href="https://dart.dev/"><img src="https://img.shields.io/badge/Dart-3.x-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart"/></a>
    <a href="#"><img src="https://img.shields.io/badge/JSON-Storage-000000?style=for-the-badge&logo=json&logoColor=white" alt="JSON Storage"/></a>
    <a href="#"><img src="https://img.shields.io/badge/Role-Admin%20%7C%20User-success?style=for-the-badge" alt="Roles"/></a>
  </p>

  <p>
    <a href="#-giới-thiệu">Giới thiệu</a> •
    <a href="#-tính-năng-nổi-bật">Tính năng</a> •
    <a href="#-công-nghệ-sử-dụng">Công nghệ</a> •
    <a href="#-hướng-dẫn-cài-đặt">Cài đặt</a> •
    <a href="#-cấu-trúc-dự-án">Cấu trúc</a>
  </p>

</div>

---

## 📖 Giới thiệu

> **Smart English Learning App** là một giải pháp di động toàn diện được phát triển bằng **Flutter**, giúp người học làm chủ tiếng Anh từ cơ bản đến nâng cao. Ứng dụng kết hợp giữa kho từ vựng phong phú, phương pháp học qua **Flashcards** sinh động và hệ thống **Quiz** đánh giá năng lực theo thời gian thực. Với khả năng quản lý tài khoản và bảo mật OTP, đây là công cụ đắc lực cho cả người học tự do và quản trị viên nội dung.

---
---

## ✨ Tính năng Nổi bật

### 🧠 1. Học tập & Rèn luyện (Learning Core)
* **Smart Vocabulary:** Tra cứu và quản lý kho từ vựng Anh-Việt phong phú. Hỗ trợ thêm/sửa/xóa và đánh dấu từ vựng yêu thích.
* **Interactive Flashcards:** Ghi nhớ từ vựng qua thẻ ghi nhớ thông minh, giúp tối ưu hóa việc lưu trữ thông tin vào bộ nhớ dài hạn.
* **Multi-level Quiz System:** Hệ thống bài tập trắc nghiệm phân theo 3 cấp độ: **Nhập môn**, **Trung cấp** và **Nâng cao**. Tự động chấm điểm và lưu lịch sử làm bài.

### 🛡️ 2. Quản lý Người dùng & Bảo mật
* **Authentication:** Đăng nhập, đăng ký và quản lý hồ sơ cá nhân (`Profile`).
* **Security OTP:** Tích hợp dịch vụ Email để gửi mã xác thực OTP khi người dùng quên mật khẩu hoặc cần đặt lại (`Reset Password`).
* **Role-based Access Control (RBAC):** * **User:** Học tập, làm bài tập và xem lịch sử cá nhân.
    * **Admin:** Quản lý danh sách người dùng, chỉnh sửa nội dung Quiz và theo dõi hệ thống.

### 📊 3. Theo dõi Tiến độ (Analytics)
* **History Tracking:** Lưu trữ chi tiết các lần làm bài tập (thời gian, điểm số, kết quả chi tiết từng câu).
* **Statistics:** Biểu đồ hóa quá trình học tập giúp người dùng nhận ra những điểm cần cải thiện.

---

## 🛠️ Công nghệ Sử dụng

| Thành phần | Công nghệ / Thư viện | Vai trò |
| :--- | :--- | :--- |
| **Framework** | `Flutter 3.x` | Xây dựng giao diện đa nền tảng (Android/iOS) |
| **Language** | `Dart` | Ngôn ngữ lập trình chính |
| **State Management** | `StatefulWidget / Provider` | Quản lý trạng thái ứng dụng |
| **Local Storage** | `Shared Preferences` | Lưu trữ cấu hình người dùng và token |
| **Data Format** | `JSON Assets` | Quản lý kho từ vựng và câu hỏi Quiz |
| **Services** | `Mailer / OTP Service` | Xử lý gửi mã xác thực qua Email |
| **Charts** | `FL Chart` | Hiển thị biểu đồ thống kê kết quả học tập |

---

## 📂 Cấu trúc Dự án

Dự án tuân thủ cấu trúc mã nguồn sạch (Clean Code), dễ dàng mở rộng và bảo trì:

```text
📦 smart-english-app
 ┣ 📂 assets/data        # Chứa file JSON từ vựng và bài tập các cấp độ
 ┣ 📂 lib
 ┃ ┣ 📂 models           # Định nghĩa các lớp đối tượng (User, Vocab, QuizResult...)
 ┃ ┣ 📂 pages            # Các màn hình chức năng (Home, Quiz, Flashcard, Admin...)
 ┃ ┣ 📂 services         # Xử lý logic: Auth, Email, Storage, QuizLoader...
 ┃ ┗ 📜 main.dart        # Điểm khởi chạy và cấu hình Route ứng dụng
 ┣ 📜 pubspec.yaml       # Quản lý các thư viện (Dependencies) và Assets
 ┗ 📜 analysis_options.yaml # Cấu hình quy tắc kiểm tra code (Linting)
```

---

## 🚀 Hướng dẫn Cài đặt
Yêu cầu tiên quyết
Flutter SDK đã được cài đặt và cấu hình biến môi trường.
Một thiết bị thật hoặc trình giả lập (Emulator) Android/iOS.
Các bước thực hiện
Clone dự án:
Bash
git clone [https://github.com/your-username/smart-english-learning-application.git](https://github.com/your-username/smart-english-learning-application.git)
cd smart-english-learning-application
Cài đặt thư viện:
Bash
flutter pub get
Cấu hình Email (Tùy chọn cho tính năng OTP):
Mở file lib/services/email_service.dart và cập nhật thông tin SMTP Server để ứng dụng có thể gửi Email.
Khởi chạy:
Bash
flutter run

---


## 🗺️ Định hướng Phát triển
[x] Hệ thống Quiz đa cấp độ và Flashcards.

[x] Xác thực người dùng qua OTP Email.

[ ] Tích hợp Text-to-Speech (TTS) để luyện phát âm cho từ vựng.

[ ] Kết nối Cơ sở dữ liệu Cloud (Firebase/Supabase) để đồng bộ dữ liệu.

[ ] Bổ sung tính năng thi đấu trực tuyến (Ranked Match) giữa các người dùng.
