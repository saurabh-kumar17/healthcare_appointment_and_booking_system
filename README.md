# Healthcare Appointment Booking & Management System

A full-stack MERN application for managing time-slot scheduling, doctor availability, and role-based workflows for patients, doctors, and system administrators.

## Tech Stack
- **Frontend:** React.js, Context API, Tailwind CSS, Vite
- **Backend:** Node.js, Express.js, REST API architecture
- **Database:** MongoDB, Mongoose ODM
- **Auth:** JWT (separate flows for patient / doctor / admin)
- **File storage:** Cloudinary (via Multer)

## Apps in this repo
- `frontend/` — patient-facing app (browse doctors, book/cancel appointments)
- `admin-portal/` — doctor + admin dashboard (manage appointments, add doctors, availability)
- `backend/` — shared REST API for all three roles

## Author
Built and maintained by **Saurabh Kumar** ([@saurabh-kumar17](https://github.com/saurabh-kumar17)).

## Getting Started
```bash
# backend
cd backend && npm install && npm run server

# frontend (patients)
cd frontend && npm install && npm run dev

# admin-portal (doctors/admin)
cd admin-portal && npm install && npm run dev
```
Each app needs its own `.env` file (Mongo URI, JWT secret, Cloudinary keys) — see `backend/config/` for what's required.
