---
url: /integrations/aws-api-gateway
title: Amazon API Gateway Tutorial Introduction
---

# Amazon API Gateway Tutorial

## Building a Serverless Application using Token-based Authentication with AWS API Gateway and Lambda

With AWS, you can create powerful, serverless, highly scalable APIs and applications through AWS Lambda, Amazon API Gateway, and a Javascript client. A serverless application runs custom code as a service without the need to maintain an operating the environment to host your service. Instead, a compute service like [AWS Lambda](https://aws.amazon.com/lambda/) or [webtask.io](https://webtask.io) executes your code on your behalf. Amazon API Gateway extends the capabilities of AWS Lambda by adding a service layer in front of your Lambda functions to extend security, manage input and output message transformations, and provide capabilities like throttling and auditing. A serverless approach simplifies your operational demands since concerns like scaling out and fault tolerance are now the responsibility of the compute service that is executing your code.

However, you often want to tie your APIs to existing users, either from social providers like Twitter and Facebook, or within your own organization from Active Directory or a customer database. This tutorial demonstrates how to authorize access of your Amazon API Gateway methods for your existing users using Auth0 delegation for AWS and integration with AWS Identity and Access Management (IAM). The tutorial walks setting up Amazon API Gateway using AWS Lambda functions, securing those functions with AWS IAM roles, and then using Auth0 delegation to obtain a token for the AWS IAM role. It will then show you how to assign different permissions to various classes of users, like internal database or social users, and how to flow identity using a JSON Web Token (JWT).

You will be taken through the following steps:

* [Step 1 - Setting up the AWS API Gateway](/integrations/aws-api-gateway/part-1)
* [Step 2 - Securing and Deploying the Amazon API Gateway](/integrations/aws-api-gateway/part-2)
* [Step 3 - Building the Client Application](/integrations/aws-api-gateway/part-3)
* [Step 4 - Using Multiple Roles with Amazon API Gateway](/integrations/aws-api-gateway/part-4)
* [Step 5 - Using Identity Tokens to Flow Identity](/integrations/aws-api-gateway/part-5)

  [Next](/integrations/aws-api-gateway/part-1)
