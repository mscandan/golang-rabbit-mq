# Golang RabbitMQ Example Project

## About the project

Example usage of RabbitMQ with Golang, both includes consumer and publisher part.

### API docs

- Consumer
  - Will fill later
- Publisher
  - Will fill later

## Getting started

- You need to have docker & docker-compose installed on your system

### Layout

```tree
├── README.md
├── consumer
│   ├── Dockerfile
│   ├── go.mod
│   └── main.go
├── docker-compose.yml
├── go.work
├── publisher
│   ├── Dockerfile
│   ├── go.mod
│   └── main.go
└── rabbit-mq
    └── rabbitmq.conf
```

A brief description of the layout:

- `.gitignore` varies per project, but all projects need to ignore `bin` directory.
- `README.md` is a detailed description of the project.
- `x/Dockerfile` specifies the build for apps to containers
- `docker-compose.yml` builds and runs all containers
