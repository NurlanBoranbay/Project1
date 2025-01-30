Disease Information and Reporting System (DIRS)
The Disease Information and Reporting System (DIRS) is a web-based application built using Flask and PostgreSQL to manage health-related data. This system provides an interactive interface for handling users, countries, diseases, doctors, and patient disease records.

Key Features:
User Management: Create, update, delete, and view users with attributes such as email, name, surname, salary, company name, and phone number.
Country Data Tracking: Store and retrieve country names along with their population data.
Disease Management: Maintain records of diseases, their pathogens, descriptions, and associated disease types.
Discovery Tracking: Record the first encounter dates of diseases in specific countries.
Doctor Registry: Store information about doctors, their qualifications, and their association with users.
Patient Disease Records: Track which patients have been diagnosed with specific diseases.
Technology Stack:
Backend: Flask (Python)
Database: PostgreSQL (SQLAlchemy ORM)
Frontend: Jinja2 Templates (for rendering dynamic pages)
Hosting: AWS RDS for PostgreSQL database
This system serves as a foundation for health organizations to manage disease reporting, patient tracking, and medical professional records efficiently.
