# 🚀 Modern Productivity App

> **Note:** This repository showcases the UI/UX design and frontend architecture of the project. 

A full-stack productivity application featuring Notes, To-Do Lists, Mind Maps, and Flashcards with a modern neumorphic design system.
---

## ⚠️ Project Status

**🔨 Currently in Active Development**

This project is actively being refined and optimized. The repository currently showcases:
- ✅ UI/UX Design & Screenshots
- ✅ Feature Documentation
- ✅ Technical Architecture Overview

**Full codebase not included because:**
- 🔄 Currently refactoring backend architecture
- 🔧 Implementing additional security features
- 🎨 Optimizing frontend performance
- 📝 Cleaning up and documenting code for production
---

## ✨ Features Implemented

### 📋 Smart To-Do Lists
![Todo Management](./screenshots/todo-view.png)
- Task management with completion tracking
- Priority label system
- Clean, minimalist interface
- Progress indicators (0/2 completed)

### 🌓 Beautiful Dark Mode
![Dark Mode](./screenshots/dashboard-dark.png)
![Light Mode](./screenshots/dashboard-light.png)
- Seamless theme switching
- Eye-friendly dark theme
- Neumorphic design elements
- Consistent styling across all components

### 🗂️ Intuitive Sidebar Navigation
![Sidebar](./screenshots/sidebar.png)
- Quick access to notes and to-do lists
- User profile with avatar
- Organized navigation
- Trash management

### 🧠 Interactive Mind Maps
![Mind Map Empty State](./screenshots/mindmap-empty.png)
![Mind Map Canvas](./screenshots/mindmap-canvas.png)
- Visual idea organization with custom nodes
- Interactive canvas for brainstorming
- Theme customization
- Import/Export functionality (JSON, PNG)

### 🎴 Flashcards with Spaced Repetition
![Flashcard Decks](./screenshots/flashcards-deck.png)
![Add Card](./screenshots/flashcards-add.png)
![Create Deck](./screenshots/flashcards-create-deck.png)
- SRS (Spaced Repetition System) algorithm
- Multiple card types (Basic, Cloze)
- Tag organization system

---

## 💻 Tech Stack

### Frontend
- **React 18** - Modern React with Hooks
- **TipTap** - Rich text editor for notes
- **React Flow** - Interactive mind map canvas
- **Custom CSS** - Neumorphic design system with dark/light themes


## 🎨 Design Philosophy

### Neumorphic UI Design
- Soft shadows creating depth and dimension
- Tactile, modern interface
- Consistent design language
- Smooth transitions and micro-interactions

### User Experience Focus
- Intuitive navigation patterns
- Clear empty states with guidance
- Real-time search functionality
- Keyboard shortcuts support
- Mobile-responsive layouts


## 🏗️ Architecture Highlights
```
Frontend Architecture:
├── Context Providers
│   ├── AuthContext (JWT + Protected Routes)
│   ├── NotesContext (Optimistic Updates)
│   ├── TodoContext (State Management)
│   ├── MindMapContext (Canvas State)
│   └── FlashCardContext (SRS Algorithm)
├── Custom Hooks
│   ├── useAuth - Authentication state
│   ├── useNotes - Notes CRUD operations
│   └── useTodos - Todo management
└── Components
    ├── Smart Components (Connected to Context)
    └── Presentational Components (Pure UI)

Backend Architecture:
├── RESTful API
├── JWT Authentication Middleware
├── MongoDB with Mongoose ODM
├── Error Handling Middleware
└── Input Validation & Sanitization
```


## 🎯 Core Features Demonstrated

### Authentication System
- Secure login/registration flow
- JWT token management
- Protected route guards
- Session persistence

### CRUD Operations
- Create, Read, Update, Delete for all entities
- Error handling with user feedback
- Loading states

### Rich Text Editing
- TipTap editor integration
- Formatting toolbar (Bold, Italic, Headings, Lists)
- Auto-save functionality
- Keyboard shortcuts (Ctrl+S)

### Spaced Repetition Algorithm
- SM-2 algorithm implementation
- Card scheduling system
- Study session tracking
- Progress analytics

---

## 📱 Screenshots Gallery

| Feature | Preview |
|---------|---------|
| **Dashboard (Light)** | ![Dashboard Light](./screenshots/dashboard-light.png) |
| **Dashboard (Dark)** | ![Dashboard Dark](./screenshots/dashboard-dark.png) |
| **Todo Management** | ![Todo](./screenshots/todo-view.png) |
| **Mind Map Canvas** | ![Mind Map](./screenshots/mindmap-canvas.png) |
| **Flashcard System** | ![Flashcards](./screenshots/flashcards-deck.png) |
| **Navigation Sidebar** | ![Sidebar](./screenshots/sidebar.png) |

---

## 📊 Project Metrics

- **Development Time:** 2+ months (ongoing)
- **Components:** 20+ React components
- **API Endpoints:** 40+ RESTful routes
- **Lines of Code:** 10,000+ (frontend + backend)
---


## 📞 Contact 

- 📧 Email: samjoel356@gmail.com
- 💼 LinkedIn: linkedin.com/in/joel-sam3/

## 📝 Development Notes

### What I Learned

- Building accessible, keyboard-navigable interfaces
- Working with MongoDB and Mongoose
- JWT authentication and protected routes
- Creating reusable component libraries

### Challenges Overcome

- Managing complex state across multiple features
- Creating a consistent design system
- Building accessible components

---

This project is for portfolio demonstration purposes.

**⭐ If you're interested in this project, feel free to reach out!**

*Last Updated: January 2026*
