# Employee Skills Management System

A comprehensive web-based system for managing employee skills, projects, and resource allocation.

## Features

- User Authentication (Email/Password)
- Employee Skills Management
  - Add/Update skills with proficiency levels
  - Track certifications and experience
- Project Management
  - Track active projects
  - Skill requirements
  - Team size planning
- Role-based Access Control
  - Admin
  - Manager
  - Employee

## Tech Stack

- Frontend: HTML, JavaScript, Tailwind CSS
- Backend: Supabase
  - Authentication
  - Database
  - Row Level Security

## Setup

1. Clone the repository:
```bash
git clone https://github.com/your-username/employee-skills-management.git
cd employee-skills-management
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory with your Supabase credentials:
```env
VITE_SUPABASE_URL=your-project-url
VITE_SUPABASE_ANON_KEY=your-anon-key
```

4. Start the development server:
```bash
npm run dev
```

## Database Schema

The application uses the following main tables:
- profiles: User profiles and roles
- skills: Skill definitions
- employee_skills: Employee-skill relationships
- projects: Project information
- project_skills: Project skill requirements
- project_assignments: Project team assignments

## Security

- Row Level Security (RLS) enabled on all tables
- Role-based access control
- Secure authentication flow

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.