
title: Blogs


# Developer Blog

## [AWS Nordics Office Hours - Simplifying serverless best practices with AWS Lambda Powertools](https://youtu.be/jFefW_WiXso){target=_blank}

<iframe width="560" height="315" src="https://www.youtube.com/embed/jFefW_WiXso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## [Create an HTTP API endpoint that calls a Lambda function to RDS Proxy](https://serverlessland.com/patterns/apigw-http-api-lambda-rds-proxy){target=_blank}

Sets up an API Gateway HTTP API endpoint with an AWS Lambda function as an integration. The Lambda function integrates with RDS Proxy to query the RDS Aurora (MySQL) relational database.

## [Packaging and deploying AWS Lambda functions written in Java with AWS Cloud Development Kit](https://aws.amazon.com/blogs/opensource/packaging-and-deploying-aws-lambda-functions-written-in-java-with-aws-cloud-development-kit/){target=_blank}

Many Java applications use Apache Maven or Gradle for building and managing the project. These tools help map how to build a particular piece of software, along with its different dependencies. In almost every scenario, these applications will depend on several external dependencies/libraries. AWS Lambda functions written in Java also use these tools for packaging software.

In this article, we’ll show how to build and package Lambda functions written in Java with external dependencies via AWS CDK.


## [Automating mutual TLS setup for Amazon API Gateway](https://aws.amazon.com/blogs/compute/automating-mutual-tls-setup-for-amazon-api-gateway/){target=_blank}

In September 2020, Amazon API Gateway announced support for mutual Transport Layer Security (TLS) authentication. This 
is a new method for client-to-server authentication that can be used with API Gateway’s existing authorization options. 
Mutual TLS (mTLS) is an extension of Transport Layer Security(TLS), requiring both the server and client to verify each other.

This post covers automating the mTLS setup for API Gateway HTTP APIs

## [Simplifying serverless best practices with AWS Lambda Powertools Java](https://aws.amazon.com/blogs/opensource/simplifying-serverless-best-practices-with-aws-lambda-powertools-java/){target=_blank}

Modern applications are increasingly relying on compute platforms based on serverless technologies to provide 
scalability, cost efficiency, and agility. Distributed architectures have unlocked many benefits, and they have introduced
new complexities in how the applications operate. With traditional architectures, debugging was as straightforward as 
logging into the server and inspecting the logs. Modern observability must respond to the complexity of microservices 
architectures, the increased frequency of software deployments, and the short-lived nature of AWS Lambda execution environments.

This post shows capabilities of Lambda Powertools Java. It comes with a set of community-built utilities, in addition to the previously mentioned core utilities.

## [Shipshape Shipping Guide](https://developer.bring.com/blog/ship-shape/){target=_blank}

Shipping Guide is one of our oldest applications. As part of a large internal project we knew we were going to do quite a few changes to it. 
The project was born on the 26th of September 2008. Since then 91 people have worked on the project, contributing 17863 commits to the master branch.
Our team had little experience with the project and making large changes across the codebase seemed like a daunting task.

In this post I walk you through how we modernized a legacy application.

## [Alerting in grafana](https://developer.bring.com/blog/alerting-in-grafana/){target=_blank}

As mentioned in our previous blog, We at bring, use influx and grafana extensively, as one of the monitoring tools to 
collect statistics and visualize different aspects of application's performance.

We have been quite excited with the latest version of grafana, which now provides alerting engine, which we can set up 
alert rules on the statistics that we collect all over.
