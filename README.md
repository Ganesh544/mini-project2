# Project Monitoring System

## Overview
The Project Monitoring System is a web-based application designed to streamline project management, monitoring, and academic project supervision. The system enables administrators, faculty members, and project teams to efficiently manage project activities, track progress, monitor milestones, and maintain project-related information through a centralized platform.

This solution improves transparency, accountability, and communication throughout the project lifecycle.

## Key Features
- User authentication and role-based access
- Administrator dashboard
- Faculty management module
- Project progress monitoring
- Task and milestone tracking
- Project status updates
- Centralized data management
- Secure web-based access

## Modules
### Admin Module
- Manage users and system activities
- Monitor all project records
- Assign responsibilities
- Generate project reports

### Faculty Module
- Supervise assigned projects
- Review project progress
- Update project status
- Provide feedback and evaluation

## Technology Stack
- Python
- :contentReference[oaicite:3]{index=3}
- HTML
- CSS
- JavaScript
- Bootstrap
- SQLite / MySQL

## Project Architecture
The system follows the Model-View-Template (MVT) architecture provided by Django for scalable and maintainable development. Basic app configuration files for Admin and Faculty modules are included in the codebase. :contentReference[oaicite:4]{index=4} :contentReference[oaicite:5]{index=5} :contentReference[oaicite:6]{index=6}

## Installation

```bash
git clone <repository-url>
cd project-monitoring-system
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## Usage
Open the application in your browser:

http://127.0.0.1:8000

## Future Enhancements
- Student dashboard
- File/document uploads
- Email notifications
- Real-time project analytics
- Cloud deployment

## Author
Ganesh Kadari
