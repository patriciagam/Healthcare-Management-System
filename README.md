# Database Project 2023/2024

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

# Database Project 2023/2024

## Overview
# Projeto de Bases de Dados 2023/2024

## Resumo

Este projeto foi desenvolvido no âmbito da cadeira de Bases de Dados do Instituto Superior Técnico e consiste na criação de um modelo de dados para uma empresa de prestação de cuidados de saúde. O projeto foi dividido em duas entregas principais, que envolveram a modelação Entidade-Associação, conversão para um modelo relacional, e a implementação de consultas utilizando Álgebra Relacional e SQL.

## Entrega 1: Modelação Entidade-Associação e Conversão para Modelo Relacional

### 1. Modelação Entidade-Associação

Nesta primeira fase, foi criado um modelo Entidade-Associação que representa os requisitos de informação da aplicação. O domínio do problema envolvia a gestão de clínicas, profissionais de saúde (médicos e enfermeiros), pacientes, consultas, e receitas médicas.

#### Principais Entidades e Relações

* **Clínica**: Identificada pelo nome, com morada e telefone.
* **Profissional de Saúde**: Inclui médicos e enfermeiros, identificados pelo NIF, com atributos adicionais como nome, morada, telefone e IBAN. Médicos possuem uma especialidade.
* **Paciente**: Identificado pelo número do SNS, com atributos como nome, NIF, data de nascimento, morada e telefone.
* **Consulta**: Associação entre paciente, médico, e clínica, com registo de sintomas e, eventualmente, receitas médicas.

### 2. Conversão E-A–Relacional

O modelo Entidade-Associação foi convertido para um modelo relacional seguindo a notação aprendida nas aulas. Foram identificadas restrições de integridade que completam o modelo, assegurando que apenas situações válidas são representadas na base de dados.

#### Modelo Relacional

* Tabelas para cada entidade (e.g., **Clinica**, **Medico**, **Paciente**).
* Relações com chaves estrangeiras para garantir a integridade referencial.
* Restrições adicionais como `unique` e `FK` foram definidas conforme necessário.

## Entrega 2: Álgebra Relacional & SQL

### 1. Consultas em Álgebra Relacional

Nesta fase, foram formuladas consultas para responder a interrogações específicas sobre o esquema relacional.

### 2. Consultas em SQL

As consultas foram também implementadas em SQL, abrangendo questões como a obtenção de pacientes que consultaram médicos de todas as especialidades e identificação de médicos com pacientes mais fiéis.

## Estrutura do Projeto

* **Diagrama Entidade-Associação**: `modelo_EA.drawio`
* **Modelo Relacional**: `modelo_relacional.sql`
* **Consultas em SQL**: `consultas.sql`
* **Relatório**: `relatorio_entrega1.pdf`, `relatorio_entrega2.pdf`

## Conclusão

O projeto proporcionou uma compreensão aprofundada dos processos de modelação de dados e da aplicação prática da Álgebra Relacional e SQL para a manipulação de bases de dados.



# Database Project 2023/2024

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

