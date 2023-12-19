# Dockerapp

Project contains basic Nest.js and Next.js project. 


## Overview

Provide a brief overview of your project, explaining its purpose, features, and any other relevant information.

## Prerequisites

Ensure you have the following prerequisites installed on your machine:

- [Docker](https://www.docker.com/get-started)


## Building the Docker Image

To build the Docker image for your application, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/daniela0111/your-repo.git
    cd your-repo
    ```

2. Build the Docker image:

    ```bash
    docker build -t your_image_name .
    ```

### Customizing the Docker Build

If your application requires specific build configurations, mention them here. For example, if your app needs environment variables during the build process, specify how to pass them:

```bash
docker build -t your_image_name --build-arg ENV_VARIABLE=value .

