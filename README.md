# Kangacook Backend API

This repository contains the Django backend for the Kangacook project. The backend provides several API endpoints to manage tasks, including creating, updating, retrieving, and deleting tasks.

## API Endpoints

- `GET /api/todos/`: Retrieve a list of all tasks.
- `POST /api/todos/`: Create a new task.
- `PUT /api/todos/:id/`: Update an existing task by ID.
- `DELETE /api/todos/:id/`: Delete an existing task by ID.
- `GET /api/todos/:id/`: Retrieve details of a specific task by ID.
- `POST /api/register/`: Register a new user.
- `POST /api/token/`: Obtain a token for authentication.
- `POST /api/token/refresh/`: Refresh the authentication token.
- `POST /api/token/forget/`: Invalidate a refresh token (logout).

## Postman Collection

The Postman collection for testing the API is provided in this repository. You can import it into Postman to interact with the API endpoints.

### Collection Import Link:
[Postman Collection Import Link](https://restless-firefly-21235.postman.co/workspace/New-Team-Workspace~aad623ce-767d-4e1e-a51e-9190b784bced/collection/7024852-cc1dfa40-59fe-4f7b-b574-4f58e91fbdb4?action=share&creator=7024852)

### Collection JSON:
You can download the collection JSON file [here](kangacook_backend_API.postman_collection.json).

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd kangacook_backend
