# 🏦 Bank Application

A banking web application featuring loan calculators for mortgages, car loans, and consumer credit.  
Built with **React** and bootstrapped with Create React App.

---

## 📌 Description

**Bank Application** is a frontend React application that helps users calculate loan payments across three categories: fixed-rate mortgages, car loans, and consumer loans. The app includes an admin panel and is built entirely with JSX components and CSS.

---

## 🧠 Features

- 🏠 **Mortgage Calculator** — fixed-rate mortgage payment breakdown
- 🚗 **Car Loan Calculator** — monthly payments for auto financing
- 💳 **Consumer Loan Calculator** — personal credit calculation
- 👤 **User Login** — authentication with session support
- 🔐 **Admin Panel** — manage users and application data
- 📱 Responsive layout across all screen sizes
- ⚛️ Component-based architecture with React

---

## 🛠 Technologies Used

| Layer        | Technology       |
|--------------|------------------|
| Frontend     | React, JSX, CSS3 |
| Bootstrapped | Create React App |

---

## 🚀 Quick Start

### Requirements

- Node.js 14+
- npm or yarn

### Clone the Repository
```bash
git clone https://github.com/babayaga0x/Bank-application.git
cd Bank-application/frontend/my-bank
```

### Install Dependencies
```bash
npm install
```

### Run in Development Mode
```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.  
The page will reload automatically on file changes.

---

## 🔐 Admin Panel

To access the admin panel, navigate to:
```
http://localhost:3000/admin
```

| Field    | Value   |
|----------|---------|
| Login    | `admin` |
| Password | `admin` |

---

## 📁 Project Structure
```
Bank-application/
│
└── frontend/
    └── my-bank/
        │
        ├── public/                 # Static assets
        │
        ├── src/
        │   └── components/
        │       ├── Header.jsx      # Navigation header
        │       ├── Header.css
        │       ├── Login.jsx       # User login form
        │       ├── Login.css
        │       ├── AdminPanel.jsx  # Admin dashboard
        │       ├── AdminPanel1.css
        │       ├── Calc1.jsx       # Mortgage calculator
        │       ├── Calc1.css
        │       ├── Calc2.jsx       # Car loan calculator
        │       ├── Calc2.css
        │       ├── Calc3.jsx       # Consumer loan calculator
        │       └── Calc3.css
        │
        ├── package.json
        └── package-lock.json
```

---

## 📦 Available Scripts

### `npm start`
Runs the app in development mode at [http://localhost:3000](http://localhost:3000).  
Hot-reloads on file changes. Lint errors are shown in the console.

### `npm test`
Launches the test runner in interactive watch mode.

### `npm run build`
Builds the app for production into the `build/` folder.  
Bundles React in production mode and optimizes for best performance.  
Output is minified and filenames include content hashes — ready to deploy.

### `npm run eject`
> ⚠️ **One-way operation — cannot be undone.**

Ejects the CRA configuration, copying webpack, Babel, and ESLint configs directly into the project. Use only if you need full control over the build tooling.

---

## 🌐 Deployment

The production build is a fully static bundle that can be served from any host:

| Platform     | Method                                 |
|--------------|----------------------------------------|
| GitHub Pages | Deploy `build/` via `gh-pages` package |
| Netlify      | Drag & drop `build/` folder            |
| Vercel       | Connect GitHub repo, auto-detects React|

Build for production:
```bash
npm run build
```

---

## 📄 License

Open source — free to use, fork, and adapt for personal or educational projects.
