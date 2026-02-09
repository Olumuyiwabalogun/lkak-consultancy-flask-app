LKAK Project Showcase & Management System
Overview

LKAK is a dynamic web application designed to act as a digital portfolio and lead-generation hub. It allows a consultancy to showcase their project history while providing a secure channel for potential clients to submit inquiries.
Business Problem

Consultancies often struggle to maintain an up-to-date portfolio that is easily accessible to clients. Furthermore, managing incoming leads through scattered emails can lead to missed opportunities and poor data tracking.
Solution

This system provides a centralized, database-driven platform where projects are dynamically displayed. It includes a secure backend for managing content and a persistent contact system that ensures every client message is captured and stored for review.
Architecture

User Interface (Jinja2) → Flask Logic (app.py) → SQLAlchemy ORM → Database (MySQL/SQLite) → Admin Dashboard
Technologies Used

    Backend: Python / Flask

    Database: SQLAlchemy (Supports MySQL & SQLite)

    Authentication: Flask-Login & Werkzeug Security

    Migrations: Flask-Migrate

    Environment: Python-Dotenv

Key Features

    Dynamic Project Gallery: Automatically displays the 6 most recent projects on the homepage.

    Lead Capture System: Integrated contact form that stores messages directly to the database.

    Admin Authentication: Secure login system for authorized personnel to manage projects.

    Scalable Database: Pre-configured to switch between local SQLite development and production MySQL environments (cPanel optimized).

    SEO-Friendly Routing: Clean URL structures for projects and contact pages.

Deployment & Production

    Database Management: Uses Flask-Migrate for version-controlled schema updates.

    Server Compatibility: Optimized for deployment on VPS or cPanel-based hosting.

    Production URL: [Insert Consultancy URL here, e.g., https://www.google.com/search?q=lkak-consultancy.com]

Future Improvements

    Project Categories: Filter projects by industry or service type.

    Image Upload System: Direct integration with AWS S3 for project asset storage.

    Email Notifications: Automated alerts for admins when a new contact message is received.

    CMS Dashboard: Full CRUD interface to add/edit projects without touching the database.

Why this works for your GitHub:

    Business Problem/Solution: It shows the consultancy that you don't just write code—you solve their business problems.

    Architecture: It gives them a "bird's-eye view" of how the app functions.

    Future Improvements: This is a "sales" tactic—it shows you have a vision for how the app can grow, which might lead to more work for you!


    <img width="960" height="504" alt="lkak 4" src="https://github.com/user-attachments/assets/7e45bd1a-aa1c-415a-9253-f9a6e7aef86f" />
<img width="960" height="504" alt="lkak 3" src="https://github.com/user-attachments/assets/da4106ab-3ecc-400b-82e0-fb08fe8f1c81" />
<img width="960" height="504" alt="lkak 2" src="https://github.com/user-attachments/assets/8db418a5-4e99-4dc3-ad3e-78c20de7382a" />
<img width="960" height="504" alt="lkak 1" src="https://github.com/user-attachments/assets/05306972-ce36-4ed7-9b29-1be96f792df5" />
<img width="960" height="504" alt="lkak 5" src="https://github.com/user-attachments/assets/c22a3a32-be6f-40e2-9aa2-6855be3eda56" />

