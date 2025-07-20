# Hostel-Management-System
Hostel Management System Database
This project contains the SQL schema and sample data for a Hostel Management System, designed to streamline the management of hostels, rooms, mess allocations, and student information.

 <B>Project Overview</B>
The system is designed for:

Hostel room allocation

Mess card application and allocation

Hostel and mess management by admin and hostel managers

Payment tracking for hostel fees

Reporting student-wise and hostel-wise data

 <B>Database Entities </B>
Student — Manages student details, allocated room, and mess card.

Hostel — Stores hostel information, room capacity, and current occupancy.

Room — Tracks room details and allocation status.

Mess — Handles mess details, types, size, and vacancy.

Mess_Allocation — Manages mess card allocation for students.

Hostel_Manager — Admin/hostel managers with assigned hostel and mess.

Application — Tracks hostel application requests.

Application_mess — Tracks mess application requests.

Payment — Tracks payment status of students.

<B>Features</B>
Automatic update of hostel and mess occupancy via SQL triggers

Stored procedure for fetching hostel-wise reports (by branch/year)

Sample dataset with hashed passwords for demonstration

View Hostel_Manager_Profile for quick manager and hostel summary

 <B>Setup Instructions</B>
Import hostel_management_system.sql into your MySQL server.

The database will be created along with all necessary tables, views, triggers, and sample data.

Use root or admin privileges to access the system for testing.

<B>Reports & Views</B>
Hostel_Manager_Profile view provides an occupancy summary for hostels and messes.

SP_branch_year stored procedure generates student reports by branch or year.

<B>Dependencies</B>
MySQL 5.7+ (compatible with default SQL modes)

MySQL Workbench (recommended for database management)
