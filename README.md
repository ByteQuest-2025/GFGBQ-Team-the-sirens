Problem Statement
Developing a transparent, AI-driven National Grievance Redressal Portal that automates complaint categorization, priority assessment, and real-time tracking to enhance citizen-government communication.

Project Name
National Grievance Portal

Team Name
ByteQuest # Deployed Link Coming Soon / [Insert Link if deployed]

2-Minute Demonstration Video Link
[https://drive.google.com/file/d/1kq4mKz8_fsIBCvvLjdqo1oJ3ZZad2rIs/view?usp=sharing

PPT Link
[Insert Your PPT Link Here]

✅ Project Overview
The National Grievance Portal is a full-stack MERN application integrated with Google Gemini AI. It allows citizens to file complaints which are then processed by AI to determine urgency and category. The system features a secure Admin Dashboard for government officials to monitor and manage grievances in real-time.

Key Features:
AI-Automated Analysis: Uses Gemini Flash to generate 1-sentence summaries and categorize reports (e.g., Roads, Water, Electricity).

Real-Time Dashboard: A high-fidelity admin interface synchronized via Port 5000 for live data monitoring.

Status Tracking: Citizens can track the lifecycle of their grievance using unique MongoDB ObjectIDs.

Fail-Safe Demo Mode: Built-in offline data handling to ensure the UI remains functional during network interruptions.

✅ Setup & Installation Instructions
Backend (Server)
Navigate to the server folder.

Install dependencies: npm install.

Create a .env file with your MONGO_URL and GEMINI_API_KEY.

Run the seed script to populate the database: node seed.js.

Start the server: node index.js (Runs on Port 5000).

Frontend (Client)
Navigate to the client folder.

Install dependencies: npm install.

Start the application: npm run dev.

Access the dashboard at /admin-dashboard.

✅ Usage Instructions
File a Grievance: Enter your name and description (e.g., "Dirty water issue").

AI Processing: The system will automatically tag the priority and category.

Admin Review: Log in as admin (admin@gov.in / admin321) to view the analytics and summaries.

Track: Use the generated ID to check status updates in real-time.

✅ Relevant Screenshots

<img width="1318" height="972" alt="image" src="https://github.com/user-attachments/assets/3e1d334d-90e4-4544-b1fe-b90439b77979" />
<img width="1885" height="913" alt="image" src="https://github.com/user-attachments/assets/fb2cea8a-0a6c-4971-af18-828c2e5cf212" />
<img width="1017" height="841" alt="image" src="https://github.com/user-attachments/assets/a9f01c7e-3b0c-4b90-8712-7d0844632ee5" />

Admin Dashboard: Showing AI-summarized reports and status badges.

System Connectivity: Verified Port 5000 integration.
