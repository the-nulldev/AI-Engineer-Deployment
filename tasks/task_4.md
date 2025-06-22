## Task Four — Final Deployment (tasks/task4.md)

### Description

In this final stage, you will publish your app to AWS. This will ensure that the rest of the web application for the site can send requests to it and receive a response. You will need to create an AWS free tier account to publish your app there.

To make it all possible, you'll use a combination of AWS Lambda Amazon API Gateway. Lambda allows you to publish the Docker container, while API Gateway allows you create a REST API endpoint that will serve as the entry point of your backend service.

### Objectives

Using AWS API Gateway, create a REST API endpoint that will trigger a Lambda backend when a POST request is received. Next, create a Lambda function that will be triggered by the POST request and run the Docker container. The output will be the AI response returned by the web app.

### Deliverables

At this point there are no code changes to push to GitHub. However, there should be an API endpoint that serves as the entrypoint to your application. Since API Gateway is free to use and AWS Lambda provides 1M executions free per month free forever, you can leave everything in place without worrying about costs (there won't be any).

### Topics

### Docs

### Other useful articles