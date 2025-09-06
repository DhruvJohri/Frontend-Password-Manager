# 🔐 PassOP – Password Manager  

[![CI](https://img.shields.io/badge/CI-passing-brightgreen?style=flat-square&logo=github)](https://github.com/) [![npm](https://img.shields.io/badge/npm-MERN-orange?style=flat-square&logo=npm)](https://www.npmjs.com/) [![license](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](./LICENSE) [![Live Preview](https://img.shields.io/badge/Live-Preview-ff69b4?style=flat-square&logo=vercel)](https://frontend-password-manager-lemon.vercel.app/)  

---

## 📖 Overview
**PassOP** is a full-stack password manager 🔐 built with the **MERN stack**.  
It allows users to **securely save, view, edit, and delete** website credentials (URL, username, password).  
The UI is **responsive, clean, and interactive**, styled with **Tailwind CSS** + **React Toastify** for smooth user feedback.  

👉 **Live Demo:** [frontend-password-manager-lemon.vercel.app](https://frontend-password-manager-lemon.vercel.app/)  

---

## 🛠️ Tech Stack
- 🗄️ **MongoDB** – Store encrypted password entries  
- ⚙️ **Express.js** – REST API backend  
- ⚡ **React (Vite)** – Modern frontend  
- 🖥️ **Node.js** – Backend runtime  
- 🎨 **Tailwind CSS** – Responsive UI styling  
- 🔔 **React-Toastify** – Notifications & feedback  

---

## 🔑 Features
✅ Save, view, edit, and delete credentials  
✅ Passwords masked by default (toggle to show 🔒)  
✅ One-click copy for site, username & password  
✅ Toast notifications for actions (copy, save, delete)  
✅ Fully responsive & mobile-friendly UI  
✅ Secure backend with **MongoDB Atlas**  

---

## 📂 Project Structure

```bash
passop-mongo
┣ 📂 backend         # Express.js + MongoDB API
┃ ┗ server.js        # Backend entry point
┣ 📂 src             # React frontend
┃ ┣ 📂 components
┃ ┃ ┗ Manager.jsx    # Core password manager logic
┃ ┗ App.jsx          # Root app (Navbar + Manager + Footer)
┗ README.md
```

---

## 🚀 Getting Started (Local Setup)

### 1️⃣ Clone the repo
```bash
git clone https://github.com/your-username/passop-mongo.git
cd passop-mongo
cd backend
npm install
npm start
```
---
## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

🚀Fork the repo

🌐Create a feature branch (git checkout -b feature-name)

🔍Commit changes (git commit -m 'Add feature')

🌟Push and open a PR 🚀

---

## 📜 License

This project is licensed under the MIT License.
Feel free to use, improve, and share ✨
---
## 💡 Built with ❤️ + ☕ by Dhruv Johri
