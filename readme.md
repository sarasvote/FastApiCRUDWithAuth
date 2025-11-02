FASTAPI CRUD WITH AUTH

1. Install Dependencies


    `pip install fastapi uvicorn sqlalchemy pymysql`

        
fastapi → web framework

uvicorn → ASGI server

sqlalchemy → ORM for DB

pymysql → MySQL driver

2.Mysql Setup

Create a database:

 `CREATE DATABASE fastapi_db;`

3.Create the Project Structure

fastapi_mysql_crud/

main.py

models.py

database.py

schemas.py


4.Run the App

 `uvicorn main:app --reload`
