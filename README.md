# 🧭 Voyage Planner — Next.js 14 Full-Stack Travel Booking App

Welcome to **Voyage Planner**, a modern full-stack travel booking application built using the latest capabilities of the **Next.js 14 App Router**. This project integrates real-time scraping, robust backend workflows, and a seamless user interface to enable users to explore and book **flights, hotels, and experiences** — all in one place.


## Concepts & Features Covered

### 🛠 Tech Stack
- **Frontend**: Next.js 14 (App Router), Tailwind CSS, TypeScript
- **Backend**: Node.js, Puppeteer, API Routes, Server Actions, JWT, Redis, BullMQ
- **Database**: PostgreSQL with Prisma ORM
- **State Management**: Zustand
- **Authentication**: JWT-based auth flow
- **Payments**: Stripe integration
- **Deployment**: Dockerized and hosted on Aptible

---

### 🚀 Core Features

- **Next.js 14 App Directory with Tailwind CSS**  
  Experience a sleek and modern UI, powered by the latest **Next.js 14 App Router** and styled with **Tailwind CSS** for fast, responsive design.

- **API Routes & Server Actions**  
  Backend logic is cleanly handled using **Next.js server actions** and **API routes** to manage dynamic data fetching, booking logic, and Stripe checkout.

- **Scraping Engine with Puppeteer, Redis & BullMQ**  
  A robust scraping system built using **Puppeteer** to extract live pricing from travel sites, with **Redis** and **BullMQ** orchestrating background job queues.

- **Secure JWT Authentication & Authorization**  
  Users are authenticated using **JWT tokens**, ensuring secure access to personalized bookings and data.

- **Stripe Integration**  
  Complete payment flow implemented via **Stripe Checkout**, enabling users to pay for flights, hotels, and curated experiences.

- **Unified Travel Booking Flow**  
  Users can search, view, and book **flights, hotels, and packages** — all within a unified, user-friendly interface.

- **Live Data from Multiple Sources**  
  Real-time scraping from multiple websites ensures up-to-date travel data for accurate results.

- **PostgreSQL + Prisma for Data Persistence**  
  Scraped and user data is persisted using **PostgreSQL**, queried and managed via the powerful **Prisma ORM**.

- **Zustand for State Management**  
  Lightweight and intuitive state management handled by **Zustand**, enabling a responsive and reactive frontend experience.

- **Dockerized & Deployed on Aptible**  
  The app is containerized using **Docker** and deployed securely on **Aptible**, ensuring scalability, isolation, and HIPAA-grade security.

---

## 📌 Environment Variables

You'll need to set the following in a `.env.local` file:

```env
DATABASE_URL=your_postgresql_connection_string
JWT_SECRET=your_jwt_secret_key
STRIPE_SECRET_KEY=your_stripe_secret_key
STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret
REDIS_URL=your_redis_connection_url
```
## ✍️ Developed By

**Keerti Damani**  
🔗 [GitHub](https://github.com/keertidamani)  


