# Re_seed Website

Re_seed is an online platform for buying and selling used books. It also provides book recommendations based on user preferences. The website is developed using ReactJS for the frontend and Django for the backend. The frontend folder contains React view pages, while the backend folder contains the Django server and database connection.

## Features

- Online platform for buying and selling used books
- Book recommendation system based on user preferences
- User-friendly interface with a responsive design
- Secure authentication and authorization
- Database connection for storing book and user information

## Technologies Used

- ReactJS
- Django
- Database (e.g., PostgreSQL, MySQL, SQLite)

## Project Structure

The project structure is organized as follows:

- `frontend/` - Contains the ReactJS views and components.
- `backend/` - Contains the Django server and database connection.
- `database/` - Contains database migration files.

## Installation

To install and run this project locally, follow these steps:

1. Clone the repository:


git clone https://github.com/HrushabhPatade/Re-seed.git

2. Navigate to the project directory:

cd Reseed

3. Set up the frontend:

Navigate to the frontend folder:

cd frontend

Install the dependencies:

npm install

4. Set up the backend:

Navigate to the backend folder:

cd backend

Install the required dependencies (preferably in a virtual environment):

pip install -r requirements.txt

5. Configure the database connection:

Create a database of your choice (e.g., PostgreSQL, MySQL, SQLite).
Update the database settings in the backend's settings.py file.

6. Start the frontend server:

In the frontend folder, run:

npm start

The frontend server will start on http://localhost:3000.

7.Start the backend server:

In the backend folder, run:

python manage.py runserver

The backend server will start on http://localhost:8000.

8. Open your web browser and go to http://localhost:3000 to access the Re_seed website.

## Usage
Use the navigation links on the website to browse and search for used books.
Register and log in to buy or sell books and access personalized book recommendations.
Explore the different features and functionalities of the Re_seed website.
