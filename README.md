# Tea API – CRUD Operations using FastAPI

A simple RESTful API built using **FastAPI** and **Python** to perform CRUD (Create, Read, Update, Delete) operations on tea records.

## Overview

This project demonstrates the fundamentals of building REST APIs with FastAPI. It allows users to create, retrieve, update, and delete tea records using HTTP methods.

The project uses Pydantic models for data validation and Python lists for temporary in-memory data storage.

## Tech Stack

- **Python** – Programming Language
- **FastAPI** – Backend Framework
- **Pydantic** – Data Validation
- **Uvicorn** – ASGI Server
- **Swagger UI** – API Testing & Documentation

## Features

- Create a new tea record.
- Retrieve all available tea records.
- Update an existing tea record using its ID.
- Delete a tea record using its ID.
- Validate request data using Pydantic BaseModel.
- Interactive API documentation with Swagger UI.

## Project Structure

```text
FastApi-/
│
├── main.py
├── requirements.txt
├── .gitignore
└── README.md
