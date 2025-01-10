# Railway Reservation System

This is a Railway Reservation System built using Django. It allows users to search for trains, book tickets, and manage reservations.

## Features

- User authentication (login, logout, registration)
- Search for trains between stations
- View train schedules
- Book and cancel tickets
- View PNR status

## Setup Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/railway_reservation_system.git
    ```
2. Navigate to the project directory:
    ```bash
    cd railway_reservation_system
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Apply migrations:
    ```bash
    python manage.py migrate
    ```
5. Create a superuser:
    ```bash
    python manage.py createsuperuser
    ```
6. Run the development server:
    ```bash
    python manage.py runserver
    ```

## Usage

1. Open your web browser and go to `http://127.0.0.1:8000/`.
2. Register a new user or log in with an existing account.
3. Use the navigation menu to search for trains, view schedules, book tickets, and manage reservations.

## Project Structure

- `home/`: Contains views, models, and templates for the home app.
- `features/`: Contains views, models, and templates for the features app.
- `rail/`: Contains project settings and URL configurations.

## Contributing

Contributions are welcome! Please create a pull request with your changes.
