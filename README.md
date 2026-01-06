# 🚀 NexusAI – Full Stack AI Content Creation Platform

NexusAI is a modern, full-stack AI-powered content creation platform built with the latest web technologies. It enables users to generate high-quality articles, blog posts, and social media content using AI, along with rich text editing, image management, and real-time backend capabilities.

---

## ✨ Features

- 🔐 **User Authentication** with Clerk
- ✍️ **Rich Text Editing** using React Quill
- 🤖 **AI-Powered Content Generation** via Google Gemini
- 🖼️ **Image Upload & Optimization** with ImageKit
- 🔍 **Unsplash Image Search** integration
- ⚡ **Real-time Backend** powered by Convex
- 🎨 **Modern UI** with Tailwind CSS & Shadcn UI
- 🌗 **Dark / Light Mode** support
- 📱 **Fully Responsive Design**

---

## 🛠️ Tech Stack

### Frontend
- **Next.js 15** (App Router)
- **React 19**
- **Tailwind CSS**
- **Shadcn UI**
- **React Quill**
- **React Hook Form**
- **Zod**
- **Lucide Icons**
- **Sonner**

### Backend & Services
- **Convex** (Real-time Backend)
- **Clerk** (Authentication)
- **Google Generative AI (Gemini)**
- **ImageKit**
- **Unsplash API**

---

## 📦 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/nexusai-platform.git
cd nexusai-platform
````

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Environment Variables

Create a `.env.local` file in the root directory and add the following:

# Convex
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

# Clerk Auth
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
CLERK_JWT_ISSUER_DOMAIN=

# ImageKit
NEXT_PUBLIC_IMAGEKIT_PUBLIC_KEY=
NEXT_PUBLIC_IMAGEKIT_URL_ENDPOINT=
IMAGEKIT_PRIVATE_KEY=

# Unsplash
NEXT_PUBLIC_UNSPLASH_ACCESS_KEY=

# Gemini AI
GEMINI_API_KEY=

> ⚠️ Make sure to keep your API keys private and **never commit `.env.local` to GitHub**.

---

### 4️⃣ Set Up Convex

```bash
npx convex dev
```

---

### 5️⃣ Run the Development Server

```bash
npm run dev
```

Open your browser and visit:

```
http://localhost:3000
```

---

## 🚀 Deployment

NexusAI is optimized for deployment on **Vercel**.

1. Push your repository to GitHub
2. Import the project into Vercel
3. Add all environment variables in Vercel Dashboard
4. Deploy 🚀

---

## 📄 License

This project is licensed under the **MIT License**.

---

## ⭐ Acknowledgements

* Google Gemini AI
* Clerk Auth
* Convex
* ImageKit
* Unsplash
* Shadcn UI

---

