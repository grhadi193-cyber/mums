# MUMS

MUMS is a role-based student advising and appointment management platform built for university counseling workflows. It helps advisors manage students, schedule sessions, track appointment requests, review session history, and keep follow-up information organized in one place.

## Why this project exists

Academic advising often relies on scattered notes, manual tracking, and disconnected communication tools. MUMS brings those workflows into a single structured interface so advisors can focus more on students and less on administration.

The project is designed to be lightweight, practical, and easy to understand. It is especially useful for teams that need a simple system to manage advising sessions, availability, and student records without introducing unnecessary complexity.

## What it does

- Separate advisor and student experiences.
- Advisor dashboards for student monitoring and workflow management.
- Student dashboards for appointment and session access.
- Availability settings for advisors.
- Appointment request and approval flow.
- Session entry and follow-up tracking.
- Persistent client-side storage for demo and prototype usage.

## Why Claude helped build this project

Claude was used as a development partner during the build process to speed up iteration and improve code quality. It helped with React component structure, route organization, state management patterns, UI flow refinement, and documentation writing.

As an independent builder, having Claude available made it easier to move quickly from idea to working software. That support is especially valuable when building a project that needs to stay clean, maintainable, and practical over time.

## Who benefits

MUMS is useful for university advising environments where staff need a simple and organized way to manage student sessions, appointment coordination, and follow-up records. It can also help students by making the advising process more transparent and easier to access.

This kind of tool is valuable in institutions that want a modern workflow without depending on heavy infrastructure or fragmented manual processes.

## Current status

This repository is a functional MVP and an active prototype. It focuses on the core advising and scheduling workflows and is intended to evolve into a more complete platform over time.

## Tech stack

- React
- React Router
- Vite
- Tailwind CSS
- Local storage for persistence

## Project structure

- `src/components/Advisor` — advisor-facing features.
- `src/components/Student` — student-facing features.
- `src/components/Shared` — shared UI and route protection.
- `src/contexts` — authentication and application state.
- `src/utils/mockData.js` — sample data and constants.

## Getting started

```bash
npm install
npm run dev
```

## Notes

This project currently uses client-side storage and mock data for rapid prototyping. A production version would add secure authentication, a backend API, and a real database.

## Future improvements

- Secure authentication.
- Backend API integration.
- Database persistence.
- Notifications and reminders.
- Calendar synchronization.
- Analytics and reporting.
- Role permissions and audit logs.

## License

Add your preferred license here.

## Contact

If you want to contribute or collaborate, please open an issue or pull request.
