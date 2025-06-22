## Task Two: Deployment with Docker (tasks/task2.md)

### Description

As you know, deploying apps via Docker ensures that they can consistently run in any environment. This avoids the age-old issue, “it works on my machine”. With Docker, both your local environment and the production environment will be consistent. Once you've containerized your app, you can run it in any environment of your choice. In this stage, let's work on the Dockerfile.

### Objectives

In this task, you need to write a `Dockerfile` to containerize the application. Use a suitable base image, copy files, install requirements, and set the entrypoint. Then, run the container and ensure the `/ask` endpoint is accepting requests and responding as expected.

### Deliverables

As before, your app should run as a web service that can accept POST requests and return responses containing the LLM's recommendations. However, now it should run as a Docker container. Your repo should now contain a `Dockerfile` to containerize the application.

### Topics
Docs
Other useful articles