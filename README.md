# StayEase: Airbnb Clone Project

## 📌 Project Overview

**StayEase** is a full-stack web application inspired by Airbnb. It allows users to browse property listings, view detailed property information, and complete bookings. This project replicates the core functionalities of Airbnb, focusing on UI/UX design, robust backend API development, and responsive, mobile-first web design.

> 🗓️ Project Duration: June 16, 2025 – June 23, 2025  
> 🛠️ Level: Novice  
> ✅ Manual QA review required before deadline

---

## 🎯 Project Goals

- Implement responsive and accessible UI/UX designs.
- Build a modular frontend architecture using React.
- Develop a backend with RESTful APIs.
- Collaborate using Git and follow software development best practices.
- Design a scalable and normalized database.
- Learn full-stack deployment and DevOps basics.

---

## 🧰 Tech Stack

- **Frontend:** HTML, CSS, JavaScript (React)
- **Backend:** Node.js, Express (or equivalent)
- **Database:** PostgreSQL / MongoDB
- **Version Control:** Git + GitHub
- **Design:** Figma for UI/UX mockups
- **Deployment:** Render / Vercel / Netlify (TBD)

---

## 🎨 UI/UX Design Planning

### 🎯 Design Goals

The design of StayEase focuses on creating an intuitive, fast, and seamless booking experience for users. The key UI/UX design goals include:

- ✅ **Intuitive Booking Flow**: Ensure users can search, view, and book properties with minimal friction.
- ✅ **Visual Consistency**: Use consistent typography, color schemes, and components throughout the application.
- ✅ **Fast Loading Times**: Optimize assets and minimize layout shifts to enhance performance.
- ✅ **Mobile Responsiveness**: Follow a mobile-first approach to ensure the app looks and works great on all screen sizes.

---

### 🌟 Key Features

- 🔍 **Property Search and Filtering**
- 📝 **Detailed Property Viewing**
- 💳 **Secure Checkout Process**
- 🔐 **User Authentication**

---

### 📄 Primary Pages

| Page Name              | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| **Property Listing View** | Displays available properties in a grid with search filters. Each card shows images, price, location, and rating. |
| **Listing Detailed View** | Shows full property details including amenities, reviews, and a booking form. Large image carousel included. |
| **Simple Checkout View** | A minimal, secure checkout page to complete bookings and confirm payment. |

---

### 💡 Importance of User-Friendly Design

A user-friendly design is essential for a high-conversion booking platform:

- 🧭 **Simplifies Navigation**
- 📱 **Enhances Mobile Experience**
- ⚡ **Boosts Performance**
- 👍 **Builds Trust**

The goal is to make the booking process **feel effortless**, **look appealing**, and **perform reliably**.

---

### 🎨 Figma Design Specifications

#### 🖌️ Color Styles

- **Primary:** `#FF5A5F` – buttons, highlights, branding
- **Secondary:** `#008489` – accents and links
- **Background:** `#FFFFFF` – page background
- **Text:** `#222222` – main text
- **Secondary Text:** `#717171` – descriptions and captions

#### ✒️ Typography

- **Font Family:** Circular
- **Headings:** Bold (700), 24px–32px
- **Body Text:** Medium (500), 16px
- **Secondary Text:** Book (400), 14px

---

### 📌 Why Design Properties Matter

Referencing design properties from mockups like Figma ensures:

- 🎯 **Consistency** in look and feel  
- 📐 **Pixel-perfect UI** translation  
- 🧠 **Better team alignment**  
- 📱 **Responsive layouts**  
- 🧩 **Reusable components**

This reduces bugs, accelerates development, and delivers a more polished user experience.

---

## 👥 Project Roles and Responsibilities

| Role               | Responsibilities |
|--------------------|------------------|
| **Project Manager** | Coordinates deadlines, monitors progress, manages communication |
| **Frontend Developer** | Builds UI components, implements responsive design, integrates APIs |
| **Backend Developer** | Develops REST APIs, handles database operations, enforces business logic |
| **Designer** | Creates and maintains UI mockups, ensures design consistency and UX quality |
| **QA/Testers** | Writes test cases, performs manual and automated testing, logs bugs |
| **DevOps Engineer** | Manages cloud deployment, CI/CD pipelines, and infrastructure |
| **Product Owner** | Defines user stories, prioritizes features, communicates stakeholder vision |
| **Scrum Master** | Runs agile ceremonies, tracks blockers, maintains sprint velocity |

These roles work collaboratively to ensure a successful, on-time delivery of the project.

---

## 🧩 UI Component Patterns

We will design and implement reusable, modular components to ensure consistency and scalability. Key components include:

### 🔝 Navbar

- Logo
- Search bar
- User navigation (Login, Profile, Logout)
- Responsive menu for mobile

### 🏠 Property Card

- Property image thumbnail
- Price per night
- Location & rating
- Favorite (❤️) button
- Compact, responsive layout

### 🔚 Footer

- Site navigation links
- Company info
- Social media icons
- Copyright

All components will be built with accessibility in mind, ensuring responsiveness on various screen sizes and devices.

---

## 🧱 Main Features

- 🔍 Property Search and Filter
- 🏘️ Grid Property Listings
- 📝 Detailed Property View
- 💳 Secure Checkout
- 🔐 User Authentication

---

## 🗂️ Primary Pages

| Page                  | Description                                                   |
|-----------------------|---------------------------------------------------------------|
| **Home / Listings**   | Grid display of available properties with filters             |
| **Property Detail**   | Detailed view with photos, descriptions, and booking form     |
| **Checkout**          | Payment summary and confirmation screen                       |
| **Login / Signup**    | Authentication and user session management                    |

---

## 📁 Repository Structure

```bash
airbnb-clone-project/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── styles/
│   ├── services/
│   └── App.js
├── .gitignore
├── package.json
└── README.md
