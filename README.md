# AMCPRO
/* File: public/style.css */
body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
  background-color: #f5f5f5;
}

header {
  background-color: #0d47a1;
  padding: 20px;
  color: white;
  text-align: center;
  font-size: 24px;
}

/* File: src/components/Header.js */
import React from 'react';

const Header = () => {
  return (
    <header>
      AMCPRO
    </header>
  );
};

export default Header;

/* File: src/index.js */
import React from 'react';
import ReactDOM from 'react-dom';
import Header from './components/Header';
import '../public/style.css';

const App = () => {
  return (
    <div>
      <Header />
      <h2 style={{ textAlign: 'center' }}>Welcome to AMCPRO Demo Website</h2>
    </div>
  );
};

ReactDOM.render(<App />, document.getElementById('root'));

{
  "name": "amcpro",
  "version": "0.1.0",
  "lockfileVersion": 2,
  "requires": true,
  "packages": {
    "": {
      "name": "amcpro",
      "version": "0.1.0",
      "dependencies": {
        "react": "^18.2.0",
        "react-dom": "^18.2.0",
        "react-scripts": "5.0.1"
      }
    },
    "node_modules/react": {
      "version": "18.2.0",
      "resolved": "https://registry.npmjs.org/react/-/react-18.2.0.tgz",
      "integrity": "sha512-6pGpU9b6c3cBxhsA6bV7LF6qKqk8IsWEHqY9kRleXvWfF/1NYhguWCI7hPBnB7/W3z4Ckqh3U66SkorqKHcLpw==",
      "dependencies": {
        "loose-envify": "^1.1.0"
      }
    },
    "node_modules/react-dom": {
      "version": "18.2.0",
      "resolved": "https://registry.npmjs.org/react-dom/-/react-dom-18.2.0.tgz",
      "integrity": "sha512-tO6lAAX8jtCRFfK0fPTuTst6f/0YML2+SLYUNNQjC9GmJSyGyI7UIfzmh8lA+5EAXDC7vYqN73E4qWrDhH+UMA==",
      "dependencies": {
        "react": "^18.2.0"
      }
    },
    "node_modules/react-scripts": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/react-scripts/-/react-scripts-5.0.1.tgz",
      "integrity": "sha512-rv9Z0u6wvlG9H9v9zGqReuR5ht3zG7kZKBS8slO0OiDqFqIhNlKf3FPWvGO1+YFhQ8dYULPTZcoJgI2KfI9/AQ=="
    },
    "node_modules/loose-envify": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/loose-envify/-/loose-envify-1.4.0.tgz",
      "integrity": "sha51

/* File: public/index.html */
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AMCPRO</title>
</head>
<body>
  <div id="root"></div>
</body>
</html>
