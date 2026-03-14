 # 🌍 Smart Tourism AI

**Smart Tourism AI** là hệ thống hỗ trợ du lịch thông minh giúp người dùng khám phá địa điểm, lập kế hoạch chuyến đi và tìm đường giữa các địa điểm du lịch một cách trực quan.

Ứng dụng tích hợp **Google Maps API**, **Weather API** và **JavaScript** để tạo trải nghiệm du lịch thông minh, hỗ trợ người dùng xây dựng lịch trình phù hợp với nhu cầu cá nhân.

---

# 🚀 Features

## 🗺️ Interactive Map

Hiển thị bản đồ và các địa điểm du lịch trên giao diện trực quan.

* Hiển thị marker các địa điểm du lịch
* Hover để xem thông tin địa điểm
* Click để xem chi tiết địa điểm

---

## 🧭 Route Navigation

Hệ thống hỗ trợ tìm đường giữa các địa điểm.

Chức năng:

* Tính khoảng cách giữa các địa điểm
* Tính thời gian di chuyển
* Hiển thị tuyến đường trên bản đồ
* Hỗ trợ nhiều điểm đến (multi-destination route)

---

## 📅 Trip Planner

Người dùng có thể tạo **lịch trình du lịch cá nhân**.

Chức năng:

* Thêm địa điểm vào lịch trình
* Hiển thị danh sách địa điểm đã chọn
* Tính tổng khoảng cách
* Tính tổng thời gian di chuyển
* Hiển thị tuyến đường tối ưu trên bản đồ

---

## 🌙 Day / Night Filter

Hệ thống cho phép lọc địa điểm theo thời gian hoạt động.

| Mode  | Ví dụ địa điểm                   |
| ----- | -------------------------------- |
| Day   | Bảo tàng, công viên, khu du lịch |
| Night | Chợ đêm, quán ăn, khu vui chơi   |

---

## 🌤️ Weather Information

Ứng dụng hiển thị thông tin thời tiết tại địa điểm thông qua API.

Thông tin hiển thị:

* Nhiệt độ
* Trạng thái thời tiết
* Icon thời tiết

Giúp người dùng dễ dàng lựa chọn thời điểm du lịch phù hợp.

---

# 🧠 Smart Tourism Concept

Dự án hướng tới mô hình **Smart Tourism**, giúp:

* Cung cấp thông tin du lịch trực quan
* Hỗ trợ lập kế hoạch chuyến đi
* Cải thiện trải nghiệm du lịch
* Kết hợp dữ liệu bản đồ và dữ liệu thời gian thực

---

# 🏗️ Project Structure

```
SmartTourismAI/
│
├── index.html
│
├── css/
│   └── map.css
│
├── js/
│   ├── map.js
│   ├── route.js
│   ├── tripPlanner.js
│   ├── weather.js
│   └── dayNight.js
│
└── data/
    └── places.json
```

---

# ⚙️ Technologies Used

| Technology      | Purpose                          |
| --------------- | -------------------------------- |
| HTML            | Structure of the web application |
| CSS             | Styling and UI design            |
| JavaScript      | Application logic                |
| Google Maps API | Map and route navigation         |
| OpenWeather API | Weather information              |

---

# 📦 Installation

## 1. Clone the repository

```bash
git clone https://github.com/yourusername/smart-tourism-ai.git
```

---

## 2. Open the project

Mở file sau bằng trình duyệt:

```
index.html
```

---

## 3. Add API Keys

### Google Maps API

Thêm API key vào file HTML:

```html
<script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY"></script>
```

---

### Weather API

Trong file JavaScript:

```javascript
const API_KEY = "YOUR_WEATHER_API_KEY";
```

---

# 🖥️ Demo Functions

Ứng dụng hỗ trợ các chức năng chính:

* Hiển thị bản đồ du lịch
* Hiển thị danh sách địa điểm
* Tìm đường giữa các địa điểm
* Lập lịch trình du lịch
* Hiển thị thời tiết
* Lọc địa điểm theo ngày và đêm

---

# 📈 Future Improvements

Các tính năng có thể phát triển thêm trong tương lai:

* AI chatbot hỗ trợ du lịch
* AI gợi ý lịch trình du lịch
* Phân tích hành vi người dùng
* Giao diện mobile responsive
* Tối ưu tuyến đường du lịch

---

# 👨‍💻 Author

**Bùi Xuân Toàn**

Student Project – Smart Tourism System

---

# 📄 License

This project is developed for **educational purposes**.

