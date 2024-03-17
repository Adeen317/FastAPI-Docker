# FastAPI + Docker

## Machine Learning App using Hugging Face Model

This repository contains a machine learning application built with FastAPI and Docker, leveraging the powerful capabilities of Hugging Face's models for natural language processing tasks.

## Features

- **FastAPI Backend:** Utilizes FastAPI for creating robust and scalable APIs with minimal code.
- **Hugging Face Model:** Integrates Hugging Face's pre-trained models for various natural language processing tasks, such as text classification, named entity recognition, sentiment analysis, etc.
- **Dockerized Environment:** Docker containerization ensures easy deployment and consistent environment setup across different platforms.

## Requirements

- Docker
- Docker Compose

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/FastAPI-Docker.git
   ```

2. Navigate to the project directory:

   ```bash
   cd FastAPI-Docker
   ```

3. Build and run the Docker containers:

   ```bash
   docker-compose up -d --build
   ```

4. Access the FastAPI application at `http://localhost:8000` in your browser.

## Usage

Once the application is up and running, you can interact with it through the defined endpoints. These endpoints are designed to handle various NLP tasks, depending on the Hugging Face model used.

You can explore the API documentation available at `http://localhost:8000/docs` for detailed information on each endpoint and how to use them.

## Configuration

If needed, you can configure the application by modifying the environment variables or Docker configuration files. This allows customization of the model used, API behavior, or any other settings relevant to your application's requirements.

## Contributing

Contributions are welcome! Whether it's bug fixes, new features, or enhancements, feel free to open an issue or submit a pull request to help improve this project.
