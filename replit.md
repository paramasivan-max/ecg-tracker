# ECG Monitor Application

## Overview

This is a full-stack ECG (Electrocardiogram) monitoring application built with React, TypeScript, Express.js, and Drizzle ORM. The application provides real-time ECG data visualization, patient monitoring, and historical data analysis for healthcare professionals. It features a modern, responsive design with both light and dark themes, comprehensive charting capabilities, and user authentication.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Framework**: React 18 with TypeScript for type safety and modern development
- **Build Tool**: Vite for fast development and optimized production builds
- **Routing**: Wouter for lightweight client-side routing
- **State Management**: TanStack Query for server state management and caching
- **UI Framework**: Radix UI components with shadcn/ui design system
- **Styling**: Tailwind CSS with CSS custom properties for theming
- **Charts**: Chart.js for ECG waveform visualization and data plotting
- **Form Handling**: React Hook Form with Zod validation schemas

### Backend Architecture
- **Runtime**: Node.js with Express.js server framework
- **Language**: TypeScript with ES modules for modern JavaScript features
- **API Design**: RESTful API with structured error handling and logging middleware
- **Development**: Hot module replacement with Vite integration for seamless full-stack development
- **Session Management**: Express session handling with PostgreSQL session store

### Data Layer
- **Database**: PostgreSQL as the primary database with Neon serverless hosting
- **ORM**: Drizzle ORM for type-safe database queries and schema management
- **Schema**: Shared TypeScript schema definitions between client and server
- **Validation**: Zod schemas for runtime type validation and data integrity
- **Storage Interface**: Abstract storage layer with in-memory implementation for development and testing

### Authentication & Authorization
- **Strategy**: Session-based authentication with username/password login
- **Storage**: Browser localStorage for client-side user session persistence
- **Mock Authentication**: Development-friendly auth system that creates users on-the-fly
- **User Management**: Complete CRUD operations for user profiles and medical information

### UI/UX Design
- **Design System**: Consistent component library with Radix UI primitives
- **Theme System**: Light/dark mode support with CSS custom properties
- **Responsive Design**: Mobile-first approach with adaptive navigation
- **Accessibility**: WCAG compliant components with proper ARIA labels and keyboard navigation
- **Visual Feedback**: Toast notifications and loading states for user interactions

## External Dependencies

### Database & Infrastructure
- **Neon Database**: Serverless PostgreSQL hosting with connection pooling
- **Drizzle Kit**: Database migration and schema management tools

### UI & Styling
- **Radix UI**: Comprehensive set of accessible, unstyled React components
- **Tailwind CSS**: Utility-first CSS framework with PostCSS processing
- **Lucide React**: Consistent icon library for UI elements
- **Chart.js**: Canvas-based charting library for ECG waveform visualization

### Development Tools
- **TypeScript**: Static type checking and enhanced developer experience
- **Vite**: Fast build tool with hot module replacement and plugin ecosystem
- **ESBuild**: Fast JavaScript bundler for production builds
- **TSX**: TypeScript execution engine for development server

### Form & Validation
- **React Hook Form**: Performant form library with minimal re-renders
- **Zod**: TypeScript-first schema validation library
- **Hookform Resolvers**: Integration between React Hook Form and Zod

### State Management & HTTP
- **TanStack Query**: Server state management with caching and synchronization
- **Date-fns**: Modern date utility library for time-based data formatting

### Replit Integration
- **Development Plugins**: Cartographer and dev banner for Replit-specific development experience
- **Runtime Error Overlay**: Enhanced error reporting during development