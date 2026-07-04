<p align="center">
  <img src="https://res.cloudinary.com/dbjcy5boz/image/upload/v1783160304/ezgif.com-animated-gif-maker_ypumdq.gif" alt="WD01 Logo" width="300"/>
</p>

<h1 align="center">WD01 Digital Systems</h1>

<p align="center">
  Official platform for WD01 Digital Systems — a full-stack digital agency
  <br/>
  <a href="https://wd-01.vercel.app">🌐 Live Website</a>
</p>

---

## 📌 Overview

WD01 Digital Systems is a digital agency co-founded by Wassim Mansour and Dhia Eddine Ben Hassen, delivering full-stack web development, digital systems automation, and end-to-end digital solutions for clients across multiple industries.

This platform serves as the agency's public showcase and content-managed presence, featuring a portfolio of delivered projects and a full headless CMS for internal content management.

---

## ✨ Features

### Public Website
- 🚀 Agency services showcase — web development, automation, digital systems
- 🗂️ Project portfolio with detailed case studies
- 🎥 Video hosting via Vimeo integration
- 📋 Client inquiry system
- 📱 Fully responsive across all devices
- 🔍 Full SEO with Google Search Console integration
- 📊 Vercel Analytics

### Admin Dashboard (CMS)
- ✏️ Full content management — text, images, videos, section toggles
- 📁 Project and portfolio management via Cloudinary
- 📬 Inquiry management and tracking
- 🛠️ Services and process step management

---

## 🔒 Security Features

- **Row Level Security (RLS)** — Supabase PostgreSQL policies with hardened `is_admin()` using SECURITY DEFINER
- **File upload validation** — type, extension, and size filtering on frontend and Supabase storage
- **Rate limiting** — inquiry submission throttling per IP
- **Honeypot fields** — bot detection via invisible form fields
- **Input sanitization** — all fields sanitized before processing
- **Supabase Auth** — secure dashboard authentication
- **Vercel geo-blocking** — edge-level regional access control

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React 18, TypeScript, Vite, Tailwind CSS, Framer Motion |
| Backend | Supabase (PostgreSQL, Auth, RLS, Storage) |
| Media | Cloudinary, Vimeo |
| Deployment | Vercel |
| Analytics | Vercel Analytics, Google Search Console |

---

## 👤 Role

Sole developer — designed, built, and deployed end-to-end by Wassim Mansour.

---

> 🔐 *Source code is confidential. Live platform available at [wd-01.vercel.app](https://wd-01.vercel.app)*
