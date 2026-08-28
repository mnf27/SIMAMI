# SIMAMI – Internal Quality Audit Management System

SIMAMI (Sistem Informasi Manajemen Audit Mutu Internal) is a web-based
application developed to support the management and monitoring of
Internal Quality Audits (AMI) for the D3 Information Technology Program
at Politeknik Negeri Malang PSDKU Lumajang.

This project was developed as a final academic project for the
D3 Information Technology program.

## Project Overview

SIMAMI provides a centralized system for managing the Internal Quality
Audit process, from audit creation and finding management to follow-up,
review, and validation.

The application implements role-based access control so that each user
can access features according to their responsibilities in the audit
process.

The system is designed to help make audit activities more structured,
traceable, and easier to monitor.

## Preview

### Assessor Dashboard

<img width="1908" height="1002" alt="Dashboard Asesor (SIMAMI)" src="https://github.com/user-attachments/assets/1459cd80-155a-4e5e-a62d-cb9ae9dcdecf" />

### Audit Management

<img width="1908" height="1002" alt="Audit Asesor (SIMAMI)" src="https://github.com/user-attachments/assets/2470e708-6f3f-408f-8ff5-f25494786641" />

### Finding Review & Validation

<img width="1908" height="1002" alt="Review-Validation Asesor (SIMAMI)" src="https://github.com/user-attachments/assets/fb0df65e-5b3f-4fc6-8a9d-f188fcc6ebb9" />

### Assessee Dashboard

<img width="1908" height="1002" alt="Dashboard Asesi (SIMAMI)" src="https://github.com/user-attachments/assets/6c2a3c6e-323a-4441-bdf5-25a21c80df2d" />

### Audit Findings

<img width="1908" height="1002" alt="Temuan audit Asesi (SIMAMI)" src="https://github.com/user-attachments/assets/a1f4b610-741b-4624-9336-bcc372ce5dc9" />

## Features

### Authentication & Authorization

- User authentication
- Role-based access control
- Role-specific routes and permissions
- Access restriction for unauthorized users

### Audit Management

- Audit period management
- Audit creation and management
- Unit management
- Auditor and auditee assignment
- Audit progress monitoring
- Audit status tracking

### Finding Management

- Audit finding management
- Finding assignment to responsible users
- Follow-up action management
- Supporting evidence submission
- Open and closed finding tracking
- Finding review and validation

### Dashboard & Monitoring

- Role-specific dashboards
- Total audit monitoring
- Total finding monitoring
- Open and closed finding statistics
- Audit progress monitoring
- Recent audit and finding information
- Audit trend monitoring

### Data & Document Management

- Excel template support
- Excel data import
- Excel data export
- Final audit document management
- PDF document upload and download

### Notifications

- Audit-related notifications
- Notification status tracking
- Notification detail and read functionality

## Audit Workflow

SIMAMI supports an audit workflow from audit creation to finding
validation:

1. An auditor creates and manages an audit.
2. Audit findings are recorded in the system.
3. Findings are assigned to responsible users.
4. Responsible users provide follow-up actions and supporting evidence.
5. Auditors review the submitted follow-up.
6. Findings are validated and their status is updated.

This workflow provides a structured process for monitoring audit findings
and their follow-up activities.

## User Roles

The application provides different access levels for users involved
in the Internal Quality Audit process.

### Asesor (Auditor)

Manages audits and is responsible for reviewing and validating audit
findings and monitoring follow-up activities.

### KPS (Head of Study Program)

Participates in the audit process and manages relevant study program
data and findings.

### Dosen (Lecturer)

Handles audit findings and follow-up actions related to their
responsibilities.

### Teknisi (Technician)

Handles relevant audit findings and provides follow-up actions
when required.

### Admin Prodi (Program Study Administrator)

Supports the management and monitoring of audit-related activities
within the study program.

## Tech Stack

### Backend

- PHP 8.2
- Laravel 12
- Laravel Breeze
- Livewire

### Frontend

- Blade
- HTML
- CSS
- Tailwind CSS 4
- JavaScript
- Alpine.js
- Vite

### Database

- MySQL

### Libraries

- Maatwebsite Excel
- Laravel DomPDF

### Development Tools

- Git
- GitHub

## My Contribution

### Mukhammad Nur Fajrin — Web Application Development

Responsible for the main technical development of the application,
including:

- Designing the application structure and database relationships
- Developing backend logic using PHP and Laravel
- Implementing authentication and role-based access control
- Developing audit management features
- Developing audit finding and follow-up features
- Implementing finding review and validation workflows
- Developing role-specific dashboards
- Implementing audit progress and status monitoring
- Implementing Excel import and export functionality
- Implementing PDF document handling
- Developing frontend interfaces using Blade and Tailwind CSS
- Implementing frontend interactions using JavaScript and Alpine.js
- Testing and debugging the application

### Project Collaboration

**Raihan Tsaqif Athazaky**

Contributed through system discussions and feedback regarding feature
design and implementation decisions, as well as collaboration on
project documentation and presentation.

## Dummy Data

All data included in this repository is dummy data created for
development, testing, demonstration, and portfolio purposes.

The repository does not contain real student, lecturer, auditor,
or institutional data.

## Project Status

This project was developed as an academic final project and is
presented as part of a web development portfolio.

## Developer

**Mukhammad Nur Fajrin**  
Diploma III in Information Technology  
Politeknik Negeri Malang PSDKU Lumajang

- LinkedIn: https://www.linkedin.com/in/mukhammad-nur-fajrin-648659426/
