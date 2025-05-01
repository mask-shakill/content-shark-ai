# 🦈 Content Shark AI

**Content Shark AI** is a modern AI-powered platform that generates short-form content, inspirational quotes, and engaging captions tailored for social media platforms. Built with a clean and scalable architecture, it combines the power of **Next.js** on the frontend and **FastAPI** on the backend.

---

## 🚀 Features

- ✨ AI-generated short content for social media
- 🧠 Custom inspirational quotes and captions
- ⚡ Fast and responsive UI built with Next.js
- 🛠️ Backend APIs built using Python FastAPI
- 📱 Perfect for content creators, marketers, and social media managers

---

## 🧱 Tech Stack

| Layer       | Technology       |
|-------------|------------------|
| Frontend    | Next.js (App Router) |
| Backend     | Python FastAPI   |
| Styling     | Tailwind CSS     |
| AI/ML       | OpenAI or HuggingFace API (Pluggable) |
| Deployment  | Vercel / Railway / Render (as per use) |

---

## 📁 Folder Structure

```bash
content-shark-ai/
├── src/
│   ├── app/                        # Next.js App Router Pages
│   │   ├── about/                  # About Page
│   │   │   └── page.tsx            # About page component
│   │   ├── login/                  # Login and Authentication
│   │   │   ├── page.tsx            # Login page component
│   │   │   └── layout.tsx          # Layout for Login page
│   │   ├── quotes/                 # AI-generated Quotes
│   │   │   └── page.tsx            # Quote generation page component
│   │   ├── captions/               # AI-generated Captions
│   │   │   └── page.tsx            # Caption generation page component
│   │   ├── content/                # Short-form Content Generation
│   │   │   └── page.tsx            # Content generation page component
│   │   ├── others/                 # Other content categories
│   │   │   └── page.tsx            # Other content generation page
│   │   ├── layout.tsx              # Root layout (shared across pages)
│   │   └── page.tsx                # Landing/Home page
│
│   ├── components/                 # Reusable UI Components
│   │   ├── Header.tsx              # Header component
│   │   ├── Footer.tsx              # Footer component
│   │   ├── QuoteCard.tsx           # Quote card component
│   │   ├── CaptionCard.tsx         # Caption card component
│   │   ├── Button.tsx              # Reusable button component
│   │   └── Input.tsx               # Reusable input component
│
│   ├── lib/                        # Helper libraries or custom hooks
│   │   ├── apiClient.ts            # Axios or fetch wrapper
│   │   ├── auth.ts                 # Auth logic and session management
│   │   └── openai.ts               # Optional: OpenAI API integration utilities
│
│   ├── context/                    # Global state management with React Context
│   │   └── AuthContext.tsx         # Context for user authentication
│
│   ├── styles/                     # Tailwind CSS and global styles
│   │   ├── globals.css             # Global styles
│   │   └── tailwind.config.js      # Tailwind CSS configuration
│
│   ├── public/                     # Static assets like images or logos
│   │   └── logo.png                # Example logo file
│
├── backend/                        # FastAPI Backend (optional, colocated)
│   ├── main.py                     # FastAPI app entrypoint
│   ├── routers/                    # API route handlers for FastAPI
│   │   ├── quotes.py               # Endpoint for generating quotes
│   │   ├── captions.py             # Endpoint for generating captions
│   │   └── auth.py                 # Authentication routes (optional)
│   ├── services/                   # Business logic layer
│   ├── models/                     # Pydantic models or schemas
│   └── utils/                      # Utility functions for backend
│
├── .env.local                      # Environment variables for API keys
├── package.json                    # Project dependencies and scripts
├── next.config.js                  # Next.js configuration
├── tsconfig.json                   # TypeScript configuration
├── README.md                       # Project documentation


```

### **Explanation of Sections**:

1. **Project Title** and Overview: A brief description of the project and its main features.
2. **Getting Started**: Instructions on how to set up the project locally.
3. **SEO-Friendly Features**: Highlights the SEO optimizations that Content Shark AI offers.
4. **Technologies Used**: A list of tools, frameworks, and technologies used in the project.
5. **SEO Benefits**: Details about how the platform is optimized for search engines.
6. **Contributing**: Instructions for others who wish to contribute to the project.
7. **License**: Information about the project's license.

This README will help others quickly understand the purpose of your project, how to get started, and the technologies behind it while also making it SEO-friendly.

