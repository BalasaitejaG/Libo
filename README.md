# Libo - A Online library managnemt system

A comprehensive digital library management system built with Python and Django that helps librarians and users manage books, memberships, and transactions efficiently.

## Features

- User Authentication and Authorization
  - Separate interfaces for administrators and members
  - Secure login and registration system
  - Role-based access control

- Book Management
  - Add, update, and remove books from the library
  - Track book availability and location
  - Manage multiple copies of the same book
  - Search books by title, author, category, or ISBN

- Member Management
  - Member registration and profile management
  - Track membership status and history
  - Manage member borrowing limits

- Transaction Management
  - Issue and return books
  - Track due dates and calculate fines
  - Reservation system for books
  - Email notifications for due dates and reservations

- Reports and Analytics
  - Generate reports on book circulation
  - Track popular books and categories
  - Monitor overdue books and fines collected

## Technology Stack

- Backend: Python, Django
- Database: SQLite
- Frontend: HTML, CSS, JavaScript, Bootstrap
- Authentication: Django Authentication System
- Additional: Django REST Framework for API

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/library-management-system.git
   cd library-management-system
   ```

2. Create and activate virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Apply database migrations:
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

7. Access the application at `http://localhost:8000`

## Usage

1. Admin Interface:
   - Access the admin panel at `/admin`
   - Manage books, members, and transactions
   - Generate reports and handle fines

2. User Interface:
   - Browse and search books
   - View availability status
   - Place reservations
   - Track borrowed books and due dates

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
