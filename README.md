# AWS Server Deployment and Containerization Test

Following steps were involved:

- Writing a Dockerfile for a simple Flask API
- Building and test the container locally
- Creating an EKS cluster
- Creating necessary roles and policies for the process
- Storing a secret using AWS Parameter Store
- Creating a CodePipeline pipeline triggered by GitHub checkins
- Creating a CodeBuild stage which will build, test, and deploy your code