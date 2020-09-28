# Flask Boiler Plate Api

>Documentation
- Flask
  - https://flask.palletsprojects.com/en/1.1.x/
- Flask SQLAlchemy
  - https://flask-sqlalchemy.palletsprojects.com/en/2.x/
- Flask Marshmallow
  - https://flask-marshmallow.readthedocs.io/en/latest/
- Marshmallow-sqlalchemy
  - https://marshmallow-sqlalchemy.readthedocs.io/en/latest/

## Api Endpoints


- Get all guides
    - URL: http://localhost:5000/guides
    - Method: GET


- Create a guide
    - URL: http://localhost:5000/guide
    - Method: POST
    - Send Body of json
    ```json
    {
        "title": "some title",
        "content": "some content"
    }
    ```
- Get a singe guide
    - URL: http://localhost:5000/guide/id
    - Method: GET

- Edit a guide
    - URL: http://localhost:5000/guide/id
    - Method: PUT
    - Send Body of json
    ```json
    {
        "title": "Updated title",
        "content": "Updated content"
    }
    ```

- Delete a guide
    - URL: http://localhost:5000/guide/id
    - Method: DELETE

# Environment Stuff

- open terminal in folder
- Run this in the terminal 
    ```
    pipenv -- three (sets python3 as the version for the environment)
    ```
- Use the following command to enter shell
    ```
    pipenv shell
    ```
- install any packages needed locally in pipenv
    ```
    pipenv install numpy or whatever library is being called
    ```
- command to open repl in python
- to start server
    ```
    python app.py << Filename. py>>