Car Wash SaaS - Subscription & Management System (Backend) 🚗
This is the backend repository for a production-ready Car Wash Subscription SaaS. The project was successfully revitalized and optimized to handle complex subscription workflows, secure payments, and a unique QR-based service redemption system.

🌟 Project Overview
Originally a legacy project with critical errors, I was commissioned to overhaul the system architecture. My work involved stabilizing the backend logic, migrating the infrastructure to a cloud-based database, and implementing a secure, automated system for managing customer car wash packages.

🚀 Key Features
Secure Authentication: Multi-provider login support using Apple Sign-In, Google Auth, and Firebase Admin.

Subscription Management: Automated handling of car wash packages with logic to track and deduct remaining washes.

QR Code Integration: Dynamic generation of QR codes for users; operators can scan these codes to verify subscriptions and update the database instantly.

Automated Scheduling: Background tasks managed via Node-Cron for system maintenance and subscription checks.

Cloud Database: Robust data persistence and schema management using MongoDB and Mongoose.

Communication: Integrated Twilio for SMS notifications and alerts.

🛠 Tech Stack
Runtime: Node.js

Framework: Express.js (v5.1.0)

Database: MongoDB via Mongoose

Security: JWT (JSON Web Tokens) & BcryptJS

Integrations: Firebase Admin, Google Auth, Apple Sign-In, Twilio, QRCode API

Deployment: Vercel

📖 API Documentation
The API is fully documented to ensure seamless integration with frontend applications. You can explore the detailed endpoints, request/response examples, and authentication requirements here:

🔗 View Postman Documentation

🔧 Installation & Setup
Clone the repository:

Bash
git clone https://github.com/MousaSalib/Paypass.git
Install dependencies:

Bash
npm install
Environment Variables:
Create a .env file and add your credentials (MongoDB URI, Firebase Keys, Twilio SID, etc.).

Run in development mode:

Bash
npm run dev
📜 License
Distributed under the ISC License.
