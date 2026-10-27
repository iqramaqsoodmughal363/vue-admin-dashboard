# 🖥️ Vue Admin Dashboard

<p align="center">
  <b>A fast, modern, and responsive Admin Dashboard built with Vue 3 & Vite.</b>
</p>

<p align="center">
  <em>"A robust frontend application featuring user authentication, a dynamic dashboard, and user management views."</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red" alt="Made with Love">
  <img src="https://img.shields.io/badge/Framework-Vue.js%203-42b883" alt="Vue.js">
  <img src="https://img.shields.io/badge/Bundler-Vite-646cff" alt="Vite">
  <img src="https://img.shields.io/badge/Status-Complete-success" alt="Status">
</p>

---

## 📋 Overview

This project is a **Vue 3** based Admin Dashboard. It utilizes **Vite** for lightning-fast development and bundling, and **Vue Router** for client-side navigation. The structure is designed to handle role-based access (Admin/User) with dedicated views for Login, Dashboard, and User Management.

---

## ✨ Key Features

* **⚡ Vite Powered:** Ultra-fast cold server start and Hot Module Replacement (HMR).
* **🛣️ Vue Router:** Seamless navigation between Login, Dashboard, and Users views.
* **🗂️ State Management:** Uses `stores` (likely Pinia or Vuex) to manage authentication state.
* **📱 Responsive Design:** Custom CSS (`style.css`) ensures the dashboard looks great on all devices.
* **🔐 Authentication Flow:** Includes an `auth.js` store to handle user sessions.

---

## 🛠️ Tech Stack

| Category | Tools / Technologies |
|---|---|
| **Framework** | Vue.js 3 |
| **Build Tool** | Vite |
| **Routing** | Vue Router |
| **State Management** | Pinia / Vuex (located in `src/stores`) |
| **Styling** | Custom CSS / Scoped CSS |
| **Language** | JavaScript (ES6+) |

---

## 📂 Project Structure

```text
vue-admin-dashboard/
│
├── public/                 # Static assets
├── src/
│   ├── assets/             # Images, logos (hero.png, vue.svg)
│   ├── components/         # Reusable UI components (HelloWorld.vue)
│   ├── router/             # Vue Router configuration (index.js)
│   ├── stores/             # State management (auth.js)
│   ├── views/              # Page views
│   │   ├── DashboardView.vue
│   │   ├── LoginView.vue
│   │   └── UsersView.vue
│   ├── App.vue             # Root component
│   ├── main.js             # App entry point
│   └── style.css           # Global styles
├── index.html              # Main HTML file
├── package.json            # Dependencies and scripts
└── vite.config.js          # Vite configuration
```

---

## 🚀 How to Build and Run

### Prerequisites
* **Node.js** (v14.18+ or v16+)
* **npm** or **yarn**

### Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/iqramaaqsoodmughal363/vue-admin-dashboard.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd vue-admin-dashboard
   ```

3. **Install Dependencies**
   ```bash
   npm install
   ```

4. **Run the Development Server**
   ```bash
   npm run dev
   ```
   *Open `http://localhost:5173` in your browser.*

5. **Build for Production**
   ```bash
   npm run build
   ```

---

## 🎯 Key Takeaways

* **Component-Based Architecture:** Vue's single-file components (`.vue`) make the code highly modular and reusable.
* **Client-Side Routing:** Smooth transitions between views without page reloads.
* **Fast Development:** Vite's HMR makes the development experience incredibly fast.

---

## 👩‍💻 Author

**Iqra Maqsood Mughal**

*Software Engineer · Full-Stack Developer · Code Craftsman · Android App Developer · Problem Solver 🚀*

```javascript
const codeIsLife = "Code is life";
while (true) { learn(); build(); innovate(); }
```

---

## 📅 Date

October 27, 2026

---

## 📄 License

This project is intended for educational and personal use purposes.
