# Frontend Job Portal Application

This project is the **frontend** part of a full-stack Job Portal application, built using **React.js** with **Vite** and **shadcn/ui** for the UI components.  

It integrates with a backend API to manage:

- Jobs  
- Companies  
- User Authentication  
- Job Applications  

## Technologies Used

- **React.js** – A JavaScript library for building user interfaces.  
- **Vite** – A fast build tool that significantly improves the frontend development experience.  
- **shadcn/ui** – A collection of reusable UI components built with Radix UI and Tailwind CSS, providing a highly customizable and accessible design system.  
- **Tailwind CSS** – A utility-first CSS framework for rapidly building custom designs.  
- **Redux Toolkit** – For efficient state management across the application.  
- **Axios** – A promise-based HTTP client for making API requests.  
- **React Router DOM** – For declarative routing within the application.  
- **Framer Motion** – For animations.  

## Features

- **User Authentication** – Login and Signup functionalities with secure password handling.  
- **User Profiles** – View and update user profiles, including resume and profile photo uploads.  
- **Job Listings** – Display a list of available jobs.  
- **Job Details** – View detailed descriptions of individual jobs.  
- **Job Search and Filtering** – Search for jobs and apply filters based on various criteria.  
- **Job Application** – Users can apply for jobs.  

### Admin Panel

- Manage companies  
- Manage job listings  
- View and manage job applicants  
- Update applicant status  

- **Responsive Design** – Built with shadcn/ui and Tailwind CSS for a responsive and modern user interface.  

---

## Getting Started

Follow the steps below to set up and run the frontend application.

## Prerequisites

Make sure you have the following installed:

- **Node.js** (LTS version recommended)  
- **npm** or **yarn**

---

## Installation

### 1️⃣ Clone the repository

```bash
git clone [repository-url]
```

### 2️⃣ Navigate to the frontend directory

```bash
cd frontend
```

### 3️⃣ Install dependencies

Using npm:
```bash
npm install
```
Or using yarn:
```bash
yarn install
```

## Project Setup (React Vite with shadcn/ui)

The project uses **Vite** for bundling and **shadcn/ui** for UI components.  
The initial setup involved the following steps:

---

### 1️⃣ Creating a Vite React Project

```bash
npm create vite@latest . --template react
```
- Choose **React** as the framework
- Choose **JavaScript** as the variant

### 2️⃣ Setting up Tailwind CSS and shadcn/ui

Install Tailwind CSS dependencies:
```bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

Initialize shadcn/ui:
```bash
npx shadcn-ui@latest init
```
Follow the prompts to configure shadcn/ui.

A jsconfig.json file will be created for path aliases.

### 3️⃣ Running the Application

To start the development server:
Using npm:
```bash
npm run dev
```

Or using yarn:
```bash
yarn dev
```
The application will typically run on:

👉 **http://localhost:5173**

---

## Important Notes

- Ensure your backend server is running and accessible as configured in your frontend environment variables.  
- The `App.css` file should be cleared of default styles.  
- The project uses **react-router-dom** for navigation.  
- Routes are protected based on user authentication status.  

---

## Project Structure

The frontend project is organized into components, pages, Redux for state management, and hooks for custom functionalities.

```bash
src/
│
├── components/   # Reusable UI components (e.g., Navbar, JobCard)
├── pages/        # Main application pages (e.g., Home, Jobs, Login, Signup)
├── redux/        # Global state management using Redux Toolkit
├── hooks/        # Custom React hooks
└── assets/       # Static assets like images
```
