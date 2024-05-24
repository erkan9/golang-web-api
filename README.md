**Book API**

This is a simple Web API for Books implemented in Golang. It provides RESTful endpoints for CRUD operations on book resources.

### Features

- **Create, Read, Update, Delete (CRUD)**: Perform basic CRUD operations on book resources.

### Usage

- **Get All Books**: `GET /api/books`
- **Get a Single Book**: `GET /api/books/{id}`
- **Create a Book**: `POST /api/books`
- **Update a Book**: `PUT /api/books/{id}`
- **Delete a Book**: `DELETE /api/books/{id}`

### Technologies Used

- **Golang**: Backend implementation.
- **Gorilla Mux**: Routing and HTTP request handling.
- **UUID**: Generating unique identifiers.

### How to Run

1. Ensure Go v1.22.2 is installed.
2. Clone the repository.
3. Navigate to the project directory.
4. Run `go mod download` to install dependencies.
5. Run `go run main.go` to start the server.
