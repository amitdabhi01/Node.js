# 🌐 Custom HTTP Server Using Node.js

A simple custom HTTP server built using Node.js core `http` module. This project demonstrates how to create and run a basic server without using any external frameworks like Express.

---

## 📌 Features

* Uses Node.js built-in `http` module
* Lightweight and fast
* No external dependencies
* Returns a simple response
* Beginner-friendly project

---

## 📁 Project Structure

```
PR-CREATE-CUSTOM-SERVER-USING-HTTP/
│
├── node_modules/
├── app.js
├── package.json
└── package-lock.json
```

---

## ⚙️ Prerequisites

Make sure you have the following installed:

* Node.js (v14 or higher)
* npm (comes with Node.js)

Check versions:

```bash
node -v
npm -v
```

---

## 🚀 Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
```

2. Navigate to project folder:

```bash
cd PR-CREATE-CUSTOM-SERVER-USING-HTTP
```

3. Install dependencies:

```bash
npm install
```

---

## ▶️ Run the Server

Start the server using:

```bash
node app.js
```

If successful, you will see:

```bash
Server is listening on port 3001
```

---

## 🌍 Access in Browser

Open your browser and go to:

```
http://localhost:3001
```

You will see:

```
Hello from node-1
```

---

## 📄 app.js Code

```js
import http from "http";

const server = http.createServer((req, res) => {
  res.end("Hello from node-1");
});

const port = 3001;

server.listen(port, (err) => {
  if (err) {
    console.log(err);
    return;
  } else {
    console.log("Server is listening on port", port);
  }
});
```

---

## 🛠️ Technologies Used

* Node.js
* JavaScript (ES Modules)
* HTTP Module

---

## 📈 Future Improvements

* Add routing support
* Handle different HTTP methods
* Add Express framework
* Environment variables
* Error handling middleware

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Amit Dabhi**

* GitHub: [https://github.com/your-username](https://github.com/your-username)

---

⭐ If you like this project, don’t forget to star the repository!
