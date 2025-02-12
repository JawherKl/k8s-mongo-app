# k8s-mongo-app

![Repository Size](https://img.shields.io/github/repo-size/JawherKl/k8s-mongo-app)
![Last Commit](https://img.shields.io/github/last-commit/JawherKl/k8s-mongo-app)
![Issues](https://img.shields.io/github/issues-raw/JawherKl/k8s-mongo-app)
![Forks](https://img.shields.io/github/forks/JawherKl/k8s-mongo-app)
![Stars](https://img.shields.io/github/stars/JawherKl/k8s-mongo-app)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
Welcome to the k8s-mongo-app repository! This project aims to provide a seamless integration of MongoDB with Kubernetes, enabling users to deploy and manage MongoDB instances within a Kubernetes cluster efficiently.

## Features
- Easy deployment of MongoDB on Kubernetes
- Scalable and highly available MongoDB instances
- Automated backups and recovery
- Monitoring and logging integration
- Secure access with authentication and authorization

## Getting Started
Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites
Before you begin, ensure you have met the following requirements:
- Kubernetes cluster (minikube, GKE, EKS, etc.)
- kubectl CLI tool
- Helm package manager

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/JawherKl/k8s-mongo-app.git
    cd k8s-mongo-app
    ```
2. Deploy MongoDB using Helm:
    ```bash
    helm install my-mongo ./
    ```

## Usage
Access the MongoDB instance using the following command:
```bash
kubectl port-forward svc/my-mongo 27017:27017
```
Then connect to MongoDB at `mongodb://localhost:27017`.

## Configuration
Customize the Helm chart values by editing the `values.yaml` file to fit your requirements.

## Contributing
Contributions are welcome! Please follow the [Contributing Guidelines](CONTRIBUTING.md).

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact
For any questions or suggestions, feel free to open an issue or contact the repository owner at [JawherKl](https://github.com/JawherKl).

---

Happy coding!
