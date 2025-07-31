# AMCPRO
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <link rel="icon" href="%PUBLIC_URL%/favicon.ico" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>AMCPRO</title>
  </head>
  <body>
    <noscript>You need to enable JavaScript to run this app.</noscript>
    <div id="root"></div>
  </body>
</html>
@tailwind base;
@tailwind components;
@tailwind utilities;

/* Optional: custom styles */
body {
  margin: 0;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
import React from "react";
import ReactDOM from "react-dom/client";
import "./index.css";

function App() {
  return (
    <div className="min-h-screen bg-gray-100 p-8 font-sans">
      <div className="max-w-4xl mx-auto bg-white shadow-xl rounded-2xl p-8">
        <h1 className="text-4xl font-bold text-center text-blue-600 mb-6">AMCPRO</h1>

        <div className="grid md:grid-cols-2 gap-6">
          <div className="bg-blue-50 rounded-xl p-6 shadow">
            <h2 className="text-xl font-semibold mb-2">📺 YouTube Growth</h2>
            <ul className="list-disc ml-5 text-gray-700">
              <li>Watch Hours Boost</li>
              <li>Likes, Comments & Subscribers</li>
            </ul>
          </div>

          <div className="bg-green-50 rounded-xl p-6 shadow">
            <h2 className="text-xl font-semibold mb-2">📱 Instagram Promotion</h2>
            <ul className="list-disc ml-5 text-gray-700">
              <li>Followers & Likes</li>
              <li>Reel Views</li>
            </ul>
          </div>

          <div className="bg-yellow-50 rounded-xl p-6 shadow">
            <h2 className="text-xl font-semibold mb-2">🌐 Website Traffic</h2>
            <ul className="list-disc ml-5 text-gray-700">
              <li>Real Visits</li>
              <li>Targeted Audience</li>
            </ul>
          </div>

          <div className="bg-red-50 rounded-xl p-6 shadow">
            <h2 className="text-xl font-semibold mb-2">⭐ Google Reviews</h2>
            <ul className="list-disc ml-5 text-gray-700">
              <li>Positive Ratings</li>
              <li>Business Boost</li>
            </ul>
          </div>

          <div className="bg-purple-50 rounded-xl p-6 shadow col-span-full">
            <h2 className="text-xl font-semibold mb-2">📲 App Installation</h2>
            <ul className="list-disc ml-5 text-gray-700">
              <li>Play Store Installs</li>
              <li>Real Android Users</li>
            </ul>
          </div>
        </div>

        <p className="text-center text-gray-500 mt-8">Your Digital Growth Partner 🚀</p>
      </div>
    </div>
  );
}

const root = ReactDOM.createRoot(document.getElementById("root"));
root.render(
  <React.StrictMode>
    <App />
  </React.StrictMode>
);
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{js,jsx,ts,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
module.exports = {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  },
};
