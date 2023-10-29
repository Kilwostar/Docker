# Docker Compose Setup for React and Node.js Web Application

This Docker Compose configuration is designed for creating and running a web application with a React frontend and a Node.js backend.

## Prerequisites

Ensure that you have Docker and Docker Compose properly installed on your system before proceeding.

## Installation and Usage

1. Begin by cloning this repository:

   ```shell
   git clone https://github.com/Kilwostar/Docker.git
   cd your-web-app
   ```

2. Install the required modules:

    ```shell
    npm install
    ```

3. Build the Docker images:

    ```shell
    docker-compose build
    ```

4. Launch the containers:

    ```shell
    docker-compose up -d
    ```

You can access the frontend at http://localhost:8000 and the backend at http://localhost:8081.

## Accessing the Database

1. To interact with the database, visit the following URL: http://localhost:8080

2. You will be redirected to the phpMyAdmin database management interface.

3. Log in with the following credentials:
   - Username: user
   - Password: 2003157

4. You can add or remove fields using the provided interface.

## Stopping the Database

To stop the database, run the following command:

```shell
docker-compose stop
```

Note that when you restart the containers, the data in the database will be preserved.