# 🗂️ Cloud Ops Hub

A modern and responsive **Project Management Web Application** built with React.js and Redux Toolkit. Manage your projects, tasks, and team members efficiently from a single dashboard.

![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)
![React](https://img.shields.io/badge/React-18-blue)
![Redux](https://img.shields.io/badge/Redux-Toolkit-purple)
![License](https://img.shields.io/badge/License-MIT-yellow)

🔗 **Live Demo:** [cloud-ops-hub.netlify.app](https://cloud-ops-hub.netlify.app)
📁 **GitHub:** [github.com/akshaykumar12151/cloud-ops-hub](https://github.com/akshaykumar12151/cloud-ops-hub)

---

## 📌 Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Screenshots](#-screenshots)
- [License](#-license)

---

## ✨ Features

- 📊 **Dashboard Overview** — Real-time stats including total projects, completed tasks, and overdue items
- 📁 **Project Management** — Create and track multiple projects with progress indicators and due dates
- ✅ **Task Management** — Create tasks with priority levels (High, Medium, Low) and status tracking
- 👥 **Team Collaboration** — Add and invite team members to projects
- 🏢 **Multi-Workspace Support** — Switch between multiple workspaces seamlessly
- 📈 **Project Analytics** — Visual analytics and calendar view for each project
- 🕐 **Recent Activity Feed** — Track all recent project and task activities
- 🌙 **Dark / Light Mode** — Toggle between dark and light themes
- 📱 **Responsive UI** — Clean and modern interface with sidebar navigation

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **React.js 18** | Frontend Framework |
| **Redux Toolkit** | State Management |
| **Vite** | Build Tool |
| **JavaScript (ES6+)** | Programming Language |
| **CSS** | Styling |
| **ESLint** | Code Quality |

---

## 📁 Project Structure
```
cloud-ops-hub/
├── public/
├── src/
│   ├── app/
│   │   └── store.js
│   ├── assets/
│   ├── components/
│   │   ├── Navbar.jsx
│   │   ├── Sidebar.jsx
│   │   ├── ProjectCard.jsx
│   │   ├── ProjectTasks.jsx
│   │   ├── ProjectAnalytics.jsx
│   │   ├── ProjectCalendar.jsx
│   │   ├── CreateTaskDialog.jsx
│   │   ├── CreateProjectDialog.jsx
│   │   ├── MyTasksSidebar.jsx
│   │   ├── RecentActivity.jsx
│   │   ├── StatsGrid.jsx
│   │   └── ...more
│   ├── features/
│   │   ├── themeSlice.js
│   │   └── workspaceSlice.js
│   ├── pages/
│   │   ├── Dashboard.jsx
│   │   ├── Projects.jsx
│   │   ├── ProjectDetails.jsx
│   │   ├── TaskDetails.jsx
│   │   └── Team.jsx
│   ├── App.jsx
│   └── main.jsx
├── .gitignore
├── index.html
├── package.json
└── vite.config.js
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/akshaykumar12151/cloud-ops-hub.git
```

2. **Go to project directory**
```bash
cd cloud-ops-hub
```

3. **Install dependencies**
```bash
npm install
```

4. **Run development server**
```bash
npm run dev
```

5. **Open in browser**
```
http://localhost:5173
```

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE.md](LICENSE.md) file for details.

---

## 👨‍💻 Author

**Akshay Kumar**
- GitHub: [@akshaykumar12151](https://github.com/akshaykumar12151)

---

⭐ **If you found this project helpful, don't forget to give it a star!** ⭐
