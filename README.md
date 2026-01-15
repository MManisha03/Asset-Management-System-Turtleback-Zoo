# Turtleback Zoo Management System

The Turtleback Zoo Management System is a full-stack web application designed to
streamline day-to-day zoo operations through a centralized administrative interface.
The system enables administrators to manage animals, buildings, attractions, and
revenue data efficiently.

## Tech Stack
- Backend: Python (Flask)
- Frontend: HTML, CSS, Jinja2 Templates
- Database: MySQL (Relational Database)
- Architecture: MVC-style design

## Features
- Create, view, update, and delete records for animals, buildings, and attractions
- Manage hourly rates and operational details
- Generate reports for attendance and revenue tracking
- Admin-friendly web interface for easy data management
- Structured relational schema for consistent and reliable data storage

## Database Design
The backend uses a normalized relational database defined in `dmsd_schema.sql`.
The schema separates core entities such as animals, buildings, attractions, and
revenue data to reduce redundancy and support efficient reporting queries.

## Application Workflow
- User requests are handled through Flask routes
- Business logic processes input and interacts with the database
- Dynamic HTML templates render results to the user
- CRUD operations ensure complete administrative control

## Setup Instructions
1. Clone the repository
2. Install required Python dependencies
3. Import `dmsd_schema.sql` into MySQL
4. Run the application using `python main.py`
5. Access the application via the local server

## Future Enhancements
- Authentication and role-based access control
- REST API support
- Cloud deployment and scalability improvements
- Enhanced reporting and dashboard visualizations

## Summary
This project demonstrates practical use of full-stack web development concepts,
including backend logic, database design, and frontend templating. It reflects
real-world administrative workflows and emphasizes maintainable code structure,
data integrity, and usability.
