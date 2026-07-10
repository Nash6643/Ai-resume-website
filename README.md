This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.




# 🚀 AI Resume Builder

An AI-powered resume builder built with **Next.js**, **TypeScript**, **Firebase**, **Tailwind CSS**, and **Google Gemini AI**.

This application allows users to create, edit, manage, and export professional resumes while leveraging AI to improve resume quality.

---

## ✨ Features

### 🔐 Authentication
- Firebase Authentication
- Secure Login
- User Registration
- Protected Routes

### 📄 Resume Management
- Create multiple resumes
- Edit existing resumes
- Save resumes to Firebase Firestore
- Resume Dashboard

### 🎨 Resume Templates
- Classic Template
- Modern Template
- Minimal (ATS-Friendly) Template

### 📑 PDF Export
- Export resumes as high-quality PDF files
- Print-ready formatting

### 🤖 AI Resume Improvement (V1)
Powered by Google Gemini AI.

Users can:
- Improve resume wording
- Strengthen professional descriptions
- Enhance ATS-friendly language
- Improve grammar and readability
- Generate more impactful resume content

---

## 🛠 Tech Stack

### Frontend

- Next.js
- React
- TypeScript
- Tailwind CSS v3

### Backend

- Next.js API Routes

### Database

- Firebase Firestore

### Authentication

- Firebase Authentication

### AI

- Google Gemini API

### PDF Generation

- html2pdf.js

---

## 📂 Project Structure

```
app/
│
├── api/
│   └── improve-resume/
│
├── dashboard/
├── editor/
├── login/
├── signup/
│
components/
│
├── resume/
├── templates/
└── ui/
│
firebase/
│
lib/
│
types/
│
context/
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/ai-resume-builder.git
```

Navigate into the project

```bash
cd ai-resume-builder
```

Install dependencies

```bash
npm install
```

Create an environment file

```
.env.local
```

Add your Firebase and Gemini credentials

```env
NEXT_PUBLIC_FIREBASE_API_KEY=YOUR_KEY
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=YOUR_DOMAIN
NEXT_PUBLIC_FIREBASE_PROJECT_ID=YOUR_PROJECT_ID
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=YOUR_BUCKET
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=YOUR_SENDER_ID
NEXT_PUBLIC_FIREBASE_APP_ID=YOUR_APP_ID

GEMINI_API_KEY=YOUR_GEMINI_API_KEY
```

Start the development server

```bash
npm run dev
```

Open

```
http://localhost:3000
```

---

## 📸 Screenshots

### Dashboard

> Add screenshot here

### Resume Editor

> Add screenshot here

### Resume Preview

> Add screenshot here

### AI Resume Improvement

> Add screenshot here

---

## 🗺 Roadmap

### ✅ Version 1
- [x] Authentication
- [x] Resume Dashboard
- [x] Resume Editor
- [x] Multiple Resume Templates
- [x] PDF Export
- [x] AI Resume Improvement

### 🚧 Version 2
- [ ] ATS Resume Scoring
- [ ] Job Description Matching
- [ ] AI Cover Letter Generator
- [ ] Interview Question Generator
- [ ] Resume Duplication
- [ ] Resume Renaming
- [ ] Resume Deletion
- [ ] Resume Version History

### 🚀 Future Enhancements
- [ ] AI Chat Assistant
- [ ] LinkedIn Resume Import
- [ ] Portfolio Generator
- [ ] Multi-language Resume Support
- [ ] Resume Analytics
- [ ] Cloud PDF Storage

---

## 🎯 Learning Outcomes

This project demonstrates:

- Full-stack web development
- Authentication using Firebase
- Firestore CRUD operations
- API integration with Google Gemini AI
- State management with React
- Dynamic resume rendering
- PDF generation
- Responsive UI design
- Component-based architecture
- TypeScript best practices

---

## 🤝 Contributing

Contributions, suggestions, and feature requests are welcome.

Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Your Name**

Computer Science Student

GitHub: https://github.com/YOUR_USERNAME

LinkedIn: https://linkedin.com/in/YOUR_PROFILE
