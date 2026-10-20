# MNP-RSP-Proposal-Management-System
A Django-based MNP and RSP Proposal Management System for proposal tracking, status-based listings, search and filtering, workflow management, and efficient data handling through a web-based interface.
# MNP & RSP Proposal Management System

## Overview

The **MNP & RSP Proposal Management System** is a web-based application developed using Django to support proposal management across both MNP and RSP modules. It provides a structured interface for accessing and tracking proposals, organizing records, and managing proposal-related workflows.

## Modules

### 1. MNP Module
- Supports proposal-related management within the MNP module.
- Provides access to relevant proposal records and workflows implemented in the application.
- Helps organize and track proposal information.

### 2. RSP Module
- Provides proposal listing and status-based tracking.
- Supports search, filtering, and sorting of proposal records.
- Includes financial-year and zone filtering where available.
- Uses server-side pagination to manage large datasets efficiently.

## Key Features

- Combined MNP and RSP proposal management.
- Web-based interface for accessing proposal records.
- Status-based proposal listings.
- Search, filtering, and sorting.
- Server-side pagination for supported listings.
- AJAX-based data retrieval where implemented.
- Proposal workflow tracking.
- Export and print options where supported by the interface.

## Technology Stack

- **Backend:** Python, Django
- **Frontend:** HTML, CSS, JavaScript
- **Libraries:** jQuery and DataTables
- **Data Communication:** AJAX and JSON
- **Database:** Configured project database

## Project Structure

The application contains Django views, templates, and supporting frontend and backend components for the MNP and RSP modules. The exact structure may vary depending on the project configuration.

## Getting Started

### Prerequisites

- Python
- pip
- Git (optional when uploading files directly through the GitHub website)
- The database and configuration required by the application

### Setup

1. Clone the repository:

   ```bash
   git clone <YOUR_REPOSITORY_URL>
   ```

2. Navigate to the project directory:

   ```bash
   cd MNP_RSP_dev
   ```

3. Create a virtual environment:

   ```bash
   python -m venv venv
   ```

4. Activate it on Windows:

   ```bash
   venv\Scripts\activate
   ```

5. Install dependencies if `requirements.txt` is available:

   ```bash
   pip install -r requirements.txt
   ```

6. Configure the required database settings and environment variables.

7. Apply migrations:

   ```bash
   python manage.py migrate
   ```

8. Run the development server:

   ```bash
   python manage.py runserver
   ```

Open the local development URL shown in the terminal to access the application.

## Future Enhancements

- Further optimize proposal listing and database queries.
- Improve performance for large datasets.
- Expand automated testing and error handling.
- Enhance technical documentation for the MNP and RSP workflows.

## Author

**Damini**  
Computer Science Engineering

## Disclaimer

This project should be shared only in accordance with the applicable organization and project-owner permissions. Never commit passwords, API keys, environment files, confidential documents, or sensitive production data.
