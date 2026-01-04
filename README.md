📌 Problem Statement

Develop a transparent, AI-driven National Grievance Redressal Portal that automates complaint categorization, priority assessment, and real-time tracking to improve citizen–government communication and accountability.

🏷️ Project Details

Project Name:
National Grievance Portal

Team Name:
ByteQuest

Deployed Link:
Deployed Link Coming Soon / [Insert Link if Deployed]

2-Minute Demonstration Video:
https://drive.google.com/file/d/18y9mMl5JG7jzAZJm6BnCYJw5oEtGThJo/view?usp=drive_link

PPT Link:
https://drive.google.com/file/d/19N-j7ogyM3la1G3vwzAlpVxei1zPnqIc/view?usp=sharing

✅ Project Overview

The National Grievance Portal is a full-stack MERN-based web application integrated with Google Gemini AI. It enables citizens to submit grievances that are automatically analyzed by AI to determine urgency and category.

A secure Admin Dashboard allows government officials to monitor, analyze, and manage grievances in real time, ensuring faster resolution and improved transparency.

✨ Key Features

AI-Automated Analysis
Uses Gemini Flash to generate concise one-line summaries and automatically categorize grievances (e.g., Roads, Water, Electricity).

Real-Time Admin Dashboard
A high-fidelity dashboard synchronized via Port 5000 for live grievance monitoring and analytics.

Grievance Status Tracking
Citizens can track the complete lifecycle of their grievance using a unique MongoDB ObjectID.

Fail-Safe Demo Mode
Built-in offline data handling ensures the UI remains functional during network disruptions or demo conditions.

⚙️ Setup & Installation Instructions
Backend (Server)

Navigate to the server folder.

Install dependencies:

npm install


Create a .env file and add the following variables:

MONGO_URL

GEMINI_API_KEY

Populate the database using the seed script:

node seed.js


Start the server (runs on Port 5000):

node index.js

Frontend (Client)

Navigate to the client folder.

Install dependencies:

npm install


Start the frontend application:

npm run dev


Access the admin panel at:

/admin-dashboard

🚀 Usage Instructions

File a Grievance
Enter your name and a brief issue description (e.g., “Dirty water issue”).

AI Processing
The system automatically analyzes the complaint, assigning a priority level and category.

Admin Review
Log in using admin credentials (admin@gov.in / admin321) to view summaries, analytics, and grievance status.

Track Grievance
Use the generated grievance ID to track status updates in real time.

🖼️ Relevant Screenshots

Admin Dashboard: Displays AI-generated summaries, grievance categories, and status badges.

System Connectivity: Confirms real-time backend integration via Port 5000.
