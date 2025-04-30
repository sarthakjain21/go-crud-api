# Go Movies CRUD API

A simple REST API for managing movie information, built with Go and Gorilla Mux.

## Overview

This project implements a basic CRUD (Create, Read, Update, Delete) API for movie data with the following features:
- In-memory data storage
- RESTful endpoint architecture
- JSON response format
- Simple movie and director data model

## Installation

### Prerequisites
- Go (version 1.16+ recommended)
- Git

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/sarthakjain21/go-crud-api.git
   cd go-crud-api
   ```

2. Install dependencies:
   ```bash
   go mod download
   ```

3. Run the application:
   ```bash
   go run main.go
   ```

The server will start on port 8080.

## API Endpoints

| Method | URL | Description |
|--------|-----|-------------|
| GET | /movies | Get all movies |
| GET | /movies/{id} | Get a specific movie by ID |
| POST | /movies | Create a new movie |
| PUT | /movies/{id} | Update a movie by ID |
| DELETE | /movies/{id} | Delete a movie by ID |



## Project Structure

This is a simple single-file application with all code in `main.go`:

- Data models (Movie, Director)
- API handler functions
- Router configuration
- In-memory data storage

## Technologies Used

- [Go](https://golang.org/) - Programming language
- [Gorilla Mux](https://github.com/gorilla/mux) - HTTP router and URL matcher
- Standard library packages:
  - encoding/json
  - net/http
  - math/rand
  - strconv
  - log
  - fmt