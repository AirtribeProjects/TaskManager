# Task Manager API

This is a RESTful API for managing tasks, built using Node.js and Express.js. It allows users to perform CRUD operations (Create, Read, Update, Delete) on tasks.

## Features

- **Create tasks:** Add new tasks with a title, description, and completion status.
- **Retrieve tasks:** Get a list of all tasks or retrieve a specific task by its ID.
- **Update tasks:** Update the details or completion status of an existing task.
- **Delete tasks:** Remove a task from the list.

## Installation

1. Clone the repository:

git clone  https://github.com/AirtribeProjects/TaskManager.git

2. Navigate to the project directory:

cd TaskManager

3. Install dependencies:

npm install express


## Usage

1. Start the server:

node app.js

2. Use Postman or any HTTP client to interact with the API.

## Endpoints

- **Retrieve all tasks:** `GET /tasks`
- **Retrieve a task by ID:** `GET /tasks/:id`
- **Create a new task:** `POST /tasks`
- **Update a task by ID:** `PUT /tasks/:id`
- **Delete a task by ID:** `DELETE /tasks/:id`

## Query Parameters

- Use the `completed` query parameter to filter tasks by completion status:
  - `GET /tasks?completed=true` - Retrieve all completed tasks.
  - `GET /tasks?completed=false` - Retrieve all incomplete tasks.
  
## Error Handling

- Proper error handling is implemented for invalid requests.
- Input validation is performed for task creation and updates.










