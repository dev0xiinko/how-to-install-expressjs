# How to Install Express.js

Follow these steps to install Express.js in your Node.js project:

## 1. Initialize a Node.js project

``` bash
npm init -y
```

## 2. Install Express.js

``` bash
npm install express
```

## 3. Create a basic server (optional)

Create a file named `index.js`:

``` javascript
const express = require('express');
const app = express();
const PORT = 3000;

app.get('/', (req, res) => {
  res.send('Hello from Express!');
});

app.listen(PORT, () => {
  console.log(`Server running on port ${PORT}`);
});
```

## 4. Run the server

``` bash
node index.js
```

## Done!

You have successfully installed Express.js.
