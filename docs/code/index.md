---
title: Open Source Projects
hide:
- navigation
---

# Open Source Projects

## [:material-github: Azure/bicep-registry-modules](https://github.com/Azure/bicep-registry-modules){target=_blank}

This repo contains the source code of all currently available Bicep modules in the Bicep public module registry (i.e., all AVM Bicep modules).

To provide our customers with a unified experience, Azure Verified Modules (AVM) is now the single Microsoft standard for Bicep modules, published to the Public Bicep Registry, via this repository.

## [:material-github: Azure/aca-landing-zone-accelerator](https://github.com/Azure/aca-landing-zone-accelerator){target=_blank}

Azure landing zone accelerators provide architectural guidance, reference architectures, reference implementations, and automation to deploy workload platforms on Azure at scale. They are aligned with industry proven practices, such as those presented in Azure landing zones guidance in the Cloud Adoption Framework.

This Azure Container Apps landing zone accelerator represents the strategic design path and target technical state for an Azure Container Apps deployment, owned and operated by an workload team.

This repository provides packaged guidance for customer scenarios, reference architecture, reference implementation, tooling, design area guidance, sample application deployed after provisioning the infrastructure using the accelerator. The architectural approach can be used as design guidance for greenfield implementation and as an assessment for brownfield customers already using containerized apps.


## [:material-github: Azure-Samples/serverless-webapp-kotlin](https://github.com/Azure-Samples/serverless-webapp-kotlin){target=_blank}

Use Azure Serverless stack to build a full-fledged web application with both backend and frontend hosted inside a same mono repo.

CI/CD pipeline is implemented using [GitHub actions](.github/workflows) for both backend and frontend app including related serverless cloud infrastructure for  backend and frontend. Infrastructure as code(IAC) for both frontend and backend infra is written using [Bicep](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/overview)

Application builds a React static web app, which talks to a bunch of APIs hosted via [Azure API Management](https://azure.microsoft.com/en-us/products/api-management/) and talking to azure functions written in kotlin, Azure storage and Azure Cosmo DB and Azure Cognitive services as backends. Feature of web application itself is simple. Since that is not the main purpose here. User can basically upload an image with a metadata. Then if user want, they can try uploading another image from another flow, and try to find face in it. If it's found in Cosmo DB, then we return the metadata.

## [:material-github: Azure/aca-dotnet-workshop](https://github.com/Azure/aca-dotnet-workshop){target=_blank}

This workshop, focusses on a containerization service offered by Microsoft Azure which is Azure Container Apps (ACA). Microsoft announced the public preview of Azure Container Apps back in Nov 2021 and in May 2022 it announced the General Availability of Azure Container Apps. In brief, Azure Container Apps is a fully managed serverless container runtime for building and running cloud-native applications which focuses on the business logic of the apps rather than on cloud infrastructure management.

## [:material-github: aws-samples/aws-appconfig-codepipeline-cdk](https://github.com/aws-samples/aws-appconfig-codepipeline-cdk){target=_blank}

This sample application demos setup of [AWS AppConfig](https://docs.aws.amazon.com/appconfig/latest/userguide/what-is-appconfig.html) using [AWS CDK](https://aws.amazon.com/cdk/). AWS AppConfig application is 
set up to use [AWS CodePipeline](https://aws.amazon.com/codepipeline/) as [configuration store](https://docs.aws.amazon.com/appconfig/latest/userguide/appconfig-creating-configuration-and-profile.html). It also sets up [AWS Lambda validator](https://docs.aws.amazon.com/appconfig/latest/userguide/appconfig-creating-configuration-and-profile-validators.html) to validate 
the configuration.

In addition, the project can set up a basic serverless api using [Amazon API Gateway](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-rest-api.html)
backed by [AWS Lambda](https://aws.amazon.com/lambda/) which makes use of [AWS AppConfig Lambda extension](https://docs.aws.amazon.com/appconfig/latest/userguide/appconfig-integration-lambda-extensions.html) to query hosted configuration.

[Kotlin](https://kotlinlang.org/) is used as language runtime to set up both the cdk application and needed lambda functions.


## [:material-github: aws-lambda-powertools-java](https://github.com/awslabs/aws-lambda-powertools-java){target=_blank}

Powertools is a suite of utilities for AWS Lambda Functions that makes tracing with AWS X-Ray, structured logging and 
creating custom metrics asynchronously easier.


## [:material-github: aws-samples/serverless-rds-proxy-demo](https://github.com/aws-samples/serverless-rds-proxy-demo){target=_blank}

This project demos benefits of using RDS proxy with serverless workload which depends on relational database like RDS Aurora. Project shows end to end automated setup of RDS Aurora(Mysql) with RDS proxy. Basic serverless architecture is set up using API gateway HTTP API and Lambda Functions.

Project sets up two endpoints with HTTP API, one which talks directly to RDS Aurora cluster and the other which talks via RDS Proxy. It provides load testing setup to measure the benefits of using RDS proxy in terms of connection pooling and elasticity.


## [:material-github: aws-samples/ecs-windows-ci-cd-blue-green](https://github.com/aws-samples/ecs-windows-ci-cd-blue-green){target=_blank}

This project sets up a Windows based ECS Cluster using [capacity provider auto-scaling](https://aws.amazon.com/blogs/containers/deep-dive-on-amazon-ecs-cluster-auto-scaling/) with fully automated Blue/Green deployment powered by AWS Code Deploy. All you
need to pass is your ECR repo name where the image resides in [cdk.json](cdk.json) via `imageRepository` property.

## [:material-github: cookiecutter-aws-sam-powertools-java](https://github.com/aws-samples/cookiecutter-aws-sam-powertools-java){target=_blank}

This is a [Cookiecutter](https://github.com/cookiecutter/cookiecutter) template to create a Serverless App based on Serverless Application Model (SAM) and Java with [Lambda Powertools Java](https://github.com/awslabs/aws-lambda-powertools-java).


## [:material-github: aws-samples/serverless-webapp-mono-repo-ci-cd-java](https://github.com/aws-samples/serverless-webapp-mono-repo-ci-cd-java){target=_blank}

Use AWS Serverless stack to build a full fledged web application with both backend and frontend hosted inside a same 
mono repo. Backend CI/CD pipeline and backend infrastructure is written using SAM. Frontend CI/CD pipeline and 
infrastructure is written using CDK Java.

Application builds a React static web app, which talks to a bunch of APIs hosted via API gateway and talking to lambda 
functions, S3 and dynamoDB as backends. Feature of web application itself is simple. Since that is not the main purpose 
here. User can basically upload an image with a metadata. Then if user want, they can try uploading another image from 
another flow, and try to find face in it. If it's found in Dynamo DB, then we return the metadata.

## [:material-github: aws-samples/api-gateway-auth](https://github.com/aws-samples/api-gateway-auth/){target=_blank}

This sample application showcases how to set up and automate different types of authentication supported by 
Amazon API Gateway HTTP API via AWS SAM.

This SAM app uses java as language runtime for the lambda functions and custom resources.

## [:material-github: aws-samples/cdk-lambda-packaging-java](https://github.com/aws-samples/cdk-lambda-packaging-java){target=_blank}

This sample application show how you can use [AWS Cloud Development Kit(AWS CDK)](https://aws.amazon.com/cdk/) to deploy a AWS lambda functions with 
external dependencies. [AWS Serverless Application Model (AWS SAM)](https://aws.amazon.com/serverless/sam/) takes care of building and packaging lambda function 
with external dependencies out of the box. It was not possible this with AWS CDK until [s3-assets](https://mvnrepository.com/artifact/software.amazon.awscdk/s3-assets) 
was introduced.

## [:material-github: pankajagrawal16/aws-ag-client](https://github.com/pankajagrawal16/aws-ag-client){target=_blank}

This Java repo demonstrates how to make IAM authenticated call to AWS api gateway endpoint. It is set up as a maven 
project currently and uses the AWS java SDK under the hood to provide simple wrapper classes to make these calls.



