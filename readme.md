# ToDo FastAPI Project 🗂️

## Overview 🌟

This project is a simple ToDo application built with FastAPI and SQLAlchemy. It allows users to create, read, update, and delete ToDo items using a RESTful API. The database used for this project is SQLite.


## Components 🛠️

1. **Database Configuration (`api/database/db_engine.py`)**:
   - Uses SQLAlchemy to connect to an SQLite database.
   - Provides a function `get_db` to manage database sessions.

2. **Models (`api/routes/models.py`)**:
   - `ToDoCreate`: Pydantic model for validating data when creating or updating a ToDo item.
   - `ToDoResponse`: Pydantic model for serializing the response of ToDo items.

3. **Schemas (`api/database/schemas.py`)**:
   - `ToDo`: SQLAlchemy model representing the ToDo table in the database.

4. **Main Application (`main.py`)**:
   - Defines FastAPI routes to handle CRUD operations on ToDo items.
   - Includes endpoints for creating, reading, updating, and deleting ToDo items.




