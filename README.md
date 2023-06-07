# Health Help Assistant using OPEN API

## Description

This is a project that uses the open API to help people who are not good at English to get medical help.
This project is a web application that can be used on the web.

## Installation

1. Clone the repository
  
    ```bash
    git clone https://github.com/rahulranjan937/HelpDesk-Flask
    ```

2. Install the requirements

    ```bash
    pip install -r requirements.txt
    ```

3. Set the environment variables

    Create a file named `.env` and add the following:

    ```bash
     OPEN_API_KEY=<YOUR_OPEN_API_KEY>
    ```

4. Run the application

    ```bash
    python app.py
    ```

    or

    ```bash
    flask run
    ```

5. Visit `http://localhost:5000/`
  
6. Enjoy!

## Docker Setup

* Dockerfile for building the image

  ``` bash
  docker build -t <image-name> .
  ```

* Docker-compose for running the container

  ``` bash
  docker-compose up
  ```

* Docker-compose for running the container in background

  ``` bash
  docker-compose up -d
  ```

* Docker-compose for stopping the container

  ``` bash
  docker-compose down
  ```
  
## License

[MIT](https://choosealicense.com/licenses/mit/)

## Author

[Rahul Ranjan](https://github.com/rahulranjan937/)
