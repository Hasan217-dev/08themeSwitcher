# 🎨 Theme Switcher

A modern, responsive **dark/light theme switcher** built with React, Vite, and Tailwind CSS. Seamlessly toggle between themes with instant visual feedback.

## ✨ Features

- **Light & Dark Mode**: Switch between beautifully designed light and dark themes
- **React Context API**: Centralized theme state management
- **Tailwind CSS**: Utility-first styling with responsive design
- **Fast HMR**: Hot Module Replacement for instant development feedback
- **ESLint Integration**: Code quality and consistency checks

## 🚀 Quick Start

### Prerequisites
- Node.js 16+ 
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/08themeSwitcher.git

# Navigate to the project
cd 08themeSwitcher

# Install dependencies
npm install

# Start development server
npm run dev
```

The app will be available at `http://localhost:5173`

## 📦 Build

```bash
# Build for production
npm run build

# Preview the production build locally
npm preview
```

## 🧪 Linting

```bash
# Run ESLint to check code quality
npm run lint
```

## 📁 Project Structure

```
src/
├── components/
│   ├── ThemeBtn.jsx      # Theme toggle button
│   └── Card.jsx          # Content card component
├── contexts/
│   └── theme.js          # Theme context provider
├── App.jsx               # Main application component
├── main.jsx              # Application entry point
└── index.css             # Global styles
```

## 🎯 How It Works

1. **Theme Context**: The `ThemeProvider` wraps the app and manages the theme state
2. **Theme Toggle**: Click the theme button to switch between light and dark modes
3. **Dynamic Styling**: Tailwind CSS classes respond to the active theme class on the HTML element

## 🛠 Tech Stack

- **React 19** - UI library
- **Vite 7** - Build tool with instant HMR
- **Tailwind CSS 4** - Utility-first CSS framework
- **ESLint** - Code linting

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

Created as a learning project for React theme management patterns.
