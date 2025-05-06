# holbertonschool-softy-pinko-docker

This project is part of the Holberton School curriculum. It focuses on Docker and containerization, providing a hands-on approach to understanding and implementing Docker in real-world scenarios.

## Table of Contents

- [holbertonschool-softy-pinko-docker](#holbertonschool-softy-pinko-docker)
  - [Table of Contents](#table-of-contents)
  - [Description](#description)
  - [Requirements](#requirements)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Author](#author)

## Description

The goal of this project is to explore the fundamentals of Docker, including creating and managing containers, building Docker images, and understanding Dockerfiles. It provides practical exercises to help you become proficient in containerization technologies.

## Requirements

- Docker installed on your system (version 20.x or higher recommended)
- Basic knowledge of Linux commands
- Git for version control

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/holbertonschool-softy-pinko-docker.git
    ```
2. Navigate to the project directory:
    ```bash
    cd holbertonschool-softy-pinko-docker
    ```
3. Build the Docker image:
    ```bash
    docker build -t softy-pinko .
    ```

## Usage

1. Run the Docker container:
    ```bash
    docker run -d -p 8080:80 softy-pinko
    ```
2. Access the application in your browser at `http://localhost:8080`.

## Author

This project was created by **Jonas** as part of the Holberton School curriculum.
