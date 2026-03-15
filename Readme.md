# Go Gin Task Manager API v1

The first complete Task Manager REST API iteration in Go/Gin, implementing core task CRUD flows and service routing fundamentals.

## Phase Position

- **A2SV Go Phase:** Task 4
- **Previous Project:** `go-gin-web-service-basics`
- **Next Project:** `go-gin-task-manager-api-v2`

## Features

- RESTful CRUD endpoints for task resources

## Tech Stack

- Go
- Gin

## Project Structure

```text
.
├── main.go
├── go.mod
├── go.sum
└── Readme.md
```

## Run

```bash
go mod tidy
go run main.go
```

## Endpoints

- `GET /tasks`
- `GET /tasks/:id`
- `POST /tasks`
- `PUT /tasks/:id`
- `DELETE /tasks/:id`

## Learning Outcomes

- Resource-based API design
- Request validation and response shaping
- HTTP status code and payload conventions
