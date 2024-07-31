# k8s-simple-app-new-relic-integration

This repository contains a simple Kubernetes application integrated with New Relic for monitoring and observability. The application demonstrates how to set up and deploy a Kubernetes app with New Relic's infrastructure and logging capabilities.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Architecture](#architecture)
- [Installation](#installation)
  - [1. Clone the Repository](#1-clone-the-repository)
  - [2. Configure New Relic](#2-configure-new-relic)
  - [3. Deploy to Kubernetes](#3-deploy-to-kubernetes)
- [Usage](#usage)

## Prerequisites

Before you begin, ensure you have the following prerequisites:

- Kubernetes cluster (local or cloud-based)
- kubectl configured to interact with your cluster
- Helm installed
- New Relic account with license key

## Architecture

This project includes:

- A simple Kubernetes application
- New Relic integration for infrastructure monitoring and logging
- Helm charts for easy deployment and New Relic configuration

## Installation

### 1. Clone the Repository

```sh
git clone https://github.com/JeremyArc/k8s-simple-app-new-relic-integration.git
cd k8s-simple-app-new-relic-integration
```
### 2. Configure New Relic
Ensure you have your New Relic license key and other required configurations. Update the values-newrelic.yaml file located at ./newrelic/k8s/helm-values/ with your New Relic license key and any other necessary settings.

### 3. Deploy to Kubernetes
Follow the New Relic Kubernetes integration instruction using Helm option.

![image](https://github.com/user-attachments/assets/ae1c9083-d139-4c68-8226-9bdc4a21030f)

## Usage
Once the deployment is complete, you can monitor your application through the New Relic dashboard. The application will send metrics and logs to New Relic, allowing you to observe the performance and health of your Kubernetes cluster and application.


