# Railway Management System 
This API provides endpoints for managing railway operations similar to IRCTC. Users can register, login, view available trains, book seats, and retrieve booking details. The API is built using Flask and MySQL, with JWT authentication for user access control.

## Prerequisites

- Python 3.x installed
- pip package manager

## Installation
- Clone the repository:
   git clone https://github.com/tavraj/irctc.git

## Go to the project directory
- cd aladdin

## Create virtual environment
- python -m venv venv

## Activate virtual environment
- source venv/bin/activate

## Install dependencies
- pip install -r requirements.txt

## Usage
- python server.py

## Endpoints
- Authentication : POST /api/auth/login: User login. Requires email and password.
- Register : POST /api/user : Requires email, password and username
- Create a Train : POST api/train : Requires destination, name, source
- Check for availability : /availability
- Book seat : /book/train_id
- Get booking details : /booking/booking_id