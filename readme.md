Frontend

React.js

Tailwind CSS

React Router

Chart library (Recharts / Chart.js)

Backend

Express.js (Node)

Python microservice (later) for:

NLP (policy summarization)

Case text analysis

REST APIs

Database

MongoDB (primary)

Mongoose ODM

Auth

JWT (access + refresh)

Role-based access control

Deployment

Frontend → Vercel / Netlify

Backend → Render / Railway

Python service → Render

DB → MongoDB Atlas

🧱 MODULE BREAKDOWN (VERY IMPORTANT)
1️⃣ Citizen Policy Tracker

Features

Browse policies by:

Government

Ministry

Year

Simple-language summaries

Status: Proposed / Active / Completed

Public reactions (upvotes, comments)

Analytics dashboard

Database entities

Policy

Ministry

Politician

Vote / Comment

2️⃣ Court Case Status Tracker

Features

Search cases by:

Case number

Party name

Case timeline (hearings, orders)

Bookmark cases

Email notifications

⚠️ For capstone safety:
Start with manually seeded data or mock court data
(you can later explain scraping as a future enhancement).

Database entities

Case

Court

Hearing

UserCaseBookmark

3️⃣ Online Legal Aid Platform

Features

Legal topic explainers (IPC, cyber law, consumer law)

Lawyer onboarding

Case submission

Appointment scheduling

Secure messaging

Roles

Citizen

Lawyer

Admin

Database entities

LawyerProfile

LegalQuery

Appointment

Message

🧑‍💻 USER ROLES (EXAMINERS LOVE THIS)
Role	Permissions
Guest	View policies & articles
Citizen	Track cases, comment, book lawyer
Lawyer	Respond to cases, manage profile
Admin	Verify lawyers, approve content
🗂️ PROJECT FOLDER STRUCTURE
Backend
backend/
├── src/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── services/
│   ├── utils/
│   └── app.js
├── server.js
├── .env
└── package.json

Frontend
frontend/
├── src/
│   ├── pages/
│   ├── components/
│   ├── layouts/
│   ├── services/
│   ├── context/
│   └── App.jsx
├── tailwind.config.js
└── package.json

Python Microservice (later)
ai-service/
├── app.py
├── requirements.txt
└── services/

🧪 MVP FIRST (DO THIS OR YOU’LL BURN OUT)
PHASE 1 – MUST HAVE

✔ Authentication
✔ Policy tracker (basic CRUD + UI)
✔ Case tracker (search + timeline)
✔ Legal aid request form
✔ Deployment

PHASE 2 – NICE TO HAVE

Charts & analytics

Email notifications

Lawyer chat

Python NLP summarization

PHASE 3 – FLEX

AI policy summaries

Case outcome prediction (demo only)

Multilingual support

🛡️ LEGAL & ETHICAL DISCLAIMERS (IMPORTANT)

Add this everywhere:

“This platform is for informational purposes only and does not constitute legal advice.”

This protects your project academically and professionally.

🎓 WHY THIS IS A TOP-TIER CAPSTONE

Multi-module system

Real social impact

Full-stack + microservices

Auth + RBAC

Scalable architecture

Deployable & demo-ready

Honestly?
This is interview-level impressive.

NEXT STEP (VERY IMPORTANT)

If you want, I’ll walk you step-by-step like a mentor.

👉 Reply with ONE of these:

“Design DB schemas first”

“Set up backend step-by-step”

“Frontend routing & UI plan”

“MVP roadmap with weekly timeline”

We’ll build this clean, not rushed 💪