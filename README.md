# 🌐 Personal Portfolio Website

This is a professional personal portfolio website showcasing skills, projects, and contact information. 
It features a modern UI, smooth animations, a responsive design, and a secure serverless backend for the contact form.

---

## ✨ Features
- **Fully Responsive:** Optimized for mobile, tablet, and desktop views.
- **Modern UI:** Smooth animations using Animate.css and interactive Lottie elements.
- **Serverless Contact Form:** Reliable email delivery via the Resend API.
- **Secure Backend:** Environment variables ensure no API keys are exposed to the frontend or GitHub.

---

## 🛠️ Tech Stack

### Frontend
- HTML5, CSS3, JavaScript
- [Lottie](https://lottiefiles.com/) & [Animate.css](https://animate.style/)

### Backend (Serverless)
- Node.js
- [Resend SDK](https://resend.com/)
- Vercel Serverless Functions

---

## 📦 Dependencies & Installation

To run this project, you need to install the following dependencies. Open your terminal in the project root and run:


# Install the Resend SDK for the backend
npm install resend

# (Optional) Install Vercel CLI for local testing
npm install -g vercel 

# 📧 How to Activate the Contact Form (Deployment)
To make the contact form work on your live website, follow these steps to link the backend:
1. Resend API Setup
Sign up at Resend.com.
Copy your API Key from the dashboard.
Update the to: email address in api/server.js to your verified Resend email.

2. Vercel Activation

When you deploy this project to Vercel, you must manually add your API Key to the cloud:
Open your project in the Vercel Dashboard.
Navigate to Settings > Environment Variables.
Add a new variable:
Key: RESEND_API_KEY
Value: (Paste your Resend API key)
Save and trigger a new deployment or push your code to GitHub.