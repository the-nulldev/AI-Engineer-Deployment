# LLM-Evals: Deployment

- [Introduction](#-introduction)
- [Learning Outcomes](#-learning-outcomes)
- [Project Structure](#-project-structure)
- [Tasks](#-tasks)
    - [Task One - API Endpoint](#1-api-endpoint)
    - [Task Two - Dockerize the App](#2-dockerize-the-app)
    - [Task Three - Refactor to Cloud Services](#3-deploy-to-aws)
    - [Task Four - Deploy to AWS](#4-deploy-to-saas)
- [Deliverables](#-deliverables)
- [Useful Resources](#-useful-resources)
- [Contributing](#-contributing)

## Introduction
This is the starter repo for the LLM Evals: Deployment module. You can modify the structure, files, and everything else.
Note that this project continues from where you left off in LLM Evals: Let's Talk Money, after you added input rails. Now, we'll deploy the app so that everyone else can use it.

## Learning Outcomes

This module covers deploying LLM applications. You'll use tools and services like FastAPI, Docker, AWS, and SaaS providers to ship and share the app you've building.

## Project Structure
The project structure is designed to be modular and easy to navigate. Here's a brief overview of the main directories and files:

```llm-evals-deployment/
├── tasks/
│   ├── task_one_api_endpoint.md    
│   ├── task_two_dockerize_app.md
│   ├── task_three_refactor_cloud_services.md
│   └── task_four_deploy_to_aws.md
├── src/
│   ├── main.py
│   ├── api/
│   ├── services/
│   ├── models/
│   └── utils/
├── Dockerfile
├── requirements.txt
├── README.md
└── CONTRIBUTING.md
```
## Tasks
This project is divided into tasks that you need to complete. The tasks are located in the `tasks` folder of the repository. Each task consists of the objectives you need to accomplish, expected outcomes, and useful resources. Here's a brief overview of the tasks:
- **Task One - API Endpoint**: Create a FastAPI endpoint that accepts user input and returns a response from the LLM.
- **Task Two - Dockerize the App**: Containerize the FastAPI application using Docker to ensure it runs consistently across different environments.
- **Task Three - Refactor to Cloud Services**: Use SaaS providers for your vector store, Redis, and Langfuse instead of self-hosting them.
- **Task Four - Deploy to AWS**: Deploy the application to AWS using AWS Lambda and API Gateway, ensuring it is scalable and reliable.

## Useful Resources

Each task will contain a collection of resources that will be helpful for you as you solve the task. There are links to topics in Hyperskill, documentation, and other helpful tutorials that you and your team can use. You may not always need to use all of the provided resources if you're already familiar with the concepts.
In addition to the provided resources, you can always discuss with your teammates and experts. Various channels are available, such as GitHub Issues, GitHub Discussions, PRs, or Discord.

## Deliverables

To fully complete this assignment, you need to have completed all tasks. 

## Contributing

All discussions and bug reports must be done via GitHub Issues, while code review is done via GitHub Pull Requests. For more information, see the [CONTRIBUTING.md](./CONTRIBUTING.md) file.

