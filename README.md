# Techligence Robotics Website

A modern, responsive corporate website for Techligence Robotics built using Next.js, TypeScript, Tailwind CSS, MongoDB Atlas, and Vercel.

## Overview

The Techligence Robotics website serves as the company's digital presence, showcasing intelligent service robotics solutions for industries such as hospitality, healthcare, corporate offices, retail environments, and public spaces.

The platform provides product information, industry solutions, company details, and a contact system that stores customer inquiries in MongoDB and allows administrators to manage submissions through a secure dashboard.

---

## Live Website

Production URL:

https://techligence-robotics.vercel.app

---

## Features

### Public Website

* Responsive Landing Page
* About Us Page
* Products Page
* Industries Page
* Contact Page
* Mobile-Friendly Design
* Modern UI/UX
* Dark Theme Interface
* Interactive Assistant Bot

### Contact Management

* Contact Form Submission
* MongoDB Atlas Integration
* Real-Time Inquiry Storage
* Secure API Endpoints

### Admin Panel

* Admin Login
* Protected Dashboard
* View Customer Inquiries
* Centralized Lead Management

### Deployment

* Production Deployment on Vercel
* GitHub Integration
* Automatic Continuous Deployment

---

## Technology Stack

### Frontend

* Next.js 16
* React 19
* TypeScript
* Tailwind CSS

### Backend

* Next.js API Routes
* MongoDB Atlas
* Mongoose

### Deployment

* Vercel

### Version Control

* Git
* GitHub

---

## Project Structure

```text
src/
│
├── app/
│   ├── about/
│   ├── products/
│   ├── industries/
│   ├── contact/
│   ├── admin/
│   └── api/
│
├── components/
│   ├── Navbar
│   ├── Footer
│   └── InteractiveBot
│
├── lib/
│   └── mongo.ts
│
└── models/
    ├── Contact.ts
    └── Product.ts
```

---

## Environment Variables

Create a `.env.local` file:

```env
MONGODB_URI=your_mongodb_connection_string

ADMIN_EMAIL=your_admin_email

ADMIN_PASSWORD=your_admin_password
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/navneetchinchole04/techligence-website-v2.git
```

Navigate to the project:

```bash
cd techligence-website-v2
```

Install dependencies:

```bash
npm install
```

Run development server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

Start production server:

```bash
npm run start
```

---

## Business Objectives

* Establish a professional online presence
* Showcase robotics products and solutions
* Generate customer leads
* Streamline inquiry management
* Support future AI-driven customer interactions

---

## Future Enhancements

* AI Chat Assistant
* Product Management Dashboard
* Analytics Dashboard
* Email Notifications
* Demo Booking System
* CRM Integration
* Multi-language Support

---

## Author

Navneet Chinchole

B.Tech Electronics & Computer Engineering

Web Development Intern

---

## License

This project is developed for Techligence Robotics and is intended for business and demonstration purposes.
