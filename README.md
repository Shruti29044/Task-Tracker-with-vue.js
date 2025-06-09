# 📝 Task Tracker

A simple task tracking application built with **Vue 3**, **Vite**, and **Axios**. This project demonstrates how to create a dynamic frontend with Vue, supporting task creation, deletion, and status toggling.

## 🚀 Features

- Add and delete tasks
- 
- Toggle task completion status
- 
- Persistent state with mock API (or local backend)
- 
- Clean and responsive UI with Vue 3 Composition API
- 
- Axios for handling HTTP requests
- 
- Vue Router (if navigation is used)

## 📦 Tech Stack

- [Vue 3](https://vuejs.org/)
- 
- [Vite](https://vitejs.dev/)
- 
- [Axios](https://axios-http.com/)
- 
- [Vue Router](https://router.vuejs.org/) (optional)

## 📁 Project Setup

Clone the repo


git clone https://github.com/yourusername/vue-task-tracker.git

cd vue-task-tracker

Install dependencies

npm install

Start the dev server

npm run dev

App will be runnig at local   http://localhost:8080/

🏗️ Build for production

npm run build

To preview the production build locally:

npm run serve

🛠 Directory Structure

vue-task-tracker/

├── public/

├── src/

│   ├── components/

│   ├── views/

│   ├── App.vue

│   └── main.js

├── package.json

└── vite.config.js

🤝 Contributing

Feel free to fork and submit a pull request if you’d like to improve the app or add new features!

⚠️ Challenges Faced 

🔧 Vue 2 to Vue 3 Migration

The initial template was based on Vue 2, which led to compatibility issues with Vue 3 packages and tooling.

Refactoring the main.js setup and updating package dependencies to support Vue 3 resolved this.

⚙️ Vite Configuration

Switching from the Vue CLI to Vite required changes in scripts and module resolution.

Some dependencies (e.g., Vue Router and Axios) needed proper integration with the new Vite-based setup.

🧱 Missing Build Directory

Running npm run serve initially failed due to the missing dist/ folder.

This was fixed by first executing npm run build to generate the production-ready files.

📦 Dependency Warnings

Encountered deprecated packages during global CLI installations.

Resolved by updating to Vue 3-compatible libraries and avoiding deprecated tooling like Vue CLI in favor of Vite.

🌐 Port Accessibility

After launching the dev server, accessing the app via localhost:5173 initially showed 404 errors due to incorrect routing or missing entry files.

Fixed by ensuring the correct App.vue mounting and directory structure.






