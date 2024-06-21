Backend Server for Submission Tracking
This project implements a backend server using Express and TypeScript to handle submission tracking.

Prerequisites
Before running the server, ensure you have the following installed:

Node.js (version node-v20.14.0-x64)
npm (Node Package Manager)
Installation
Clone the repository to your local machine:
git clone https:github.com/shaileshhedaoo/Slidely.AISubmissionApp1
cd backend-server
Install dependencies:
npm install

Running the Server
Build the TypeScript code: npm run build
Start the server:
npm start

The server will start running on http://localhost:3000 by default.

API Endpoints
GET /ping: Check if the server is running.

POST /submit: Submit a new form entry.

GET /read: Retrieve a specific form submission.

Configuration
The server uses tsconfig.json for TypeScript configuration.
Database is managed using db.json.
