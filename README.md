
# 📋 Smart Attendance System

## 📑 Project Overview

The **Smart Attendance System** is a Python-based application that leverages **face recognition technology** to automate and manage student or employee attendance. Using **OpenCV** and the **LBPH (Local Binary Patterns Histograms)** algorithm, the system accurately identifies individuals from a pre-registered dataset and records their attendance automatically in structured files (CSV/XLSX).

This project reduces manual attendance efforts, enhances accuracy, and provides a modern, AI-driven solution for educational institutes and organizations.

---

## 🛠️ Features

✅ Face Recognition using LBPH
✅ Real-time Attendance Marking via Webcam
✅ Structured Data Storage (CSV / XLSX)
✅ Simple GUI (CLI-based, optional future GUI with PyQt)
✅ Dataset Management Utilities (Enroll / Delete / Update)
✅ Attendance Reports
✅ Email Attendance Feature (Optional)
✅ Cleanup Utilities for File Management

---

## 🧑‍💻 Technologies Used

| Technology                 | Purpose                             |
| -------------------------- | ----------------------------------- |
| Python 3.13.2              | Core Language                       |
| OpenCV                     | Computer Vision / Face Detection    |
| Numpy                      | Data Handling                       |
| Pandas                     | DataFrames / Export CSV/XLSX        |
| PyQt5 / Tkinter (Optional) | GUI (Planned/Future)                |
| OS / shutil                | File & Directory Handling           |
| datetime                   | Time & Date Utilities               |
| smtplib                    | Email Attendance Reports (Optional) |

---

## 📂 Project Structure

```
Smart_Attendance_system/
├── attendance/
│   ├── attendance.csv
│   └── attendance.xlsx
├── dataset/
│   └── (stored face images)
├── trained_model/
│   └── recognizer.yml
├── data/
│   └── (user details if any)
├── main.py
├── face_recognition.py
├── data_upload.py
├── attendance_marking.py
├── email_sender.py (Optional)
├── cleanup.py
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run

### 1️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 2️⃣ Run the Project

```bash
python main.py
```

---

## 🧾 Main Functionalities

| Functionality                 | Description                                  |
| ----------------------------- | -------------------------------------------- |
| **Enroll User**               | Capture & store face dataset for new user    |
| **Train Model**               | Train LBPH recognizer with captured datasets |
| **Mark Attendance**           | Real-time recognition & attendance marking   |
| **View Attendance**           | Export/view attendance sheets                |
| **Send Attendance via Email** | Send CSV/XLSX reports via email (optional)   |
| **Cleanup**                   | Manage old datasets and logs                 |

---

## 🏗️ Future Scope

🔹 Upgrade GUI with PyQt5
🔹 Cloud Integration (Firebase / AWS)
🔹 SMS / WhatsApp API for Attendance Reports
🔹 Better Encryption & Security for Data
🔹 Multi-Factor Authentication

---

## 📌 Sample Attendance Output

```
| Name       | Date       | Time    | Status    |
|------------|------------|---------|-----------|
| John Doe   | 2025-07-19 | 10:15AM | Present   |
| Jane Smith | 2025-07-19 | 10:17AM | Present   |
```

## 🤝 Contributors

**Tarun Marskolhe**
Email: [tarunmarskolhe14@gmail.com](mailto:tarunmarskolhe14@gmail.com)
Phone: 7758895367

---

## ⚖️ License

This project is licensed for **academic, learning, and personal demonstration purposes.**
For commercial use, contact the author.
