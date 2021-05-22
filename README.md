🎉 Pydantic With SQLAlchemy
=========================

A demonstration on the use of [Pydantic] with [SQLAlchemy] in [Python].

✔ Usage
---------------------

- Install required Python dependencies:

    ```bash
    pip install -r requirements.txt
    ```

- Create Server:

    ```bash
    python -m uvicorn sql_app.main:app --reload
    ```

- Open the displayed url ( usually 127.0.0.1:8000 ) in your browser and use it.


👀 Resources
-----------------------

- https://fastapi.tiangolo.com/tutorial/sql-databases/




[Python]: https://www.python.org/
[Pydantic]: https://pypi.org/project/pydantic/
[SQLAlchemy]: https://pypi.org/project/SQLAlchemy/