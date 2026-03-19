# Java Web App Deployment with AWS CI/CD

This project combines Java web app development with AWS CI/CD tools.

<br>

## Table of Contents
- [Introduction](#introduction)
- [Technologies](#technologies)
- [Setup](#setup)
- [Conclusion](#conclusion)

<br>

## Introduction
This project is used for an introduction to creating and deploying a Java-based web app using AWS, especially their CI/CD tools.

The deployment pipeline I'm building around the Java web app in this repository is invisible to the end-user, but makes a big impact by automating the software release processes.

<br>

## Technologies
- **Amazon EC2**: I'm developing my web app on Amazon EC2 virtual servers. Software development and deployment happens entirely on the cloud.
- **VS Code**: For my IDE, I chose Visual Studio Code. It connects directly to my development EC2 instance, making it easy to edit code and manage files in the cloud.
- **GitHub**: All my web app code is stored and versioned in this GitHub repository.
- **AWS CodeArtifact**: CodeArtifact stores artifacts and dependencies. Ensures high availability and speeding up project's build process.
- **AWS CodeBuild**: CodeBuild will take over the build process. It'll compile the source code, run tests, and produce ready-to-deploy software packages automatically.
- **AWS CodeDeploy**: CodeDeploy automates deployment process across EC2 instances.
- **AWS CodePipeline**: CodePipeline will automate the entire process from GitHub to CodeDeploy, integrating build, test, and deployment steps into one efficient workflow.


<br>

## Setup
To get this project up and running on your local machine, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/nextwork-web-project.git
    ```
2. Navigate to the project directory:
    ```bash
    cd nextwork-web-project
    ```
3. Install dependencies:
    ```bash
    mvn install
    ```

<br>

## Conclusion
Shoutout to **[NextWork](https://learn.nextwork.org/app)** for their project guide.
