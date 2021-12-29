- 👋 Hi, I’m @BlacPanda420: Want to start an NFT that promotes Garbage recycling WOrld WIde for EAL coins
- 👀 I’m interested in: Making the World a Green Carbon free planet.
- 🌱 I’m currently learning: Code to inact a blockchain that rewards holders of EAL. Thus promoting the act of Recycling Garbage. I know. WtF. But a reward system for not fillking our landfills with Shit we can turn into fertilizer to keep tne earth green.
- 💞️ I’m looking to collaborate on or with: people who realy belive Global warming is a Real thing. Moment in time is now. We can make a change. Cryptography is the Digital answer.
- 📫 How to reach me: law_1010@yahoo.com 8567396090.
- Videos of proper waty to dispose of spoiled vegatabels. images of Recycling collection systems. A fully intergrated way of life that promotes healthy and carbon free lifestyle. Action to ReveseGlobalWarming.

<!---
BlacPanda420/BlacPanda420 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# This workflow will build and push a new container image to Amazon ECR,
-7# and then will deploy a new task definition to Amazon ECS, when there is a push to the main branch.
#
# To use this workflow, you will need to complete the following set-up steps:
#
# 1. Create an ECR repository to store your images.
#    For example: `aws ecr create-repository --repository-name my-ecr-repo --region us-east-2`.
#    Replace the value of the `ECR_REPOSITORY` environment variable in the workflow below with your repository's name.
#    Replace the value of the `AWS_REGION` environment variable in the workflow below with your repository's region.
#
# 2. Create an ECS task definition, an ECS cluster, and an ECS service.
#    For example, follow the Getting Started guide on the ECS console:
#      https://us-east-2.console.aws.amazon.com/ecs/home?region=us-east-2#/firstRun
#    Replace the value of the `ECS_SERVICE` environment variable in the workflow below with the name you set for the Amazon ECS service.
#    Replace the value of the `ECS_CLUSTER` environment variable in the workflow below with the name you set for the cluster.
#
# 3. Store your ECS task definition as a JSON file in your repository.
#    The format should follow the output of `aws ecs register-task-definition --generate-cli-skeleton`.
#    Replace the value of the `ECS_TASK_DEFINITION` environment variable in the workflow below with the path to the JSON file.
#    Replace the value of the `CONTAINER_NAME` environment variable in the workflow below with the name of the container
#    in the `containerDefinitions` section of the task definition.
#
# 4. Store an IAM user access key in GitHub Actions secrets named `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY`.
#    See the documentation for each action used below for the recommended IAM policies for this IAM user,
#    and best practices on handling the access key credentials.

name: Deploy to Amazon ECS i

on:
  push:
    branches:
      - main

