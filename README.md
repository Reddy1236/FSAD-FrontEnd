# Student Peer Review Frontend

Frontend for the Student Peer Review and Collaboration Platform, built with React and Vite.

## Features

### Student workflow
- View project and review statistics from a dashboard
- Upload project details and supporting files
- Submit peer reviews with ratings and structured feedback
- Track recent activity and notifications
- Export reports

### Teacher workflow
- View platform analytics and submission trends
- Browse and manage student projects
- Assign reviewers
- Approve, reject, or request improvements

### UI highlights
- Split-screen login page
- Role-based navigation
- Math captcha on login
- Light and dark theme toggle
- Responsive layout for desktop and mobile

## Tech Stack
- React 19
- Vite 7
- React Router 7
- Tailwind CSS 4
- Recharts
- Lucide React

## Getting Started

### Prerequisites
- Node.js 18 or later
- npm 9 or later

### Run locally

```bash
npm install
npm run dev
```

The app starts on [http://localhost:5173](http://localhost:5173).

## Environment

Create a `.env` file if you want to point the frontend to a deployed backend:

```env
VITE_API_BASE_URL=http://localhost:8080/api
```

If `VITE_API_BASE_URL` is not set:
- development mode uses `http://localhost:8080/api`
- production build falls back to same-origin `/api`

## Demo Login

| Role | Email | Password |
|------|-------|----------|
| Student | `student@demo.com` | `student123` |
| Teacher | `teacher@demo.com` | `teacher123` |

Complete the math captcha shown on the login form, then sign in.

## Project Structure

- `src/` contains pages, layouts, reusable components, context, config, and utilities
- `public/` contains static assets
- `docs/DOCUMENTATION.md` contains wireframes, routing notes, data model ideas, and API planning

## Available Scripts

```bash
npm run dev
npm run build
npm run preview
npm run lint
```
