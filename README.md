# 🎓 Students Management REST API - GO

A lightweight RESTful backend application built with **Go (Golang)** and **SQLite** for managing student records.

## 🚀 Features

- ⚡ RESTful APIs using Go's standard `net/http` package
- 🗄️ SQLite database integration for persistent storage
- 📝 Create, retrieve and list student records
- ⚙️ Configuration management
- 📊 Structured logging with `log/slog`
- 🛑 Graceful server shutdown using OS signals and context timeouts

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Go | Backend development |
| net/http | HTTP server and routing |
| SQLite | Database |
| log/slog | Structured logging |
| Context | Graceful shutdown |

## 📡 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| POST | `/api/students` | Create a student |
| GET | `/api/students` | Retrieve all students |
| GET | `/api/students/{id}` | Retrieve a student by ID |

## ⚙️ Getting Started

**1. Clone the repository**

```bash
git clone <your-repository-url>
cd students-api
```

**2. Install dependencies**

```bash
go mod tidy
```

**3. Configure environment variables**

Set up the configuration required by the application.

**4. Run the application**

```bash
go run cmd/students-api/main.go
```

## 📁 Project Structure

```text
students-api/
├── cmd/
│   └── students-api/
│       └── main.go
├── internal/
│   ├── config/
│   ├── http/
│   │   └── handlers/
│   │       └── student/
│   └── storage/
│       └── sqlite/
├── go.mod
└── go.sum
```

## 🎯 Key Learning Outcomes

- Building RESTful services with Go
- Organising backend applications using modular architecture
- Integrating relational databases
- Implementing structured logging and configuration
- Managing application lifecycle and graceful shutdown

---

**Built with ❤️ using Go.**
