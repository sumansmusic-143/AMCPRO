# AMCPRO
// ✅ DG's VITE + REACT FULL PROJECT STRUCTURE
// Clean and ready to deploy on Vercel

// 👉 Step 1: Create project using Vite
// Run this in your terminal (not inside any existing folder):

npm create vite@latest amcpro -- --template react

cd amcpro

npm install


// 👉 Step 2: Update package.json (optional if using TypeScript or Tailwind, let me know if needed)

{
  "name": "amcpro",
  "version": "0.0.0",
  "private": true,
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview"
  },
  "dependencies": {
    "react": "^18.2.0",
    "react-dom": "^18.2.0"
  },
  "devDependencies": {
    "@vitejs/plugin-react": "^4.0.0",
    "vite": "^4.0.0"
  }
}


// 👉 Step 3: vite.config.js

import { defineConfig } from 'vite';
import react from '@vitejs/plugin-react';

export default defineConfig({
  plugins: [react()],
});


// 👉 Step 4: Basic src structure
// src/main.jsx

import React from 'react';
import ReactDOM from 'react-dom/client';
import App from './App';
import './index.css';

ReactDOM.createRoot(document.getElementById('root')).render(
  <React.StrictMode>
    <App />
  </React.StrictMode>
);


// src/App.jsx

function App() {
  return (
    <div style={{ textAlign: 'center', padding: '40px' }}>
      <h1>Hello DG, Welcome to AMC PRO 🎬</h1>
      <p>This is a clean Vite + React app ready for Vercel Deployment!</p>
    </div>
  );
}

export default App;


// 👉 Step 5: src/index.css (optional styling)

body {
  margin: 0;
  font-family: sans-serif;
  background-color: #f0f0f0;
  color: #333;
}


// 👉 Step 6: Deploy to Vercel
1. Push to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Import project from GitHub
4. Vercel will auto-detect Vite and build it

✅ Done!
