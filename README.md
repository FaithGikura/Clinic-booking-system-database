# Clinic-booking-system-database

## Description
This project is a MySQL-based relational database design for a Clinic Booking System.
It manages doctors, their specializations, patients, appointment bookings, and payments.

## The database implements:

Primary Keys (PK) and Foreign Keys (FK)

Unique and NOT NULL constraints

One-to-Many (1:M) and Many-to-Many (M:N) relationships

Proper relational integrity

## How to Run/Setup
To import and set up the database:

Open your MySQL tool (e.g., MySQL Workbench, phpMyAdmin, or Command Line).

Create a new database (optional but recommended):

CREATE DATABASE clinic_booking;

USE clinic_booking;

Import the provided clinic_booking.sql file:

If using the terminal:

mysql -u your_username -p clinic_booking < clinic_booking.sql
Or upload the file through your SQL tool.

 Ensure your MySQL server is running before importing the file.

## Entity Relationship Diagram (ERD)
You can view the system's ERD here:

## Project Structure
/clinic-booking-system-db
│
├── README.md
├── clinic_booking.sql
└── assets/
    └── ERD.png (optional: ERD screenshot)
## Features
Doctors can have multiple areas of specialization.

Patients can book multiple appointments.

Each appointment is linked to one doctor and one patient.

Each appointment can have one payment.

Many-to-Many relationship between doctors and specializations.

## Author
Faith Gikura

