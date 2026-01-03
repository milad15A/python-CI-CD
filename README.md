# Python CI/CD Pipeline

This repository demonstrates the implementation of a Continuous Integration (CI) and Continuous Deployment (CD) pipeline for a simple Python script using GitHub Actions.

## Overview

The pipeline includes the following steps:

1. **Lint and Test**: The Python code is linted and tested to ensure code quality and correctness.
2. **Build and Push Container Image**: The code is packaged into a Docker container and pushed to GitHub Container Registry (GHCR).
3. **Run and Verify**: The container is pulled and run to verify that the application behaves as expected.

## Challenge Steps

1. **Repository Setup**:
   - A new repository was created with the Python .gitignore template.
   - The repository includes the following files:
     - `hello.py`: A simple Python script.
     - `Dockerfile`: To build the Docker image.
     - `.dockerignore`: To exclude unnecessary files during image build.
     - `python-pipeline.yml`: The GitHub Actions workflow that defines the CI/CD pipeline.

2. **Three-Stage Pipeline**:
   - **Lint and Test**: Ensures code quality.
   - **Build and Push**: Packages the script into a Docker container and uploads it to GitHub Container Registry.
   - **Run and Verify**: Verifies that the built container works correctly.

## How to Use

1. Clone the repository.
2. Ensure you have Docker installed on your local machine for containerization.
3. Push changes to the repository and confirm that the GitHub Actions workflow runs successfully.

The pipeline demonstrates best practices for CI/CD and can be extended for more complex Python applications.

## Notes

This challenge should take approximately 15 minutes to complete.
