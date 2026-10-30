# Health Care Management System

## Overview

This project was developed as part of the Database course at Instituto Superior Técnico and consists of designing a data model for a healthcare services company. The project was divided into two main deliverables, involving Entity-Relationship (ER) modelling, conversion into a relational model, and the implementation of queries using Relational Algebra and SQL.

## Deliverable 1: Entity-Relationship Modelling and Conversion to the Relational Model

### 1. Entity-Relationship Modelling

In the first phase, an Entity-Relationship (ER) model was created to represent the application's information requirements. The problem domain involved the management of clinics, healthcare professionals (doctors and nurses), patients, medical appointments, and medical prescriptions.

#### Main Entities and Relationships

- Clinic: Identified by its name, with address and phone number.
- Healthcare Professional: Includes doctors and nurses, identified by their Tax Identification Number (NIF), with additional attributes such as name, address, phone number, and IBAN. Doctors also have a medical specialty.
- Patient: Identified by their National Health Service (SNS) number, with attributes such as name, NIF, date of birth, address, and phone number.
- Medical Appointment: A relationship between a patient, a doctor, and a clinic, recording symptoms and, optionally, medical prescriptions.

### 2. ER-to-Relational Model Conversion

The Entity-Relationship model was converted into a relational model following the notation taught in class. Integrity constraints were identified to complement the model, ensuring that only valid scenarios could be represented in the database.

#### Relational Model

- Tables were created for each entity (e.g., Clinic, Doctor, Patient).
- Relationships were represented using foreign keys to ensure referential integrity.
- Additional constraints, such as `UNIQUE` and `FK`, were defined where necessary.

## Deliverable 2: Relational Algebra & SQL

### 1. Relational Algebra Queries

In this phase, queries were formulated to answer specific questions based on the relational schema.

### 2. SQL Queries

The queries were also implemented in SQL, covering questions such as retrieving patients who have consulted doctors from every medical specialty and identifying doctors with the most loyal patients.

## Project Structure

- Entity-Relationship Diagram: `modelo_EA.drawio`
- Relational Model: `modelo_relacional.sql`
- SQL Queries: `consultas.sql`
- Reports: `relatorio_entrega1.pdf`, `relatorio_entrega2.pdf`

## Conclusion

This project provided an in-depth understanding of data modelling processes and the practical application of Relational Algebra and SQL for database manipulation.

