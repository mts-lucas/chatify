# chatify
Simple message app backend


## Want to use this project?

1. Fork/Clone

2. Create and activate a virtual environment:

    ```sh
    $ python3 -m venv venv && source venv/bin/activate
    ```

3. Install the requirements:

    ```sh
    (venv)$ pip install -r requirements.txt
    ```

4. Apply the migrations:

    ```sh
    (venv)$ python manage.py migrate
    ```

5. Start a Redis server for backing storage:

    ```sh
    (venv)$ docker run -p 6379:6379 -d redis:5
    ```

6. Run the server:

    ```sh
    (venv)$ python manage.py runserver
    ```
