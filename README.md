# PrepPilot AI 🚀

PrepPilot AI is an AI-powered interview preparation platform that helps job seekers evaluate their profiles against job descriptions, identify skill gaps, generate interview questions, and create tailored resumes.

The application leverages Google Gemini AI to analyze resumes and job requirements, providing personalized interview preparation plans and actionable insights.

---

## Features

### AI-Powered Interview Analysis

* Resume and Job Description matching
* Match score calculation (0-100)
* Technical interview question generation
* Behavioral interview question generation
* Skill gap identification
* Personalized preparation roadmap

### Resume Intelligence

* Resume PDF upload and parsing
* ATS-friendly resume generation
* Job-specific resume customization
* PDF export functionality

### User Management

* User Registration & Login
* JWT-based Authentication
* Secure Cookie Sessions
* Protected Routes

### Report Management

* Save interview reports
* View previous reports
* Access generated preparation plans
* Resume download support

---

## Tech Stack

### Frontend

* React.js
* Vite
* React Router
* Axios
* SCSS

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* Multer
* PDF Parse
* Puppeteer

### AI Integration

* Google Gemini AI

---

## Project Architecture

Resume Upload
↓
Resume Parsing
↓
Google Gemini AI
↓
Interview Analysis
├── Match Score
├── Technical Questions
├── Behavioral Questions
├── Skill Gaps
└── Preparation Plan
↓
MongoDB Storage
↓
User Dashboard

---

## Installation

### Clone Repository

```bash
git clone <repository-url>
cd PrepPilot-AI
```

### Backend Setup

```bash
cd Backend
npm install
```

Create a `.env` file:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GOOGLE_GENAI_API_KEY=your_gemini_api_key
```

Start backend:

```bash
npm run dev
```

### Frontend Setup

```bash
cd Frontend
npm install
npm run dev
```

Frontend will run on:

```text
http://localhost:5173
```

Backend will run on:

```text
http://localhost:3000
```

---

## Environment Variables

| Variable             | Description                       |
| -------------------- | --------------------------------- |
| MONGO_URI            | MongoDB Connection String         |
| JWT_SECRET           | Secret key for JWT authentication |
| GOOGLE_GENAI_API_KEY | Google Gemini API Key             |

---
