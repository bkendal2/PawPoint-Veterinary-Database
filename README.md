# PawPoint Veterinary Database

A relational database system built in MySQL for a multi-location veterinary clinic. The project demonstrates database design, SQL implementation, data integrity, querying, stored procedures, triggers, views, and transaction management.

## Project Overview

PawPoint Veterinary Group is a fictional veterinary clinic network operating across multiple locations. This project involved designing and implementing a relational database capable of managing the organization's day-to-day clinical and business information.

The database supports information related to clinics, veterinarians, pet owners, animals, appointments, treatments, prescriptions, vaccinations, billing, payments, and inventory.

## Technologies Used

- MySQL
- SQL
- MySQL Workbench
- Relational Database Design
- Database Normalization
- Stored Procedures
- Triggers
- Views
- Transactions

## Database Features

The database includes functionality for:

- Managing multiple veterinary clinic locations
- Maintaining veterinarian and specialization information
- Tracking pet owners and animals
- Supporting animals with multiple owners
- Recording appointments and treatments
- Managing prescriptions and authorized refills
- Tracking vaccinations
- Managing invoices and payments
- Monitoring clinic inventory
- Recording inventory movements
- Enforcing relationships through primary and foreign keys

## Database Structure

Major tables include:

- `Clinic`
- `ClinicHours`
- `Owner`
- `Animal`
- `Veterinarian`
- `Specialization`
- `Appointment`
- `Treatment`
- `Prescription`
- `PrescriptionRefill`
- `Vaccine`
- `Vaccination`
- `Invoice`
- `Payment`
- `InventoryItem`
- `InventoryMovement`

Junction tables such as `AnimalOwner`, `AnimalAllergy`, and `VetSpecialization` are used to represent many-to-many relationships while maintaining a normalized database structure.

## SQL Functionality

The implementation goes beyond basic table creation and includes:

- Table creation and constraints
- Sample data insertion
- Primary and foreign keys
- Multi-table joins
- Aggregate queries
- Views
- Stored procedures
- Database transactions
- Triggers and validation rules

## Data Integrity

Foreign-key relationships and database constraints are used to maintain consistency between related records.

The project also implements database-level business rules. For example, a prescription refill trigger prevents the number of used refills from exceeding the number originally authorized.

## What I Learned

This project gave me hands-on experience taking a relational database from the design stage to a functioning MySQL implementation.

I gained practical experience with database normalization, many-to-many relationships, primary and foreign keys, SQL queries, stored procedures, views, transactions, and triggers.

Testing the database also demonstrated the importance of enforcing business rules at the database level rather than relying solely on application logic.

## Future Improvements

Potential future enhancements could include:

- Connecting the database to a web-based veterinary management application
- Adding role-based access control
- Building reporting and analytics dashboards
- Implementing automated backup and recovery procedures
- Migrating the database to a managed cloud database platform

## Disclaimer

PawPoint Veterinary Group is a fictional organization created for educational and portfolio purposes. All sample data used in this project is fictional.
