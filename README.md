# ⚡ Actionory - The Ultimate Productivity Workspace

![Actionory Banner](https://via.placeholder.com/1200x400?text=Actionory+Dashboard+Preview)

> **Unlock unlimited potential for your productivity.** > Actionory is a modern, cross-platform productivity application designed to combine Task Management, Time Blocking, and Habit Tracking into a single, beautiful interface.

![Version](https://img.shields.io/badge/version-1.0.4-blue.svg)
![Electron](https://img.shields.io/badge/Electron-v28-2B2E3A?logo=electron)
![React](https://img.shields.io/badge/React-v18-61DAFB?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-v5-3178C6?logo=typescript)
![License](https://img.shields.io/badge/license-Private-red.svg)

## ✨ Key Features

* **🖥️ Cross-Platform:** Works seamlessly on **Web** and **Desktop (Windows)** with a single codebase.
* **🎨 Custom UI:** Features a completely custom **TitleBar** with native Windows snapping integration, dark mode, and a "Notion-style" utility menu.
* **🔄 Auto-Update System:** Built-in OTA updates using `electron-updater` and GitHub Releases.
* **⏳ Time Blocking System:** Visual timeline to manage your day with "Live", "Past", and "Future" block statuses.
* **🔐 Secure Authentication:** Google OAuth integration with Deep Linking (`actionory://`) support for desktop login.
* **⚡ High Performance:** Built with **Vite** for lightning-fast reloading and optimized builds.
* **📊 Analytics:** Dashboard with charts and insights into your productivity trends.

## 🛠️ Tech Stack

**Frontend:**
* React.js
* TypeScript
* TailwindCSS (Styling)
* Framer Motion (Animations)
* Lucide React (Icons)
* Zustand (State Management)
* React Router DOM (Smart routing for Web vs Electron)

**Desktop (Electron):**
* Electron JS
* Electron Builder (Packaging)
* Electron Updater (Auto-updates)

**Backend / Services:**
* REST API (Node.js/Express)
* MongoDB (Database)

## 🚀 Getting Started

### Prerequisites
* Node.js (v18 or higher)
* npm or yarn

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/uiamirali/actionory-source.git](https://github.com/uiamirali/actionory-source.git)
    cd actionory
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Setup Environment Variables:**
    Create a `.env` file in the root directory:
    ```env
    VITE_API_URL=http://localhost:5000/api
    VITE_GOOGLE_CLIENT_ID=your_google_client_id
    ```

### Running in Development Mode

You need two terminals to run the Desktop version:

**Terminal 1 (React Server):**
```bash
npm run devv
