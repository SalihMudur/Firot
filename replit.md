# Generator Service Center Task Management System

## Project Overview
An authenticated task management system for generator service center admins to assign repair tasks to field workers. Admins can create accounts for workers and assign specific tasks like repairing electronic equipment at various locations.

## Key Features
- Admin authentication system
- Admin can create login credentials for workers
- Task assignment and management
- Worker task tracking
- Location-based repair assignments

## User Preferences
- Simple, everyday language in UI
- Focus on practical task management workflow
- Mobile-friendly for field workers

## Project Architecture
- Frontend: React with Vite, Wouter routing, TanStack Query
- Backend: Express.js with PostgreSQL database
- Database: PostgreSQL with Drizzle ORM
- Styling: Tailwind CSS + shadcn/ui components
- Authentication: Session-based auth

## Recent Changes
- Initial project setup (2025-08-21)
- Created authentication system with admin login
- Implemented user management for creating worker accounts
- Built task assignment system
- Migrated from in-memory storage to PostgreSQL database (2025-08-21)

## Data Models
- Users: Admin and worker accounts with role-based access
- Tasks: Repair assignments with location, equipment details, and status
- Sessions: Authentication management