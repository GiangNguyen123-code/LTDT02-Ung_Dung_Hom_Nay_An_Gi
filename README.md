# 🍜 Hôm Nay Ăn Gì? (What To Eat Today)

> **Ứng dụng di động hỗ trợ lựa chọn món ăn hằng ngày trên nền tảng Android**  
> *Chấm dứt nỗi ám ảnh "Hôm nay ăn gì?" chỉ với một cú chạm hoặc một cú lắc điện thoại!*

---

## 📌 Thông tin đề tài

* **Lớp học phần:** 126LTTD02
* **Giảng viên hướng dẫn:** ThS. Đỗ Phú Huy
* **Nhóm thực hiện:** Nhóm 07

### 👥 Thành viên nhóm

| STT | Họ và tên | Mã sinh viên | Vai trò |
| :---: | :--- | :---: | :---: |
| 1 | **Nguyễn Đỗ Hữu Giang** | `2415053122312` | **Nhóm trưởng** |
| 2 | **Thái Trường Giang** | `2415053122313` | Thành viên |
| 3 | **Lê Doãn Đàn** | `2415053122305` | Thành viên |

---

## 📖 Giới thiệu tổng quan

Câu hỏi **"Hôm nay ăn gì?"** là vấn đề nan giải diễn ra hằng ngày, gây mất nhiều thời gian và dễ dẫn đến tình trạng "tê liệt vì có quá nhiều lựa chọn" (choice paralysis). 

Ứng dụng **"Hôm Nay Ăn Gì"** ra đời như một **trợ lý ẩm thực cá nhân**, lấy cảm hứng từ cơ chế **"mở hòm vật phẩm" (loot box)** trong trò chơi điện tử, mang lại trải nghiệm chọn món bất ngờ, thú vị và đầy hào hứng.

---

## ✨ Tính năng nổi bật

### 🎯 Tính năng cốt lõi (Core Features)
* 🎁 **Mở hòm ẩm thực:** Cơ chế mở thưởng ngẫu nhiên nhận món ăn kèm hình ảnh minh họa và giá cả tham khảo.
* 🎡 **Vòng quay may mắn:** Lắc nhẹ thiết bị để khởi động vòng quay chọn món siêu tiện lợi.
* 🔍 **Bộ lọc thông minh:** Lọc danh sách món linh hoạt theo ngân sách chi tiêu hoặc theo chế độ ăn chay/mặn.
* 🗺️ **Bản đồ quán ăn:** Tích hợp **Google Maps** định vị và tìm kiếm các quán ăn xung quanh vị trí hiện tại.

### 📝 Quản lý thực đơn cá nhân
* ➕ **Tùy biến món ăn:** Tự do thêm món mới, điều chỉnh giá, bật/tắt từng món tùy sở thích mỗi ngày.
* 💾 **Lưu trữ Offline:** Dữ liệu được lưu trữ trực tiếp trên thiết bị, sử dụng mượt mà không phụ thuộc Internet.

### 🚀 Tính năng mở rộng
* ☀️ **Gợi ý theo thời tiết:** Đề xuất món ăn phù hợp với nhiệt độ và thời tiết thực tế.
* 🚫 **Danh sách đen (Blacklist):** Loại trừ tức thì các món không muốn ăn trong lượt quay.
* ⭐ **Món yêu thích:** Đánh dấu món ưu tiên để tăng tỷ lệ xuất hiện trong các lượt quay tiếp theo.
* 📊 **Thống kê ẩm thực:** Biểu đồ trực quan theo dõi thói quen ăn uống theo tuần/tháng.
* 📤 **Chia sẻ nhanh:** Gửi kết quả món ăn đã chọn cho bạn bè hoặc nhóm cùng chốt món.

---

## 🎨 Trải nghiệm người dùng (UX/UI)

* 🌙 **Dark Theme:** Giao diện nền tối hiện đại, giúp hình ảnh món ăn nổi bật và thân thiện với mắt.
* 🃏 **Card View & Lottie Animation:** Hiệu ứng chuyển động mượt mà, trực quan chuẩn Material Design 3.
* 📳 **Haptic Feedback:** Rung phản hồi sống động khi lắc máy hoặc mở hòm chọn món.

---

## 🛠️ Công nghệ sử dụng

| Thành phần | Công nghệ / Thư viện áp dụng |
| :--- | :--- |
| **Hệ điều hành** | Android |
| **Ngôn ngữ** | Kotlin |
| **Kiến trúc** | MVVM (Model - View - ViewModel) + LiveData / Flow |
| **Cơ sở dữ liệu** | Room Database (SQLite) |
| **Giao diện** | Material Design 3, Lottie Animation |
| **Bản đồ & Vị trí** | Google Maps SDK, Fused Location Provider |

---

## 🚀 Hướng dẫn cài đặt & Khởi chạy dự án

1. **Clone repository:**
   ```bash
   git clone [https://github.com/GiangNguyen123-code/LTDT02-Ung_Dung_Hom_Nay_An_Gi.git](https://github.com/GiangNguyen123-code/LTDT02-Ung_Dung_Hom_Nay_An_Gi.git)
