# ✅ Todo MFE – Remote App

This project is the **Remote Microfrontend App** for a Todo List built with **React** and **TypeScript**, exposing independent modules using **Webpack 5 Module Federation**. These modules are loaded into the `todo-mfe-host` app.

---

## 🧠 Exposed Modules

The following modules are exposed to the host app:

1. **TodoList** – Displays the full list of todo items  
2. **TodoItem** – Renders a single task item  
3. **Filter** – Dropdown to filter tasks by status

These modules are federated and dynamically imported by:

👉 [`todo-mfe-host`](https://github.com/rohittiwariofficial/todo-mfe-host)

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/rohittiwariofficial/todo-mfe-remote.git
cd todo-mfe-remote
```

### 2. Install dependencies

```bash
npm install
# or
yarn install
```

### 3. Run the development server

```bash
npm start
# or
yarn start
```

> This will start the remote app at [http://localhost:3001](http://localhost:3001)

---

## ✅ Features

- Fully modular, independently deployable frontend  
- Federated modules exposed via Webpack 5  
- Type-safe codebase using TypeScript  
- Easy integration into any compatible host app

---

## 🔧 Tech Stack

- React  
- TypeScript  
- Webpack 5 (Module Federation)  
- HTML5, CSS3

---

## 🧩 Related Microfrontend

👉 [`todo-mfe-host`](https://github.com/rohittiwariofficial/todo-mfe-host)

---

## 🙋‍♂️ Author

**Rohit Tiwari**  
Senior MERN / Backend Developer  
[LinkedIn](https://www.linkedin.com/in/rohittiwariofficial)

---

## 📜 License

MIT – free to use and modify.
