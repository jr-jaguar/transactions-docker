1. Run the project using Docker Compose:
    ```
    docker-compose up -d
    ```

2. Execute the following command to enter the Docker container:
    ```
    docker exec -it transactions-app bash
    ```
3. Run the application with the following command, specifying the input file:
    ```
    php public/index.php input.txt
    ```
