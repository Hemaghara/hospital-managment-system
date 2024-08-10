# hospital-managment-system

Hospital Management System
Overview
This Java-based Hospital Management System provides a simple command-line interface for managing patients and doctors within a hospital. It interacts with a MySQL database to perform CRUD (Create, Read, Update, Delete) operations related to patients and doctors, as well as manage appointments.

Features
Add New Patients: Insert new patient records into the database.
View All Patients: Retrieve and display details of all patients.
View All Doctors: Retrieve and display details of all doctors, including their specializations.
Appointment Details: Query appointments to find out which doctors are booked on a specific date.
Retrieve Patient ID: Fetch patient ID based on the patient's name.
Retrieve Doctor ID: Fetch doctor ID along with their specialization based on the doctor's name.

Prerequisites
Java: Ensure that you have Java installed on your system.
MySQL: A MySQL database server should be running with a database named hem.
JDBC Driver: The MySQL JDBC driver (mysql-connector-java) should be included in your project's classpath.

Database Schema
Ensure the following tables exist in your MySQL database:

patients: A table to store patient information.
Columns: id, name, age, gender
doctor: A table to store doctor information.
Columns: id, name, doctor_specialization
appointments: A table to store appointment details.
Columns: appointment_date, doctor_id
