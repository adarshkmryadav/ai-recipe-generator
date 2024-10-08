# Generative AI Recipe Application

## Overview
This application is a serverless web app built using **AWS Amplify** and powered by **Amazon Bedrock** with the **Claude 3 Sonnet foundation model**. Users can input ingredients, and the app generates recipes based on those inputs. The architecture consists of a user-friendly HTML frontend and a serverless backend to handle AI-generated recipe requests.

## Features
- **Serverless**: Built using AWS Amplify for frontend hosting and AWS Lambda for backend logic.
- **AI-Powered**: Recipes generated using Amazon Bedrock's Claude 3 Sonnet foundation model.
- **Integrated Frontend and Backend**: Communication via AWS AppSync and Amplify Data.

## Architecture
- **Frontend**: Hosted on AWS Amplify with continuous deployment from GitHub.
- **Backend**: AWS Lambda for serverless functions, with API built using AWS AppSync.
- **AI Model**: Amazon Bedrock foundation model for recipe generation.
- **Authentication**: Managed with AWS Cognito.

## Prerequisites
To use or modify this project, you'll need:
- **AWS account** (with administrator-level access).
- **Node.js** and **npm** installed locally.
- **GitHub account**.
- **AWS CLI** configured.

## Getting Started
Follow the official AWS deployment documentation to clone, configure, and deploy the app:
[Build a Serverless Web Application Using AWS Amplify, Lambda, Amazon Bedrock, and Cognito](https://aws.amazon.com/getting-started/hands-on/build-serverless-web-app-lambda-amplify-bedrock-cognito-gen-ai/)

This guide includes:
1. **Setting up the frontend** with AWS Amplify.
2. **Configuring authentication** with AWS Cognito.
3. **Deploying the backend** with AWS Lambda and AppSync.
4. **Connecting the frontend to the backend**.

## Clean Up
To remove resources created during deployment, refer to the clean-up instructions in the [AWS tutorial](https://aws.amazon.com/getting-started/hands-on/build-serverless-web-app-lambda-amplify-bedrock-cognito-gen-ai/).

## Conclusion
This project demonstrates how to create a serverless web application using AWS services and generative AI. Feel free to explore, modify, and contribute to the application. Happy coding!

---
