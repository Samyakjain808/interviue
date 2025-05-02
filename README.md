# 🎥 Interviue – Remote Interview Platform with Video Calls

**Interviue** is a modern, full-stack web application designed to facilitate seamless remote interviews. Built with **Next.js** and **TypeScript**, it integrates real-time video calling, screen sharing, and recording functionalities to provide an efficient and interactive interview experience.

---

## 🚀 Features

- **Real-Time Video Calls**: Conduct interviews with high-quality video and audio.
- **Screen Sharing**: Share your screen to present documents, code, or other resources.
- **Session Recording**: Record interview sessions for future reference and review.
- **Authentication & Authorization**: Secure login and user management using Clerk.
- **Dynamic Routing**: Navigate through the application with dynamic and static routes.
- **Responsive Design**: Optimized for various devices using Tailwind CSS and Shadcn UI components.

---

## 🛠️ Tech Stack

- **Frontend**: Next.js 14, TypeScript
- **Backend**: Convex (Serverless Backend)
- **Authentication**: Clerk
- **Video Streaming**: Stream SDK
- **Styling**: Tailwind CSS, Shadcn UI

---
### Check the Demo

interviue-rc4g-pqtk2cmkc-samyakjains-projects-b2e8a41f.vercel.app
---
### Installation

1. **Install dependencies:**

```bash
npm install

```
### Set Up Environment Variables

Create a `.env` file in the root directory and add the following variables:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
CONVEX_DEPLOYMENT=your_convex_deployment_url
NEXT_PUBLIC_CONVEX_URL=your_convex_public_url
NEXT_PUBLIC_STREAM_API_KEY=your_stream_api_key
STREAM_SECRET=your_stream_secret
```
### Run Development Server
```bash
npm run dev
```
