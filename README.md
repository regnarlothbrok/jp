# Job Portal

A full-featured job portal application built with the MERN (MongoDB, Express.js, React.js, Node.js) stack that allows users to search for jobs relevant to their skillset and experience, providing a tailored job search experience.

## Screenshots

### Authentication Pages
![image](https://github.com/user-attachments/assets/96fb3f2a-6ac7-4129-9189-89c7629e28dd)
![image](https://github.com/user-attachments/assets/0ba8aa11-7b40-4a55-8529-06b31a686a6a)


- Login page screenshot
- Signup page screenshot

### User Dashboard
![image](https://github.com/user-attachments/assets/ad235f47-c1cd-4bad-904a-cd6291374ebc)


- Home page/dashboard screenshot
- Job search interface
- Job listings view

### Job Management
![image](https://github.com/user-attachments/assets/cfff904f-2086-4392-822b-ca0ac2b05775)

- Job posting interface
- Job details view
- Application submission form

### Company Features
![image](https://github.com/user-attachments/assets/2008f662-2d11-4a38-93f3-5b97801381c9)

- Company profile page
- Company dashboard
- Company job listings

### Admin Panel
![image](https://github.com/user-attachments/assets/72566325-0dc1-4f85-a0bf-707eb7b0adb8)
![image](https://github.com/user-attachments/assets/182540b7-4235-4187-9616-0a5ce33a06bb)


- Admin dashboard
- User management interface
- Company management interface

## Features

- User authentication (Login/Signup)
- Job search and browsing
- Company profiles and management
- Job posting and management
- Admin dashboard
- Protected routes for authenticated users
- Responsive UI using Shadcn UI components

## Tech Stack

- **Frontend**: React.js, Vite, Shadcn UI
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Additional Tools**: React Router DOM

## Project Structure

```
job-portal/
├── frontend/               # React frontend application
│   ├── src/
│   │   ├── components/    # React components
│   │   ├── assets/       # Static assets
│   │   └── App.jsx       # Main application component
│   └── package.json
│
└── backend/               # Node.js backend application
    ├── controllers/      # Route controllers
    ├── models/          # Database models
    ├── routes/          # API routes
    ├── middlewares/     # Custom middlewares
    └── package.json
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB installed and running locally
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone [your-repository-url]
cd job-portal
```

2. Install frontend dependencies:
```bash
cd frontend
npm install
```

3. Install backend dependencies:
```bash
cd backend
npm install
```

### Running the Application

1. Start the frontend development server:
```bash
cd frontend
npm run dev
```
The frontend will be available at `http://localhost:5173`

2. Start the backend server:
```bash
cd backend
npm run dev
```
The backend API will be available at `http://localhost:8000`

## API Endpoints

The application uses the following API endpoints:

- User API: `http://localhost:8000/api/v1/user`
- Job API: `http://localhost:8000/api/v1/job`
- Application API: `http://localhost:8000/api/v1/application`
- Company API: `http://localhost:8000/api/v1/company`

## Available Scripts

In both the frontend and backend directories, you can run:

- `npm run dev`: Runs the application in development mode
- `npm run build`: Builds the application for production
- `npm start`: Runs the built application

## Environment Variables

Create a `.env` file in the backend directory with the following variables:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=8000
```
