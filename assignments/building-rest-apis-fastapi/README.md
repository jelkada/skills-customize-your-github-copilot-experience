# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a small REST API with FastAPI to practice defining routes, handling JSON data, validating requests, and returning appropriate HTTP responses.

## 📝 Tasks

### 🛠️ Create a FastAPI Application

#### Description

Create a FastAPI application that can be run locally with Uvicorn. Add a root endpoint that confirms the API is running.

#### Requirements

Completed program should:

- Create a FastAPI application instance.
- Run the application locally with Uvicorn.
- Define a `GET /` route.
- Return a JSON response that identifies the application as a working API.

### 🛠️ Add an Items Endpoint

#### Description

Create an endpoint that returns a collection of items stored in memory. Each item should include an identifier, name, and description.

#### Requirements

Completed program should:

- Store at least three items in an in-memory list or dictionary.
- Define a `GET /items` route that returns all items as JSON.
- Define a `GET /items/{item_id}` route that returns one item by its identifier.
- Return a `404 Not Found` response when the requested item does not exist.

### 🛠️ Create and Update Items

#### Description

Add routes that allow API clients to create new items and update existing items using JSON request bodies.

#### Requirements

Completed program should:

- Define a `POST /items` route that accepts a new item.
- Return the created item with its assigned identifier.
- Define a `PUT /items/{item_id}` route that updates an existing item.
- Return a `404 Not Found` response when an update targets a missing item.

### 🛠️ Validate Requests and Test the API

#### Description

Use Pydantic models to validate incoming data and test the API through FastAPI's interactive documentation.

#### Requirements

Completed program should:

- Define a Pydantic model for item data.
- Require a non-empty item name and a description in the request body.
- Return a validation error when a request body is missing required or invalid data.
- Verify each route using the interactive documentation at `/docs`.
- Include example requests and responses in the project README or submission notes.
