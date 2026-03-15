# Go Gin Task Manager API v1

The first complete Task Manager REST API iteration in Go/Gin, implementing core task CRUD flows and service routing fundamentals.

## Phase Position

- **A2SV Go Phase:** Task 4
- **Previous Project:** `go-gin-web-service-basics`
- **Next Project:** `go-gin-task-manager-api-v2`

## Features

- RESTful CRUD endpoints for task resources
- Basic routing, controllers, and model organization
- API documentation scaffold in `docs/`

## Tech Stack

- Go
- Gin

## Project Structure

```text
.
├── Readme.md
├── go.mod
├── go.sum
└── main.go
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
- Controller-routing composition
- Request validation and response shaping
