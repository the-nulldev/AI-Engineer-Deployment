## Task One — API Endpoint (tasks/task1.md)

### Description

Usually, we want to integrate AI capabilities into our existing applications. The frontend team has already created the UI:

![Smartphone Store UI](./images/smartphones-ui.png)

Also, the backend team has implemented the rest of the application logic allowing users to create accounts, order for smartphones, and other capabilities. Now, they're collaborating with you, the AI team, to integrate an Ai-powered assistant to help users choose the best smartphone.

What you've been building is a microservice in a larger web application. It is completely decoupled from the main app, and they communicate with each other only via APIs. Therefore, we need to implement an API endpoint that the application can send requests to. When a user asks a question, a POST request is sent to the endpoint with the user’s query, user ID, and session ID. Once the response is generated, it will be displayed to the user in the frontend UI.

Your task is to use FastAPI to implement the API endpoint. The application should remain the same (monitoring, evaluations, guardrails, and budgets remain unchanged), but instead of sending queries from the CLI, the application should run as a web service that we can send requests to and receive responses.

Another thing to note is that some aspects of the application will no longer be required, while some need a different setup. You'll need to remove them and also modify some aspects of the application. For example, you don't need the EndSession tool anymore. You can remove that as well as generation of goodbye messages. Also, ensure you're building the vector store when the smartphones info tool is called.

### Objectives

- Use FastAPI to implement an endpoint, `/ask` which, when a request is made, it returns the AI response.
- The JSON payload should contain the user’s query, the user’s name, and session ID.
- A JSON response should be returned from the server.
- Use Pydantic to validate the request schema.
- Remove the `EndSession` tool.
- Any other necessary modifications.

### Deliverable

In this task, your application should run as a web service that can accept POST requests and return responses containing the LLM's recommendations. Therefore, your repo should contain the updated code that adds this functionality.

### Topics

### Docs

### Other useful articles