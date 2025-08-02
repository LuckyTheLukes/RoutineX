# RoutineX

RoutineX is an offline-first Android app designed for small technical crews working in environments without reliable internet access. It helps teams manage recurring maintenance jobs, track subtask progress, and synchronize job data manually via a secure hub — all while logging detailed work history for reporting and accountability.

## 🚀 Features

- 📋 Recurring task management (daily, weekly, monthly, etc.)
- ✅ Checklist-style subtasks with individual progress tracking
- 👥 User login via ID
- 🕓 Time tracking: start, end, and duration per subtask
- 🗂️ Local Room database (fully offline)
- 🔄 Manual data import/export (via local file transfer or Wi-Fi)
- 🧾 Task history logging for reporting
- 🔐 No internet or cloud dependency

## 🧱 Tech Stack

- **Kotlin**
- **MVVM Architecture**
- **Room Database**
- **Coroutines**
- **LiveData / ViewModel**
- **Material UI Components**
- **(Optional) Jetpack Compose**

## 🔧 Requirements

- Android Studio Hedgehog or later
- Minimum SDK: 24 (Android 7.0)
- Target SDK: 34 (Android 14)

## 🗃️ Folder Structure (Simplified)


com.routinex/

├── data/

│ ├── db/

│ ├── models/

│ └── repository/

├── ui/

│ ├── activities/

│ ├── fragments/

│ ├── viewmodels/

│ └── adapters/

├── utils/

└── App.kt


## 📥 Sync Process

RoutineX does not require the internet. Data is manually exported/imported using:

- USB
- Wi-Fi file sharing
- Local area sync (e.g., to a laptop hub)

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.

---

Built by [Lucky](https://github.com/LuckyTheLukes/)
