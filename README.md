

```markdown
# Notes App - Full Stack Application

A modern full-stack notes application with user authentication and admin functionality.

## Overview

This project consists of:
- **Frontend**: Next.js 14 + TypeScript + Tailwind CSS
- **Backend**: FastAPI + Python + JWT Authentication
- **Features**: User management, notes CRUD, admin dashboard

## Quick Start

### Prerequisites

- Node.js 18+
- Python 3.8+
- npm/yarn and pip

### Installation

1. **Clone/Setup the project**:

Setup Backend:

cd backend
pip install -r requirements.txt
python main.py

Setup Frontend:

cd ../frontend
npm install
npm run dev

Access the Application:
Frontend: http://localhost:3000
Backend API: http://localhost:8000
API Docs: http://localhost:8000/docs


Admin Setup Guide
Step 1: Create Admin User
Register a new user through the frontend
Stop the backend server
Open 
backend/database.json
Find your user and change "role": "user" to "role": "admin"
Restart the backend server
Step 2: Test Admin Features
Login with your admin credentials
You should see a purple "Admin Dashboard" button
Access the admin dashboard to manage all users' notes
Project Structure

notes-app/
├── frontend/              # Next.js frontend
│   ├── src/
│   │   ├── app/         # App router pages
│   │   ├── lib/         # API client
│   │   └── components/  # React components
│   └── README.md        # Frontend documentation
├── backend/              # FastAPI backend
│   ├── models/          # Pydantic models
│   ├── routers/         # API endpoints
│   ├── database/        # Database layer
│   └── README.md        # Backend documentation
└── README.md            # This file

Features
User Features
✅ User registration and login
✅ Create, read, update, delete notes
✅ Persistent authentication
✅ Responsive design
Admin Features
✅ Admin dashboard
✅ Manage all users' notes
✅ Edit/delete any note
✅ User management
✅ Role-based access control
API Documentation
Full API documentation is available at:

Swagger UI: http://localhost:8000/docs
ReDoc: http://localhost:8000/redoc
Development
Frontend Development

cd frontend
npm run dev

Backend Development

cd backend
python main.py

Testing Admin Functionality
Create Admin User:
Register normally → Update role in database → Restart backend
Login as Admin:
Use admin credentials → See admin dashboard button
Admin Operations:
View all notes from all users
Edit any note
Delete any note
Troubleshooting
Common Issues
Admin button not showing:
Verify user role is "admin" in database
Restart backend after role change
Check browser console for errors
Authentication issues:
Ensure backend is running on port 8000
Check CORS configuration
Verify JWT token in localStorage
Database issues:
Check 
database.json
 syntax
Ensure unique UUIDs
Verify file permissions
Contributing
Fork the repository
Create a feature branch
Make your changes
Test thoroughly
Submit a pull request
License
MIT License


   ```bash
   # Navigate to project directory
   cd d:/task/new
