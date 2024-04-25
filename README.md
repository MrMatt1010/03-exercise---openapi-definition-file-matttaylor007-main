# 03 Exercise - OpenAPI Definition File

## Scenario

Your team is about to start working on a Todo application. As part of the API design process your Tech Lead has asked to you to describe in an OpenAPI file the Todo API's available endpoints (paths), each endpoint's operations (HTTP methods), and each operation's response statuses.

## Rationale

Get familiar documenting desired properties of an API, as a first step in the process of designing the API.

## Getting Started

1. Open a Terminal in VS Code for this project
2. Type `npm install` to install npm dependencies
3. `Type npm start` to start the Express Server
4. Open `http://localhost:5001/` in your browser to view the [Swagger UI](https://swagger.io/tools/swagger-ui/) generated API docs. (You need to restart the server after you update the `apispec.yaml` file.)

## Todo API Requirements

When designing the Todo API, keep in mind your users' needs. The user should be able to:

- add tasks ('todos') to keep track of things they need to do
- view their existing tasks
- edit tasks when the task description is not accurate
- delete tasks they do not need to do anymore
- indicate which tasks are done to keep track of tasks which are already done

## Instructions

Update the `apispec.yaml` file to include endpoints, operations and response statuses to create, read, update and delete todos.

- Think about the different endpoints your API would need to carry out the CRUD operations, which operations would be applicable to each endpoint (POST, GET, PATCH, DELETE), and which status codes would be applicable to each operation. Useful links: [Paths and Operations](https://swagger.io/docs/specification/paths-and-operations/), [HTTP Request Methods](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods), [HTTP response status codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status).
- The success response for the `/todos` GET request has already been added for you.
- Start by pasting the boilerplate code into Stoplight and use it to help you fill in the rest of your OpenAPI file and check for syntax problems. You can toggle between Stoplight's Code and Interface views as needed.
- You do not need to document any parameter details, request body content, response body content or schemas.

**Acceptance Criteria:**

- [ ] The `apispec.yaml` file includes the required paths (endpoints).
- [ ] The `apispec.yaml` file specifies the operations (HTTP methods) that can be used to access each path. The operations should include a description and operationId.
- [ ] The `apispec.yaml` file specifies the responses for all API operations. The responses should include a status code and description.
- [ ] Commits are pushed to GitHub
- [ ] Exercise has been submitted in Google Classroom
