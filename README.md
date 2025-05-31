# 🗂️ Simple Go File Server

A beginner-friendly web server built with Go that demonstrates basic routing, HTML serving, and form handling using Go’s `net/http` package.

---

## 📌 Features

- `/` — Serves a styled homepage (`index.html`)
- `/hello` — Returns a greeting from the Go backend
- `/form` — Serves a contact form with `name` and `address` fields
- `/submit` — Handles form submission via POST request

---

## 📁 Project Structure

go-fileserver/
│
├── static/
│   ├── index.html
│   └── form.html
│
├── main.go
└── go.mod

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/go-fileserver.git
cd go-fileserver

2. Run the server

go run main.go

3. Open in your browser
	•	http://localhost:8080/ — Homepage
	•	http://localhost:8080/hello — Hello route
	•	http://localhost:8080/form — Form page

⸻

🧠 Concepts Covered
	•	Go’s net/http package
	•	Serving static HTML and CSS
	•	Basic form submission handling
	•	HTML layout and embedded CSS

⸻

📦 Requirements
	•	Go 1.18 or higher

⸻

📄 License

MIT License — free to use and modify.

⸻

✍️ Author

Vaibhav Gautam
(https://www.linkedin.com/in/vaibhav-gautam-a79418234/)
vaibhavgautam1707@gmail.com
https://go-server-9d44.onrender.com

