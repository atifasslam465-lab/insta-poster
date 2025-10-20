# InstaQueue

A Multi-Account Instagram Scheduling Web App

## Project Overview

InstaQueue is a secure, reliable, and user-friendly web application that enables users to bulk-schedule and automate Instagram photo posts for multiple accounts.

## Features

- Multi-account management
- Bulk scheduling via CSV import
- Rich post composition (captions, user tagging)
- Post management (edit, reorder, delete)
- Automated posting scheduler
- Notification center
- Light/Dark mode themes
- Data export functionality

## Project Structure

```
instagram-auto-poster/
├── frontend/          # React/Vite frontend application
├── backend/           # Node.js/Express backend API
├── README.md          # Project documentation
└── package.json       # Root package.json for project scripts
```

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB

### Installation

1. Clone the repository
2. Install frontend dependencies:
   ```
   cd frontend
   npm install
   ```
3. Install backend dependencies:
   ```
   cd backend
   npm install
   ```

### Running the Application

1. Start the backend server:
   ```
   cd backend
   npm run dev
   ```
2. Start the frontend development server:
   ```
   cd frontend
   npm run dev
   ```

Alternatively, from the root directory:
```bash
npm run dev
```

## Development

This project uses:
- Frontend: React with Vite
- Backend: Node.js with Express
- Database: MongoDB
- Instagram Integration: Instagram Graph API

## Documentation

For detailed information about the project, see:
- [Progress Summary](PROGRESS_SUMMARY.md)
- [Final Summary](FINAL_SUMMARY.md)
- [Full Documentation](DOCUMENTATION.md)
