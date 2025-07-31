# AMCPRO
// package.json
{
  "name": "amcpro",
  "version": "0.1.0",
  "private": true,
  "dependencies": {
  "react": "^18.2.0",
  "react-dom": "^18.2.0",
  "react-scripts": "5.0.1"
}
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test",
    "eject": "react-scripts eject"
  }
}

// index.html (place inside public/index.html)
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>AMC PRO</title>
  </head>
  <body>
    <div id="root"></div>
  </body>
</html>

// src/index.js
import React from 'react';
import ReactDOM from 'react-dom/client';
import App from './App';

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(
  <React.StrictMode>
    <App />
  </React.StrictMode>
);

// src/App.js
import React from 'react';

function App() {
  return (
    <div style={{ textAlign: 'center', marginTop: '50px' }}>
      <h1>Welcome to AMC PRO</h1>
      <p>Your app is deployed successfully!</p>
    </div>
  );
}

export default App;

// .gitignore
node_modules
build
.env
.DS_Store
