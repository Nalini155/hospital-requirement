CareFlow Intelligence

Hospital Resource Forecasting & Operations Intelligence System

CareFlow Intelligence is a full-stack web application that helps hospitals predict upcoming patient demand — admissions, bed occupancy, and ICU occupancy — so administrators can prepare resources in advance and avoid capacity overload.

⚠️ Disclaimer: This system provides capacity & operations risk signals only. It does not provide medical diagnosis or emergency predictions.

📌 Problem Statement

Hospitals often struggle to anticipate patient demand surges, leading to bed shortages, ICU overload, and understaffed departments. CareFlow Intelligence addresses this by combining historical hospital data with time-series forecasting to give administrators an early warning system for capacity planning.

✨ Features
Demand Forecasting — Predicts next 7-day patient admissions using time-series modeling, with confidence intervals
Resource Gap Analysis — Compares forecasted demand against available capacity (beds, ICU) and highlights shortages
Live Dashboard — Real-time occupancy percentages, forecast trend charts, and a resource gap table
Capacity Alerts — Automatic alerts when forecasted occupancy crosses safe thresholds
What-If Simulation — Test scenarios like "What if 15 beds become unavailable?" or "What if inflow increases by 20%?" and see the projected impact instantly
Role-Based Access:
Admin — Full dashboard, user management, system overview, activity logs, data management
Reception — Simplified view with the ability to update daily bed and ICU numbers
Secure Authentication — Email/password login and signup, with Google sign-in option
🧠 Tech Stack
Layer	Technology
Frontend	Next.js (React), Tailwind CSS, Recharts
Backend	FastAPI (Python)
Database	PostgreSQL / SQLite
Forecasting	Prophet / XGBoost (time-series ML)
Auth	JWT-based authentication
🖥️ Dashboard Overview
Today's Occupancy %
Forecasted Occupancy Trend (7/14/30 days)
Available Beds & ICU Beds
Expected Admissions
Resource Gap Table (Resource | Available | Forecast Need | Gap)
Department-wise breakdown (Emergency, ICU, General Ward, Pediatrics)
🚀 Getting Started
bash
# Clone the repository
git clone https://github.com/Nalini155/hospital-requirement.git
cd hospital-requirement

# Install dependencies
npm install

# Run the development server
npm run dev

Open http://localhost:3000 in your browser.

Demo Admin Login:

Email: admin@careflow.health
Password: careflow123
📂 Project Structure
hospital-requirement/
├── src/              # Application source code
├── db/               # Database schema & seed scripts
├── prisma/           # Prisma ORM configuration
├── scripts/          # Utility & setup scripts
├── public/           # Static assets
├── tests/            # Test files
└── mini-services/    # Supporting microservices
👩‍💻 Author

Nalini Krishna Priya B.Tech CSE, 2nd Year

📄 License

This project is developed for academic/educational purposes.
