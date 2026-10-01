# 🚗 UCR 2026 - Hệ Thống AI Bám Làn Tự Hành

<div align="center">

### 🧠 Computer Vision • 🤖 AI Detection • 🎯 PID Control • ⚡ Real-Time Processing

*"Biến camera thành đôi mắt, biến thuật toán thành tay lái."*

</div>

---

## 📖 Giới Thiệu

Đây là dự án nghiên cứu và phát triển hệ thống **xe tự hành bám làn đường bằng Trí Tuệ Nhân Tạo (AI)** được xây dựng cho cuộc thi **UIT Car Racing - UCR 2026**.

Mục tiêu của dự án là giúp xe:

* Nhận diện làn đường bằng AI.
* Tự động điều khiển góc lái.
* Tối ưu tốc độ khi vào cua.
* Hoạt động ổn định trong thời gian thực.
* Chạy được trên phần cứng phổ thông.

Toàn bộ hệ thống được phát triển bằng **Python, OpenCV, YOLO và PID Controller**.

---

# ✨ Tính Năng

## 🔍 Nhận Diện Làn Đường Bằng AI

* Huấn luyện mô hình YOLO riêng.
* Phát hiện làn đường theo thời gian thực.
* Hoạt động trong nhiều điều kiện ánh sáng khác nhau.
* Tối ưu cho CPU.

---

## 🎯 Điều Khiển Xe Tự Động

* PID Controller giúp xe bám giữa làn.
* Tự động điều chỉnh góc lái.
* Giảm tốc khi vào cua.
* Tăng tốc trên đoạn đường thẳng.

---

## 📊 Công Cụ Debug

* Hiển thị ảnh camera.
* Hiển thị vùng lane được nhận diện.
* Theo dõi lỗi PID.
* Theo dõi tốc độ và góc lái theo thời gian thực.

---

## ⚡ Tối Ưu Hiệu Năng

* Chạy ổn định trên máy không có GPU.
* Giảm tải cho CPU.
* Tách FPS Camera và FPS YOLO.
* Đảm bảo phản hồi nhanh cho xe.

---

# 🛠️ Công Nghệ Sử Dụng

| Thành phần        | Công nghệ      |
| ----------------- | -------------- |
| Ngôn ngữ          | Python         |
| Thị giác máy tính | OpenCV         |
| AI Detection      | YOLO           |
| Xử lý số liệu     | NumPy          |
| Điều khiển        | PID Controller |
| Giao tiếp xe      | UCR Library    |

---

# 🚀 Quy Trình Huấn Luyện

```text
Thu Thập Dữ Liệu
        │
        ▼
 Gắn Nhãn (Label)
        │
        ▼
 Chuẩn Hóa Dataset
        │
        ▼
 Huấn Luyện YOLO
        │
        ▼
 Đánh Giá Mô Hình
        │
        ▼
      best.pt
        │
        ▼
 Điều Khiển Xe
```

---

# 🧠 Nguyên Lý Hoạt Động

```text
Camera
   │
   ▼
YOLO Detect Lane
   │
   ▼
Tính Tâm Làn Đường
   │
   ▼
Tính Sai Số
   │
   ▼
PID Controller
   │
   ▼
Tính Góc Lái
   │
   ▼
Điều Khiển Xe
```

---

# 📂 Cấu Trúc Dự Án

```text
.
├── dataset/
│   ├── images/
│   └── labels/
│
├── runs/
│
├── best.pt
├── train.py
├── main.py
└── README.md
```

---

# 🎯 Mục Tiêu Dự Án

Dự án hướng đến việc xây dựng một hệ thống xe tự hành có khả năng:

✅ Bám làn chính xác

✅ Vào cua ổn định

✅ Hoạt động thời gian thực

✅ Tự động điều chỉnh tốc độ

✅ Sẵn sàng cho các cuộc thi xe tự hành

---

# 🔥 Định Hướng Tương Lai

* [ ] Nhận diện nhiều loại làn đường
* [ ] Tránh vật cản bằng AI
* [ ] Nhận diện biển báo giao thông
* [ ] Kết hợp Camera và LiDAR
* [ ] Tối ưu cho Jetson Nano
* [ ] Xe tự hành hoàn chỉnh

---

# 👨‍💻 Tác Giả

**Nguyễn Đoàn Thanh Phong**

🎓 Sinh viên ngành Kỹ thuật Máy tính

💻 Đam mê:

* Trí Tuệ Nhân Tạo (AI)
* Computer Vision
* Robotics
* Hệ Thống Nhúng
* Xe Tự Hành

---

# ⭐ Ủng Hộ Dự Án

Nếu bạn thấy dự án hữu ích:

🌟 Star Repository

🍴 Fork Repository

🚀 Theo dõi các phiên bản tiếp theo

---

<div align="center">

## "Không chỉ dạy máy nhìn thấy làn đường, mà còn dạy nó cách tự đưa ra quyết định."

🚗💨 UCR 2026

</div>
