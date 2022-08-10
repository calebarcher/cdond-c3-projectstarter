# Project 3 - Build CI/CD Pipelines, Monitoring & Logging

## Objective

The objective of this project is to build a CI/CD pipeline for a fictional project called **Udapeople**. This CI/CD pipeline will do the following

- Build the project
- Run Tests
- Scan the project for vulneraibilites
- provision infrastructure on AWS using AWS Cloudformation
- Confifure the infrastructure using Ansible
- Run migration
- Run Deployments using a blue/green deployment strategy
- Run Smoke tests
- Destroy the environment and revert migrations if smoketest fails
- Clean up of old environment after successful deployment.

## Tools

The following tools are used for this project

- CircleCi: Circle Ci is a CI/CD tool used for automating building, testing and deployement of code
- AWS Cloudformation: An IAC service that allows users to provision AWS resources using code.
- Ansible: Ansible is used for configuring the backend EC2 instances we provisioned
- KVDB: A key-Value data store for saving our migration results
