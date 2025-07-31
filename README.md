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

/* File: package.json */
{
  "name": "amcpro-demo",
  "version": "1.0.0",
  "private": true,
  "dependencies": {
    "react": "^17.0.2",
    "react-dom": "^17.0.2",
    "react-scripts": "4.0.3"
  },
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test",
    "eject": "react-scripts eject"
  }
}

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
