Passport Automation System

A Flask-based web application designed to digitize internal passport application processes and manage the entire workflow securely from submission to final decision.

Live Demo:
https://pasaport-otomasyonu-pro-final.onrender.com

⸻

Project Overview

This project focuses on building a structured and secure web system that replaces manual passport application handling with an automated, role-based workflow. It simulates a real-world internal application management system with user and administrator roles.

The main goal was to gain hands-on experience in web development, workflow automation, authentication, and secure data handling.

⸻

Features
	•	Role-based authentication (User / Admin)
	•	Secure user login and session management
	•	Create, submit, and track passport applications
	•	Admin panel for reviewing applications
	•	Approve / reject functionality with review notes
	•	Email notifications using SMTP
	•	Basic filtering and reporting for applications

⸻

Security & Data Handling Considerations
	•	Separation of user and admin privileges
	•	Input validation to reduce invalid or malformed data
	•	Controlled access to application review actions
	•	Structured handling of sensitive user-submitted information
	•	Awareness of common web security practices in Flask-based systems

⸻

Technologies Used
	•	Python
	•	Flask
	•	HTML / CSS
	•	SMTP (Email notifications)
	•	SQLite
	•	Git & GitHub

⸻

Quick Start

	python -m venv .venv
	.\.venv\Scripts\activate # Windows
	pip install -r requirements.txt
	python app.py

⸻

Alternatively:

	set FLASK_APP=app.py
	flask run

⸻

What I Learned
	•	Designing end-to-end workflows for real-world applications
	•	Implementing role-based access control
	•	Building backend logic with Flask
	•	Handling user data responsibly and securely
	•	Understanding how security concepts apply in web applications


