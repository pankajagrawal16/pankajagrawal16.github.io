
title: Open Source Projects

# Open Source Projects

## [:material-github: ecs-windows-ci-cd-blue-green](https://github.com/aws-samples/ecs-windows-ci-cd-blue-green){target=_blank}

This project sets up a Windows based ECS Cluster using [capacity provider auto-scaling](https://aws.amazon.com/blogs/containers/deep-dive-on-amazon-ecs-cluster-auto-scaling/) with fully automated Blue/Green deployment powered by AWS Code Deploy. All you
need to pass is your ECR repo name where the image resides in [cdk.json](cdk.json) via `imageRepository` property.

## [:material-github: aws-lambda-powertools-java](https://github.com/awslabs/aws-lambda-powertools-java){target=_blank}

Powertools is a suite of utilities for AWS Lambda Functions that makes tracing with AWS X-Ray, structured logging and 
creating custom metrics asynchronously easier.

## [:material-github: serverless-webapp-mono-repo-ci-cd-java](https://github.com/aws-samples/serverless-webapp-mono-repo-ci-cd-java){target=_blank}

Use AWS Serverless stack to build a full fledged web application with both backend and frontend hosted inside a same 
mono repo. Backend CI/CD pipeline and backend infrastructure is written using SAM. Frontend CI/CD pipeline and 
infrastructure is written using CDK Java.

Application builds a React static web app, which talks to a bunch of APIs hosted via API gateway and talking to lambda 
functions, S3 and dynamoDB as backends. Feature of web application itself is simple. Since that is not the main purpose 
here. User can basically upload an image with a metadata. Then if user want, they can try uploading another image from 
another flow, and try to find face in it. If it's found in Dynamo DB, then we return the metadata.

## [:material-github: api-gateway-auth](https://github.com/aws-samples/api-gateway-auth/){target=_blank}

This sample application showcases how to set up and automate different types of authentication supported by 
Amazon API Gateway HTTP API via AWS SAM.

This SAM app uses java as language runtime for the lambda functions and custom resources.

## [:material-github: cdk-lambda-packaging-java](https://github.com/aws-samples/cdk-lambda-packaging-java){target=_blank}

This sample application show how you can use [AWS Cloud Development Kit(AWS CDK)](https://aws.amazon.com/cdk/) to deploy a AWS lambda functions with 
external dependencies. [AWS Serverless Application Model (AWS SAM)](https://aws.amazon.com/serverless/sam/) takes care of building and packaging lambda function 
with external dependencies out of the box. It was not possible this with AWS CDK until [s3-assets](https://mvnrepository.com/artifact/software.amazon.awscdk/s3-assets) 
was introduced.

## [:material-github: aws-ag-client](https://github.com/pankajagrawal16/aws-ag-client){target=_blank}

This Java repo demonstrates how to make IAM authenticated call to AWS api gateway endpoint. It is set up as a maven 
project currently and uses the AWS java SDK under the hood to provide simple wrapper classes to make these calls.



