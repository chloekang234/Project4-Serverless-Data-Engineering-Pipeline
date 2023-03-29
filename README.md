# Individual Project 4: Serverless Data Engineering Pipeline

## Objectvices of Project
This project reproduces the architecture of the example serverless data engineering project or perform something similar using only serverless technologies.
AWS lambda was used to have serverless application architecture.

## Progress

### week 1

AWS SAM (Serverless Application Model) is a framework for building serverless applications on AWS (Amazon Web Services). It is an open-source framework that extends AWS CloudFormation to provide a simplified way of defining the Amazon API Gateway APIs, AWS Lambda functions, and Amazon DynamoDB tables needed by your serverless application.

1. `sam init`
a command that initializes a new serverless application project by creating a sample template and directory structure.


2. `sam build --use-container`
a command to build a deployment package for a serverless application using a Docker container.
When you run this command, SAM will package and build your code, including all the dependencies and libraries required by your application, inside a Docker container that matches the AWS Lambda environment. This ensures that the deployment package is consistent and that any native dependencies are compiled correctly.

3. `sam validate`
a command that checks the syntax and semantics of the AWS SAM template and verifies that it is valid according to the AWS SAM specification. If the template is not valid, the command will return an error message indicating the issues with the template.

4. `sam local invoke`
 a command to invoke a Lambda function locally on your development machine. It allows you to test your Lambda function code locally and get immediate feedback on its behavior.

5. `sam local start-api`
a command that allows you to locally test and debug your serverless APIs using a local API Gateway.
When you run sam local start-api, it starts a local API Gateway and listens to HTTP requests on a specified port. It reads the template.yaml or template.yml file in the current directory to determine the API's configuration and which Lambda functions to invoke for each API endpoint.

6. `curl <address-you-get-from-previous-command>`# Individual Project 4: Serverless Data Engineering Pipeline

## Objectvices of Project
This project reproduces the architecture of the example serverless data engineering project or perform something similar using only serverless technologies.
AWS lambda was used to have serverless application architecture.

## Progress

### week 1

AWS SAM (Serverless Application Model) is a framework for building serverless applications on AWS (Amazon Web Services). It is an open-source framework that extends AWS CloudFormation to provide a simplified way of defining the Amazon API Gateway APIs, AWS Lambda functions, and Amazon DynamoDB tables needed by your serverless application.

1. `sam init`
a command that initializes a new serverless application project by creating a sample template and directory structure.


2. `sam build --use-container`
a command to build a deployment package for a serverless application using a Docker container.
When you run this command, SAM will package and build your code, including all the dependencies and libraries required by your application, inside a Docker container that matches the AWS Lambda environment. This ensures that the deployment package is consistent and that any native dependencies are compiled correctly.

3. `sam validate`
a command that checks the syntax and semantics of the AWS SAM template and verifies that it is valid according to the AWS SAM specification. If the template is not valid, the command will return an error message indicating the issues with the template.

4. `sam local invoke`
 a command to invoke a Lambda function locally on your development machine. It allows you to test your Lambda function code locally and get immediate feedback on its behavior.

5. `sam local start-api`
a command that allows you to locally test and debug your serverless APIs using a local API Gateway.
When you run sam local start-api, it starts a local API Gateway and listens to HTTP requests on a specified port. It reads the template.yaml or template.yml file in the current directory to determine the API's configuration and which Lambda functions to invoke for each API endpoint.

6. `curl <address-you-get-from-previous-command>`