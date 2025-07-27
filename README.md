# Business Management System (BMM) – React + Vite

A role-based Business Management Web App built using React and Vite.  
This app includes separate dashboards for **Owners** and **Employees**, each with unique UI and features to manage daily business operations efficiently.

---

## 🚀 Features

- 🔐 Role-based redirection (Owner / Employee)
- 👑 Owner Dashboard with cards, charts, and detailed business insights
- 👷 Employee Dashboard with tasks, shifts, attendance, and announcements
- 🧭 Sidebar + Navbar layout for both roles
- 🎨 Responsive, clean and professional UI
- ⚡ Fast builds and dev environment via Vite

---

## 🛠️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- npm (comes with Node)

---

### 📦 Installation

```bash
git clone https://github.com/bharat-2004/Business-Management-Model.git
cd business-management-system
npm install
npm run dev
```

After starting, open in your browser:

👉 **Owner Dashboard:**  
[http://localhost:5173/owner/dashboard](http://localhost:5173/owner/dashboard)

👉 **Employee Dashboard:**  
[http://localhost:5173/employee/dashboard](http://localhost:5173/employee/dashboard)

---

## 📁 Project Structure (Simplified)

```
src/
  components/
    Navbar.jsx
    Sidebar.jsx
    ProtectedRoute.jsx
  pages/
    login/
      Login.jsx
    owner/
      Dashboard.jsx
      Inventory.jsx
      Revenue.jsx
      Alerts.jsx
    employee/
      Dashboard.jsx
      Tasks.jsx
      ShiftInfo.jsx
      Announcements.jsx
      Attendance.jsx
  context/
    AuthContext.jsx
  App.jsx
  main.jsx
```

---

## 🧑‍💼 Usage

1. Run `npm run dev`
2. Go to login page → Select **Owner** or **Employee**
3. Get redirected to your respective dashboard
4. Use sidebar to navigate different sections

---

## 🛠️ Built With

- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [React Router DOM](https://reactrouter.com/)
- Context API

---

## 📜 License

MIT – Use freely with credit.
