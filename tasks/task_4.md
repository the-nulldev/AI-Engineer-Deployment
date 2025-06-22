## Final Deployment

### Description

In this final stage, you will publish your app to AWS. This will ensure that the rest of the web application for the site can send requests to it and receive a response. You will need to create an AWS free tier account to publish your app there.

You'll use a combination of AWS Lambda Amazon API Gateway. Lambda allows you to run the Docker container, while API Gateway allows you to create a REST API endpoint that will serve as the entry point to your backend services.
As part of the AWS free tier, you will be able to run the app for free.

### Objectives

Using AWS API Gateway, create a REST API endpoint that will trigger Lambda when a POST request is received. Next, create a Lambda function that will be triggered by the POST request and run the Docker container. The output will be the AI response returned by the web app.

### Deliverables
1. A REST API endpoint created using AWS API Gateway that triggers a Lambda function.
2. A Lambda function that runs the Docker container and returns the AI response.
3. The Lambda function should be able to handle the input from the API Gateway and return the output in a format that can be consumed by the web application.
4. The Lambda function should be able to run the Docker container and return the output of the AI response.

### Resources
- [AWS Lambda Documentation](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)
- [AWS API Gateway Documentation](https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html)
- [AWS Free Tier](https://aws.amazon.com/free/)
- [AWS Lambda with Docker](https://docs.aws.amazon.com/lambda/latest/dg/images-create.html)
- [AWS API Gateway with Lambda](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-integrate-with-lambda.html)
- [AWS Lambda Function Handler in Python](https://docs.aws.amazon.com/lambda/latest/dg/python-handler.html)

### Topics

### Docs

### Other useful articles