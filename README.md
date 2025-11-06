# 🥗 FitTrack – Calorie Manager

[![React](https://img.shields.io/badge/React-18-blue?logo=react)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)](https://www.typescriptlang.org/)
[![Material UI](https://img.shields.io/badge/Material%20UI-5-007FFF?logo=mui&logoColor=white)](https://mui.com/)
[![Vite](https://img.shields.io/badge/Vite-5-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/)
[![Recharts](https://img.shields.io/badge/Recharts-visualization-ff69b4)](https://recharts.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

---

## 🧠 About the Project

**FitTrack** is a modern and responsive web app to track daily calorie intake
and exercise.

Built with **React + TypeScript**, **Material UI**, and **Context API +
useReducer** for scalable global state management.  
It allows users to **log meals and activities**, **visualize calorie balance**,
and **switch between light and dark themes** with persistent data in
**LocalStorage**.

## 🌐 Live Demo

[👉 Watch the Demo](https://fittrack-dev.netlify.app)

## 📸 Screenshots

<p align="center">
  <img src="./public/screen1.png" width="280" alt="Add Activity"/>
  <img src="./public/screen2.png" width="280" alt="Summary"/>
  <img src="./public/screen3.png" width="280" alt="Meals & Activities"/>
</p>

## 🚀 Tech Stack

- ⚛️ React 18 + TypeScript

- 🎨 Material UI (MUI) for responsive design

- 🧠 Context API + useReducer for global state

- 🍿 notistack for toast notifications

- 📊 Recharts for data visualization

- 💾 LocalStorage persistence (no backend required)

- 🌗 Light/Dark mode with ThemeProvider

- ⚡ Vite for lightning-fast builds

## ✨ Features

✅ Add, edit, and delete meals or exercises ✅ Track calories consumed, burned,
and net balance ✅ Visualize data with a dynamic bar chart ✅ Toggle between
light and dark themes ✅ Responsive Material UI design ✅ LocalStorage data
persistence ✅ Real-time notifications and confirmations

🧠 What I Learned

This project helped me deepen my skills in:

- Architecting apps with Context API + useReducer instead of Redux

- Building scalable and reusable components with MUI

- Managing complex UI state in React with TypeScript

- Implementing snackbar notifications with notistack

- Creating responsive dashboards with clean code and performance in mind

## 📁 Folder Structure

```
src/
 ├── components/       # UI and visual components
 ├── context/          # Global contexts and providers
 ├── data/             # Static data (categories)
 ├── hooks/            # Custom hooks (activity, theme)
 ├── reducers/         # useReducer logic
 ├── types/            # TypeScript types and interfaces
 ├── App.tsx           # Root component
 └── main.tsx          # App entry point
```

## 🛠️ Getting Started

```
# 1. Clone the repository
git clone https://github.com/guillevarelabarros/fittrack-calorie-manager.git
cd fittrack-calorie-manager

# 2. Install dependencies
yarn install

# 3. Start the development server
yarn dev

# 4. Build for production
yarn build
```

## 🧑‍💻 Author

Guillermo Ignacio Varela Barros

- 🔗 LinkedIn: https://www.linkedin.com/in/guillevarelabarros

- 💻 GitHub: https://github.com/guillevarelabarros

## 🔗 Useful Links

📹 Demo: https://fittrack-dev.netlify.app

💻 Repository:
https://github.com/guillevarelabarros/react-fittrack-calorie-manager

## 💡 Quote

“It’s not just about counting calories — it’s about taking control.” — Guille
Varela Barros 💪

## 🏷️ Why This Project?

FitTrack demonstrates:

- Clean front-end architecture

- Real-world use of TypeScript + React Hooks

- UI/UX design with Material UI

- Data visualization and state persistence

- Production-ready React app structure
