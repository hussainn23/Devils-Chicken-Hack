# Devils-Chicken-Hack


 Devils-Chicken-Hack is a role-based Android application designed to manage and access multiple game-related modules from a single dashboard. The app provides controlled access to features based on user roles, ensuring security and simplicity.

---

## 📱 App Name

 Devils-Chicken-Hack

---

## 🎯 Purpose

The app allows admins and specific role users to access different game tools/modules such as Dragon Tiger, Baazigar, Mafia Hacks, and more — all from one centralized interface.

---

## 🔐 Role-Based Access

Each user sees only the modules allowed for their role.

### Available Roles:



---

## 🧩 Features

* Secure login system
* Role-based UI visibility
* Clean & minimal dashboard
* Click-based navigation to game modules
* Logout & session handling using SharedPreferences
* No night mode (forced light mode)

---

## 🛠 Tech Stack

* **Language:** Kotlin
* **Architecture:** Activity-based
* **UI Binding:** ViewBinding
* **Storage:** SharedPreferences
* **Minimum SDK:** As per project configuration

---

## 📂 Project Structure (Key Files)

```
com.example.dragon_chicken_aviatoradmin
│
├── MainActivity.kt
├── ActivityLogin.kt
├── ActivityGame.kt
├── SharedPref.kt
├── res/layout/activity_main.xml
└── AndroidManifest.xml
```

---

## ▶️ How It Works

1. User logs in
2. Role is fetched from SharedPreferences
3. Dashboard loads only permitted game cards
4. Clicking a card opens `ActivityGame` with game name & ID
5. Logout clears session and redirects to login screen

---

## 🔧 Setup Instructions

1. Clone the repository
2. Open in Android Studio
3. Sync Gradle
4. Run on a physical device or emulator

---

## ⚠️ Important Notes

* Ensure all CardView IDs exist in **all layout variants**
* Use the same `activity_main.xml` structure across layouts
* App is designed for internal / controlled use

---

## 📞 Support

For issues or improvements, contact the app administrator.

---

## 📌 Disclaimer

This application is intended for educational and internal use only. The developer is not responsible for misuse.

---
