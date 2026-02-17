Employees Server

## Description

This is a simple API to solve the first challenge of the class microservices with nodejs and express.

## Endpoints

```bash
GET http://localhost:3000/employees
POST http://localhost:3000/employees
GET http://localhost:3000/employees/:id
```

## Docker setup and execution

```bash
docker build -t employees-server .
docker run -p 3000:3000 --name employees-server -d employees-server
```
