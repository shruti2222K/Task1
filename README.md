# CI/CD Pipeline Using GitHub Actions

## Objective
Automate the build and deployment process of a Node.js application using GitHub Actions and Docker.

## Tools Used
- GitHub
- GitHub Actions
- Node.js
- Docker
- DockerHub

## Project Structure

```text
Task1/
├── .github/workflows/main.yml
├── Dockerfile
├── app.js
├── package.json
└── README.md
```

## CI/CD Workflow

The pipeline is triggered automatically on every push to the main branch.

Steps:
1. Checkout source code
2. Setup Node.js environment
3. Install dependencies
4. Run tests
5. Login to DockerHub using GitHub Secrets
6. Build Docker image
7. Push Docker image to DockerHub

## GitHub Secrets Used

- DOCKER_USERNAME
- DOCKER_PASSWORD

## Outcome

Successfully implemented a CI/CD pipeline using GitHub Actions for a Node.js application.

Workflow Status: Successful
