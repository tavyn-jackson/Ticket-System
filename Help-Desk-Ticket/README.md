# Help Desk Ticket System

A Flask-based web application that allows users to create support tickets and view ticket status while allowing authenticated administrators to update ticket progress.

The project was created to demonstrate:

- Software Testing Lifecycle (STLC)
- System Testing
- Integration Testing
- End-to-End Testing
- Authentication Testing
- Database Validation
- Automated Testing using Pytest

## Technologies Used

- Python
- Flask
- SQLite
- HTML
- Pytest
- VS Code
- SQLite Viewer

## System Architecture

```text
User Browser
      ↓
Flask Application
      ↓
SQLite Database
      ↓
Updated Status Returned
      ↓
Browser Display
```

## Features

### User Functions

- Create support tickets
- View ticket information
- View ticket status

### Administrator Functions

- Login authentication
- View submitted tickets
- Update ticket status
- Logout functionality

- ## Application Workflow

### Ticket Creation Process

1. User opens Create Ticket page
2. User enters ticket details
3. Flask receives POST request
4. Data is inserted into SQLite database
5. User is redirected to ticket list
6. Ticket status displays as Open

### Ticket Status Update Process

1. Administrator logs in
2. Session is created
3. Admin accesses dashboard
4. Status is updated
5. SQLite database record is updated
6. User sees updated ticket status
