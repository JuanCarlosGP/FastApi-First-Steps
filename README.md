# FastAPI First Steps

This repository contains the code for a basic FastAPI project aimed at helping beginners get started with FastAPI.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project serves as a starting point for those who want to learn FastAPI, a modern, fast (high-performance), web framework for building APIs with Python 3.7+. It provides a structured layout and basic functionality to kickstart your FastAPI development journey.

## Features

- Basic FastAPI setup.
- Simple API endpoints.
- CRUD (Create, Read, Update, Delete) operations example.
- Docker configuration for containerization.

## Requirements

- Python 3.7+
- pip (Python package installer)
- [FastAPI](https://fastapi.tiangolo.com/) and its dependencies (installed automatically via `requirements.txt`)
- Docker (optional, for containerization)

## Installation

1. Clone this repository:

    ```
    git clone https://github.com/JuanCarlosGP/FastApi-First-Steps.git
    ```

2. Navigate to the project directory:

    ```
    cd FastApi-First-Steps
    ```

3. Install dependencies:

    ```
    pip install -r requirements.txt
    ```

## Usage

1. Run the FastAPI application:

    ```
    uvicorn main:app --reload
    ```

2. Access the API at `http://localhost:8000` in your web browser or API client.

## Contributing

Contributions are welcome! If you find any issues or would like to suggest improvements, please open an issue or submit a pull request. For major changes, please open an issue first to discuss the proposed changes.

## License

This project is licensed under the [MIT License](LICENSE).
