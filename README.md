# 🎬 Go Movie CRUD API

A simple RESTful API built in Go to manage a list of movies. It uses the Gorilla Mux router and supports basic CRUD (Create, Read, Update, Delete) operations.

---

## 📦 Features

- List all movies (`GET /movies`)
- Get a single movie by ID (`GET /movies/{id}`)
- Create a new movie (`POST /movies`)
- Update an existing movie (`PUT /movies/{id}`)
- Delete a movie (`DELETE /movies/{id}`)

---

## 🛠️ Tech Stack

- **Language**: Go (Golang)
- **Routing**: Gorilla Mux
- **Encoding/Decoding**: `encoding/json`