# Hello World Docker Task

A lightweight Python application containerized with Docker. 

---

## 🚀 Quick Start

Follow these steps to build and run the application in a containerized environment.

### 1. Prerequisites
Ensure you have [Docker](https://docs.docker.com/get-docker/) installed and running on your system.

### 2. Build the Image
The following command packages the Python script and the required environment into a Docker image.
```bash
docker build -t hello-world .
```

### 3. Run the Container
Execute the image as a container to see the output.

```bash
docker run hello-world
```

![alt text](image.png)