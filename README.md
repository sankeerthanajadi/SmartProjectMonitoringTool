Smart Project Monitoring Tool
Overview

The Smart Project Monitoring Tool is an AI-powered web application designed to streamline and automate the monitoring of academic projects. It enhances communication between students, guides, and coordinators while enabling efficient tracking, evaluation, and feedback.

Features
Project Submission – Upload project details and abstracts
AI-Based Review – Automated abstract evaluation using AI
Role-Based Access – Separate dashboards for Students, Guides, and Coordinators
Real-Time Notifications – Instant updates and alerts
Progress Tracking – Monitor project status and milestones
Guide Feedback System – Manual review and comments
Report Generation – Structured and automated reports
Tech Stack
Frontend
React.js
HTML
CSS
JavaScript
Backend
Node.js
AI Module
Flask (Python)
Gemini API
Database
PostgreSQL (Neon DB)
System Architecture
React.js – User Interface (Role-based dashboards)
Node.js – Business logic and API handling
Flask (Python) – AI-based abstract analysis
PostgreSQL – Data storage (users, projects, reviews, etc.)
Database Design

The system uses a relational database with the following key tables:

users – Stores user details
projects – Project information
project_groups – Group details
group_members – Mapping users to groups
submissions – Uploaded abstracts/files
ai_reviews – AI-generated feedback
guide_reviews – Manual reviews
notifications – Alerts and updates
project_comments – Discussions
How It Works
Users upload project details (Excel/File)
Data is stored in the database
AI module analyzes abstracts and provides feedback
Guides review and add comments
Notifications are sent to users
Reports are generated for tracking progress
Installation and Setup
Prerequisites
Node.js
Java (JDK 11+)
Python
PostgreSQL
AI Module Setup
cd ai-module
pip install -r requirements.txt
python app.py
Database Setup
Configure PostgreSQL (Neon DB or local)
Update credentials in application.properties
API Endpoints (Examples)
/api/excel/upload – Upload project data
/api/projects – Manage projects
/api/reviews – AI and guide reviews
Advantages
Reduces manual effort
Improves efficiency and accuracy
Enhances communication
Provides real-time updates
Scalable and easy to maintain
Future Enhancements
Enhanced Domain-Specific AI Models: Improve accuracy using domain-specific and multilingual datasets
Offline and Hybrid Deployment Support: Reduce dependency on internet connectivity
User-Friendly Onboarding: Add tutorials and guided setup
Advanced Plagiarism Detection: Enable deeper and more accurate checks
Configurable Rule Engine: Replace hardcoded rules with flexible configurations
Continuous Learning: Improve AI using user feedback
Conclusion

This project provides a smart, scalable, and efficient solution for managing academic projects by combining automation, AI, and structured workflows.

Contributors
S Madhumitha
V Bhavana Kruthi
D Asritha
J Sai Sankeerthana
License

This project is developed for academic purposes.
