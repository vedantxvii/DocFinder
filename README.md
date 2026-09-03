 # DocFinder – Lost & Found Document Recovery Portal

A modern full-stack web application that helps users **report, search, and recover lost or found documents** with the help of **AI-powered matching**.

## 🚀 Features

### 📄 Report Lost & Found Documents

Users can report lost documents and submit details of documents they have found.

### 🤖 AI-Powered Matching

Uses the **Gemini API** to analyze document information and assist in identifying potential matches between lost and found reports.

### 🔍 Search Documents

Users can search and explore reported documents to find potential matches.

### 🔐 Authentication

Secure user authentication and protected application flows.

### 🔔 Notifications

Users can receive notifications related to document matches and activity.

### 📊 User Dashboard

Manage reports, profile information, activity, and notifications from a centralized dashboard.

### 🗄️ Database Integration

Persistent application data is managed using **PostgreSQL** with **Drizzle ORM**.

---

## 🖼️ Application Preview

The application includes a modern landing page, authentication flow, user dashboard, document reporting forms, search functionality, and notification management.

---

## 🛠️ Tech Stack

### Frontend

* React
* TypeScript
* Vite
* Tailwind CSS
* React Context
* React Query
* Lucide React

### Backend

* Node.js
* Express.js
* REST APIs

### Database

* PostgreSQL
* Drizzle ORM

### AI

* Google Gemini API

### Tools & Configuration

* Git & GitHub
* NPM
* Vite
* Vercel configuration

---

## 📦 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/vedantxvii/DocFinder.git
cd DocFinder
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the project root and add the required environment variables for your database and Gemini API.

Example:

```env
DATABASE_URL=your_database_url
GEMINI_API_KEY=your_gemini_api_key
```

> Never commit your `.env` file or expose API keys publicly.

### 4. Run the Development Server

```bash
npm run dev
```

The application will be available at:

```text
http://localhost:5173
```

---

## 🏗️ Build for Production

```bash
npm run build
```

This creates the production build for deployment.

---

## 🚢 Deployment

The application can be deployed using platforms such as:

* Vercel
* Netlify
* Other Node.js-compatible hosting platforms

---

## 📁 Project Structure

```text
DocFinder/
├── client/
│   ├── public/
│   └── src/
│       ├── assets/
│       ├── components/
│       │   ├── auth/
│       │   ├── dashboard/
│       │   ├── forms/
│       │   ├── landing/
│       │   └── ui/
│       ├── hooks/
│       ├── lib/
│       ├── pages/
│       ├── App.tsx
│       ├── index.css
│       └── main.tsx
│
├── server/
│   ├── db.ts
│   ├── index.ts
│   ├── routes.ts
│   ├── storage.ts
│   ├── vite.ts
│   └── services/
│       └── gemini.ts
│
├── shared/
│   └── schema.ts
│
├── migrations/
├── package.json
├── drizzle.config.ts
├── vite.config.ts
├── tailwind.config.ts
├── tsconfig.json
├── vercel.json
└── README.md
```

---

## 🎯 Project Highlights

* AI-assisted document matching
* Full-stack React + Express architecture
* PostgreSQL database integration
* RESTful API development
* User authentication
* Responsive dashboard
* Document search and reporting workflows

---

## 🙏 Credits

* Google Gemini API
* React
* Vite
* Tailwind CSS
* Express.js
* Drizzle ORM
* Lucide React
* PostgreSQL

---

## 👩‍💻 Author

**Vedantxvii**

GitHub: [@vedantxvii](https://github.com/vedantxvii)
