# ALX Listing App

A modern property listing application built with Next.js, TypeScript, and TailwindCSS as part of the ALX Software Engineering program.

## Purpose and Goals

The ALX Listing App is designed to showcase property listings with a clean, modern interface. This project demonstrates:

- Modern React development with Next.js
- TypeScript for type safety
- Component-based architecture
- Responsive design with TailwindCSS
- Clean folder structure and best practices

## Folder Structure

```
alx-listing-app/
├── components/
│   └── common/           # Reusable UI components
│       ├── Card.tsx      # Property card component
│       └── Button.tsx    # Reusable button component
├── interfaces/           # TypeScript type definitions
│   └── index.ts         # Component prop interfaces
├── constants/           # Application constants
│   └── index.ts        # App-wide constants
├── pages/              # Next.js pages (Pages Router)
│   ├── _app.tsx       # App wrapper component
│   └── index.tsx      # Homepage
├── public/
│   └── assets/        # Static assets (images, icons)
├── styles/
│   └── globals.css    # Global styles with Tailwind
└── README.md
```

## Component Purpose

### Card Component
- **Purpose**: Displays property information including image, title, and description
- **Props**: `title`, `description`, `image`
- **Usage**: Reusable across different property listings

### Button Component
- **Purpose**: Provides consistent button styling and behavior
- **Props**: `label`, `onClick`
- **Usage**: Actions like "Book Now", "View Details", etc.

## Getting Started

Follow these steps to run the project locally:

### 1. Clone the Repository
```bash
git clone <repository-url>
cd alx-listing-app
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Run the Development Server
```bash
npm run dev
```

### 4. Open in Browser
Navigate to [http://localhost:3000](http://localhost:3000) to view the application.

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Technologies Used

- **Next.js 14** - React framework with Pages Router
- **TypeScript** - Type safety and better developer experience
- **TailwindCSS** - Utility-first CSS framework
- **ESLint** - Code linting and formatting

## Features

- ✅ Responsive design
- ✅ TypeScript integration
- ✅ Component-based architecture
- ✅ Clean folder structure
- ✅ TailwindCSS styling
- ✅ ESLint configuration

## Learning Objectives

This project helps demonstrate:
- Next.js Pages Router setup and configuration
- TypeScript interface definitions
- Component composition and reusability
- TailwindCSS utility classes
- Project structure best practices
- Modern React development patterns

---

Built with ❤️ for ALX Software Engineering Program
