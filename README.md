# 🚀 React Monorepo - Course from scratch with Midudev

This is a **multi-package monorepository** containing multiple React projects created as part of a course for learning from scratch, following the teachings of Midudev.

## 📦 Monorepository Structure

```
course-from-0/
├── package.json                	# Main configuration of the monorepo
├── projects/                   	# Folder containing all projects
│   └── 01-twitter-follow-card/         # First project: Hello World
├── .git/                       	# Initialized Git repository
└── README.md                   	# This file
```

## 🛠️ Selected Technology Stack

- **React** - Primary library for user interfaces
- **Vite** - Ultra-fast build tool
- **SWC** - Super-fast Rust-based compiler (superior alternative to Babel)
- **JavaScript** - Initial language (with planned migration to TypeScript)
- **Git** - Version control with remote repository on GitHub

## 🚀 How to Run the Project

### First Project: 01-twitter-follow-card

1. **Navigate to the project directory:**
```bash
cd projects/01-twitter-follow-card
```

2. **Install dependencies** (if they haven't been installed):
```bash
npm install
```

3. **Run in development mode:**
```bash
npm run dev
```

## 📋 Creation Process Complete

✅ **Git repository initialized and connected to GitHub**  
✅ **Main package.json created** (`npm init -y`)  
✅ **Monorepository structure established** (`projects/` folder)  
✅ **First React project created** with Vite + SWC  
✅ **Dependencies installed** correctly  
✅ **Development server running** on port 5173  

## 🎯 Technical Decisions

### Why SWC instead of Babel?
- ⚡ **Superior performance**: Much faster compilation
- 🦀 **Based on Rust**: Greater efficiency and security
- 🔮 **Future**: Coming soon as the default in Vite
- 🎯 **Modern**: Excellent support for ES6+ and JSX

### Why Monorepository?
- 🗂️ **Organization**: Multiple related projects in one place
- 🔄 **Consistency**: Same configurations and dependencies
- 🚀 **Efficiency**: Code sharing between projects
- 📚 **Learning**: Visible progression from simple to complex

## 📝 Commands Executed

```bash
# Initialize Git and connect to GitHub
git init
git add README.md
git commit -m “first commit”
git branch -M main
git remote add origin https://github.com/
git push -u origin main

# Monorepository configuration
npm init -y
mkdir projects
cd projects

# Creating the first project with Vite
npm create vite@latest
# → Name: 01-twitter-follow-card
# → Framework: React
# → Variant: JavaScript + SWC

# Installation and execution
cd 01-twitter-follow-card
npm install
npm run dev
```

## 🌟 Key Features

- **Modular architecture**: Easy addition of new projects
- **Optimized configuration**: Vite + SWC for maximum performance
- **Solid foundation**: Ready to scale in complexity
- **Best practices**: Clear and organized structure from the start

**Problems or suggestions?**  
Open an issue on [GitHub](https://github.com/LuisFCosteC/React.JS-projects-with-Mdudev/issues) so we can improve together!

**Next step:** Start developing our first React component in `projects/01-twitter-follow-card/src/App.jsx` 🎉