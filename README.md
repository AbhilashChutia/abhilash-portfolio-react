# Portfolio Website

Welcome to my **personal portfolio website**! This project showcases my skills, projects, and experience as a **front-end developer**. Built with **React** and **Vite**, and deployed using **GitHub Pages**.

## Tech Stack

- **React**  - A powerful JavaScript library for building user interfaces
- **Vite**  - A fast and modern frontend build tool for React
- **CSS Modules**  - Scoped and maintainable styles
- **GitHub Pages**  - Simple and free hosting for static websites

## Getting Started

### 1 Clone the Repository
```sh
 git clone https://github.com/yourusername/your-repo.git
 cd your-repo
```

### 2 Install Dependencies
```sh
 npm install
```

### 3 Start Development Server
```sh
 npm run dev
```
Then, open [http://localhost:5173](http://localhost:5173) in your browser.

## Deploying to GitHub Pages

To deploy your **Vite React** project on GitHub Pages, follow these steps:

1. Install the GitHub Pages package:
   ```sh
   npm install gh-pages --save-dev
   ```
2. Add the following scripts to your `package.json`:
   ```json
   "scripts": {
     "build": "vite build",
     "deploy": "gh-pages -d dist"
   }
   ```
3. Run the following command to deploy:
   ```sh
   npm run build && npm run deploy
   ```

