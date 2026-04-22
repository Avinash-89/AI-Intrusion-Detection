# 🚨 AI Intrusion Detection System

A modern AI-powered surveillance desktop application that detects vehicle intrusions from video input using YOLO and provides a professional dashboard interface.

---

## 🔥 Features

* 🔐 Login & Registration System
* 🎥 Video Upload & Processing
* 🚗 Car Detection (YOLOv8)
* 🎨 Green Vehicle Filtering
* 🚨 Intrusion Detection Logic
* 📸 Automatic Evidence Capture
* 🧠 SQLite Database Logging
* 📋 Interactive History Panel
* 🎯 Modern UI (CustomTkinter)

---

## 🛠️ Tech Stack

* Python
* OpenCV
* YOLOv8 (Ultralytics)
* CustomTkinter
* SQLite
* Pillow

---

## 📂 Project Structure

```
AI-Intrusion-Detection-System/
│
├── main.py
├── yolov8n.pt
├── detections.db
├── evidence/
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ⚙️ Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/AI-Intrusion-Detection-System.git
cd AI-Intrusion-Detection-System
```

---

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 3️⃣ Run Application

```bash
python main.py
```

---

## 🧠 How It Works

1. Login / Register
2. Upload a video
3. Start detection
4. System detects cars using YOLO
5. Ignores green vehicles
6. Detects intrusion when boundary is crossed
7. Saves image + logs event in database

---

## 📊 Database Schema

### Users Table

| Field    | Type    |
| -------- | ------- |
| id       | INTEGER |
| username | TEXT    |
| password | TEXT    |

### Detections Table

| Field      | Type    |
| ---------- | ------- |
| id         | INTEGER |
| timestamp  | TEXT    |
| image_path | TEXT    |
| event_type | TEXT    |

---

## 📸 Screenshots

*(Add screenshots here for better presentation)*

---

## 📦 Convert to EXE

```bash
pip install pyinstaller
pyinstaller --onefile --noconsole --add-data "yolov8n.pt;." main.py
```

---

## ⚠️ Important Notes

* Keep `yolov8n.pt` in project root
* Database auto-creates on first run
* Works fully offline

---

## 🚀 Future Scope

* Live CCTV integration
* Email/SMS alerts
* Cloud database
* Admin panel
* Analytics dashboard

---

## 👨‍💻 Author

**Avinash Kumar Gupta**
BCA (Data Science & AI)

---

## ⭐ If you like this project

Give it a star ⭐ on GitHub!
