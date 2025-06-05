# ✅ Remote Todo App – React Micro Frontend

This is the **remote MFE** (Micro Frontend) that exposes a **Todo List Component** for use in a host container via **Webpack 5 Module Federation**.

---

## 📦 Tech Stack

- React
- Webpack 5 Module Federation
- JavaScript
- Micro Frontend Architecture

---

## 🚀 How It Works

This app exposes its **Todo App** module to be consumed by:

🔗 [`host-app`](https://github.com/rohittiwariofficial/host-app)

It uses Webpack's `ModuleFederationPlugin` to expose remote components.

---

## 🔧 Setup & Run

### 1. Clone the repo

```bash
git clone https://github.com/rohittiwariofficial/remote-todo-app
cd remote-todo-app
npm install
```

### 2. Start the app

```bash
npm start
```

> ℹ️ This app runs by default on `http://localhost:3001` and exposes its module to the host app.

---

## 🧠 Folder Structure

```
remote-todo-app/
├── public/
├── src/
│   ├── TodoApp.js
│   └── bootstrap.js
├── webpack.config.js
```

---

## 🧩 Related Project

This app is designed to be consumed by:

👉 [`host-app`](https://github.com/rohittiwariofficial/host-app)

---

## 🙋‍♂️ Author

**Rohit Tiwari**  
Senior MERN / Backend Developer  
[LinkedIn](https://www.linkedin.com/in/rohittiwariofficial)

---
