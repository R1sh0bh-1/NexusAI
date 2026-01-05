NexusAI - Full Stack AI Content Creation Platform
A modern, full-stack platform built with Next.js 15, Tailwind CSS, Shadcn UI, React Quill, Convex, Clerk Auth, Google Gemini AI, ImageKit, and Unsplash integration.

Create stunning AI-generated articles, blog posts, social media content, and more with a rich text editor, image uploads, and powerful AI assistance.

Features
User authentication with Clerk
Rich text editing with React Quill
AI-powered content generation (via Google Gemini)
Image management with ImageKit and Unsplash search
Responsive design with Tailwind CSS and Shadcn UI components
Real-time backend with Convex
Dark/Light mode support
Tech Stack
Frontend: Next.js (App Router), React 19, Tailwind CSS, Shadcn UI
Backend: Convex
Auth: Clerk
AI: Google Generative AI (Gemini)
Images: ImageKit, Unsplash API
Other: React Hook Form, Zod, Sonner, Lucide Icons
Getting Started
Clone the repository
Bash
git clone https://github.com/your-username/nexusai-platform.git
cd nexusai-platform
Install dependencies
Bash
npm install
Create a .env.local file in the root directory and add the following variables:
text
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
Set up Convex
Bash
npx convex dev
Run the development server
Bash
npm run dev
Open http://localhost:3000 in your browser.
Deployment
Deploy easily on Vercel (recommended for Next.js apps).

Enjoy building with NexusAI! Feel free to customize and extend it further.
