# Movie Management API

A simple RESTful API for managing a collection of movies using Go and the Gorilla Mux router.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Usage](#usage)
- [Endpoints](#endpoints)
- [Installation](#installation)
- [Contributing](#contributing)

## Overview

This project provides a basic API for managing movie data. It allows you to perform CRUD (Create, Read, Update, Delete) operations on a list of movies stored in memory. It's a great starting point for learning Go and building RESTful APIs.

## Features

- Create, read, update, and delete movies.
- Retrieve a list of all movies or a single movie by ID.
- Simple in-memory storage for movie data.
- JSON-based communication for easy integration with front-end applications.

## Usage

1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/movie-management-api.git](https://github.com/samriddha-basu-cloud/Movie-Detail-Fetch-using-Go.git)
   ```

2. Navigate to the project directory:
   ```bash
   cd Movie-Detail-Fetch-using-Go
   ```

3. Run the application:
   ```bash
   go run main.go


4. The API is now running on http://localhost:8000.

## Endpoints

- **GET /movies**: Retrieve a list of all movies.
- **GET /movies/{id}**: Retrieve a single movie by ID.
- **POST /movies**: Create a new movie.
- **PUT /movies/{id}**: Update an existing movie.
- **DELETE /movies/{id}**: Delete a movie by ID.

## Installation

1. Install Go: [Official Go Installation Guide](https://golang.org/doc/install)

2. Clone this repository and navigate to the project directory.

3. Install dependencies:
   ```bash
   go get -u github.com/gorilla/mux
   ```

4. Run the application:
   ```bash
   go run main.go
   ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
