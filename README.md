# Stacknaut-
Cut the fullstack development by 95%
# Backend-as-a-Service Framework SaaS Platform

## Project Description
A powerful yet minimalist SaaS platform that enables developers to create fully-functional backends with just 5-10 lines of code. Features Swiss-inspired design with dark-first coding interface, real-time collaboration, enterprise-grade scalability, and complete database integration for persistent project storage.

## Key Features
- **Working Backend Builder** - Visual interface for creating backends with drag-and-drop data models, API endpoints, and deployment settings
- **Complete authentication system** with email OTP verification and persistent sessions
- **Database integration** with full CRUD operations for projects, endpoints, schemas, and teams
- **Real-time collaboration** features with team management and active user presence
- **Advanced analytics** dashboard with comprehensive metrics and system health monitoring
- **Mobile-responsive design** across all components with performance optimizations
- **Swiss minimalism design** with dark coding interface optimized for developers
- **API endpoint management** interface with live documentation generation
- **Visual database schema builder** with relationships and persistent storage
- **Real-time monitoring dashboard** with performance metrics and skeleton loading states
- **Code generation and download** - Generate actual backend code from visual configurations

## Data Storage
**Database Tables (Persistent Storage):**
- **projects** (eyjz57f8rzeo): User projects with code, settings, and collaboration data
- **api_endpoints** (eyjz5jpbb2f4): API endpoint configurations and settings  
- **database_schemas** (eyjz5twyd5og): Database schema definitions and relationships
- **teams** (eyjz62x3ot1c): Team information and collaboration settings

**Local Storage:** Zustand with persistence for auth state, collaboration state, localStorage for session management

## Devv SDK Integration
**Built-in Services:** 
- **Authentication system** (email OTP verification) for user login/logout with persistent sessions
- **Database operations** with full CRUD for projects, endpoints, schemas, and teams
- **Real-time data persistence** and synchronization across all features

**External Services:** None currently integrated

## Special Requirements
- Dark-first interface optimized for coding experience  
- Swiss/International Style minimalism with clean typography
- Interactive backend builder works without authentication (demo mode)
- Syntax highlighting for backend-saas framework code with proper CSS styles
- Real-time collaboration features with live user presence
- Advanced analytics with comprehensive system monitoring
- Mobile-first responsive design with optimized touch interactions
- Performance optimization with lazy loading and code splitting
- Accessibility compliance with proper ARIA labels and keyboard navigation
- **Database persistence for all user data and project configurations**
- **Real-time synchronization across team collaboration features**
- **Working backend creation and code generation from visual interface**

## File Structure

/src
├── services/
│   └── database.ts                # Database service layer with full CRUD operations for all entities
│
├── store/
│   ├── auth-store.ts              # Zustand auth state with persistence and demo login
│   ├── collaboration-store.ts     # Team collaboration and real-time features state (with demo data)
│   └── project-store.ts           # Project management with database integration and real-time sync
│
├── components/
│   ├── ui/                        # Pre-installed shadcn/ui components
│   ├── AuthModal.tsx              # Email OTP authentication modal (mobile-optimized)
│   ├── CodeBlock.tsx              # Syntax-highlighted code display with copy functionality
│   ├── CodeEditor.tsx             # Interactive code editor with mobile responsive tabs
│   ├── BackendBuilder.tsx         # **NEW** Complete visual backend builder with working functionality
│   ├── APIEndpointManager.tsx     # Complete API endpoint CRUD interface with database integration
│   ├── DatabaseSchemaBuilder.tsx  # Visual database model builder with persistent storage
│   ├── MonitoringDashboard.tsx    # Real-time performance monitoring with skeleton states
│   ├── CollaborationBar.tsx       # Real-time collaboration status and active users (mobile-friendly)
│   ├── TeamManagement.tsx         # Team member management and invitations (responsive)
│   ├── AdvancedAnalytics.tsx      # Advanced analytics and system health monitoring
│   └── Loading.tsx                # Optimized loading components and skeleton screens with multiple variants
│
├── pages/
│   ├── HomePage.tsx               # Landing page with working BackendBuilder, mobile navigation
│   ├── DashboardPage.tsx          # Main app dashboard with database integration and responsive design
│   └── NotFoundPage.tsx           # 404 error page
│
├── App.tsx                        # Root component with routing, dark mode, and auth state checking
├── main.tsx                       # Entry file
│
└── index.css                      # Swiss minimalism design system with mobile optimizations
                                  # Features: JetBrains Mono for code, Inter for UI
                                  # Colors: Deep code editor dark, success green, highlight yellow
                                  # Performance: Reduced motion support, text rendering optimization
                                  # Mobile: Touch scroll, tap highlight removal, responsive utilities
                                  # **Fixed syntax highlighting CSS classes for code display**
