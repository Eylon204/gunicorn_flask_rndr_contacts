# Contact Manager - Flask API with HTML Frontend

This is a simple **Contact Manager** application built with **Flask** on the backend and a basic **HTML/JavaScript** frontend. The application allows users to perform **CRUD operations** (Create, Read, Update, Delete) on contacts stored in a **SQLite** database. It demonstrates how to build a REST API using Flask and how to connect it to a frontend for seamless interaction.

## Table of Contents
- [Contact Manager - Flask API with HTML Frontend](#contact-manager---flask-api-with-html-frontend)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Technologies Used](#technologies-used)
  - [Installation](#installation)
    - [Prerequisites](#prerequisites)
    - [Clone the Repository](#clone-the-repository)
- [Backend Setup](#backend-setup)
    - [1.	Create a virtual environment:](#1create-a-virtual-environment)
    - [2.	Install the required dependencies:](#2install-the-required-dependencies)
  - [Frontend Setup](#frontend-setup)
  - [Usage](#usage)
    - [1.	Activate your virtual environment if not already activated:\\](#1activate-your-virtual-environment-if-not-already-activated)
    - [2.	Start the Flask server:](#2start-the-flask-server)
    - [3.	The backend should now be running on http://127.0.0.1:5000.](#3the-backend-should-now-be-running-on-http1270015000)
- [Running the Frontend](#running-the-frontend)

---

## Features
- **Add Contact**: Add new contacts to the database with name, email, and age.
- **View Contacts**: Display a list of all saved contacts.
- **Update Contact**: Modify contact details such as name, email, and age.
- **Delete Contact**: Remove a contact from the database.
- **CORS Enabled**: Allows cross-origin requests for easy communication between the frontend and backend.

---

## Technologies Used
- **Backend**:
  - Flask
  - Flask-SQLAlchemy (ORM for database management)
  - Flask-CORS (To enable CORS)
  - SQLite (as the database)

- **Frontend**:
  - HTML
  - CSS
  - JavaScript (Fetch API)

---

## Installation

### Prerequisites
Ensure you have the following installed:
- **Python 3.x**: [Install Python](https://www.python.org/downloads/)
- **Flask**: [Flask Documentation](https://flask.palletsprojects.com/en/2.0.x/)

### Clone the Repository
git clone https://github.com/yourusername/contact-manager.git
cd contact-manager

# Backend Setup

### 	1.	Create a virtual environment:
python3 -m venv env
source env/bin/activate  # For MacOS/Linux
or
.\env\Scripts\activate  # For Windows

### 	2.	Install the required dependencies:
pip install -r requirements.txt

## Frontend Setup

The frontend is a simple HTML page with JavaScript for interacting with the API. You don’t need any special setup other than running a static file server if needed.

## Usage

Running the Backend

###	1.	Activate your virtual environment if not already activated:\
source env/bin/activate  # Mac/Linux
or
.\env\Scripts\activate  # Windows

###	2.	Start the Flask server:
python app.py #Windows
or
python3 app.py #MacOS/Linux

### 3.	The backend should now be running on http://127.0.0.1:5000.

# Running the Frontend
	1.	Open the index.html file in your browser (simply double-click it or use an editor like VSCode’s Live Server extension).
	2.	The frontend will automatically interact with the backend to display, add, edit, and delete contacts.