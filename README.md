# Web-App-with-Flask-and-FASTAPI

# Overview
This project demonstrates a robust web scraping service using two popular Python frameworks: FastAPI and Flask. The service targets the "Box Office Mojo" website to scrape data, processes it, and provides a structured output. This repository showcases the versatility of using both frameworks within the same application environment.

# Features
FastAPI Implementation: For efficient asynchronous operations, endpoint setup, and automatic API documentation.
Flask Implementation: For straightforward routing and template rendering capabilities.
Dynamic Web Scraping: Scrapes and processes box office data from Box Office Mojo.
Logging: Detailed logging of scraping operations to trace and debug the workflow.
RESTful API Endpoints: Includes GET and POST endpoints for interaction and triggering scraping tasks.

# Installation
To run this project locally, you need to install the required dependencies:
pip install -r Pipfile.txt

# Usage
# Start the Flask Server:
python server1.py

This will host the Flask application usually on http://localhost:8000.

# Start the FastAPI Server:
uvicorn server2:app --reload

This will host the FastAPI application with live reload on http://127.0.0.1:8000.

# Triggering the Scraper: Use the provided endpoint to trigger the scraping process:

POST /box-office-mojo-scraper
This can be accessed via the web at the respective server's address.

# API Documentation
FastAPI: Visit http://127.0.0.1:8000/docs for the auto-generated documentation by FastAPI.
Flask: Documentation needs to be manually created or refer to Flask routes in server1.py.
