# Contact List Application

A modern, responsive contact management application built with React, TypeScript, and Tailwind CSS. This project demonstrates advanced frontend development practices, state management, and exceptional user experience.

##  Live Demo

[View Live Demo](https://contact-list-chi-hazel.vercel.app/)

##  Key Features

###  Contact Management
-  Add new contacts with smart form validation
  - Real-time duplicate detection for name, email, and phone
  - Automatic avatar generation based on names
  - Custom error handling and feedback
-  Edit existing contacts with live validation
  - Click-to-call phone numbers
  - Click-to-email functionality
-  Delete contacts with confirmation dialog
-  Persistent storage with automatic saving

###  Smart Search & Organization
-  Intelligent search across name, email, or phone
  - Switch search type on the fly
  - Case and space-insensitive matching
  - Debounced search for performance
-  Smart phone number search
  - Matches any format: `+1 (234) 567-8900`, `1234567890`
  - Ignores spaces, dashes, and parentheses
-  Favorites system with quick filtering
-  Sort contacts alphabetically (A-Z/Z-A)

###  Modern UI/UX
-  Dark/Light theme with system preference detection
-  Responsive design optimized for:
  - Mobile devices (stacked layout)
  - Tablets (2-column grid)
  - Desktop (3-column grid)
-  Polished interactions
  - Loading skeletons during data fetch
  - Smooth transitions and animations
  - Hover effects and visual feedback
-  Contextual empty states
  - Empty contact list guidance
  - No search results messaging
  - No favorites indication

##  Tech Stack

- **Frontend**: React 18 with TypeScript
- **Styling**: Tailwind CSS with dark mode support
- **Components**: Headless UI for accessibility
- **Icons**: Heroicons
- **Build**: Vite for optimal development experience
- **Performance**: Debounced search, optimized re-renders

##  Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation
1. Clone and enter the repository:
   ```bash
   git clone https://github.com/Ishan03-25/ContactList.git
   cd ContactList
   ```

2. Install dependencies and start:
   ```bash
   npm install
   npm run dev
   ```

Visit `http://localhost:5173` to view the application.

##  Project Structure

```
src/
├── components/     # Reusable UI components
├── contexts/      # React contexts (theme, etc.)
├── types/         # TypeScript definitions
├── utils/         # Helper functions
├── App.tsx        # Main application
└── main.tsx       # Entry point
```

##  Design Choices

### UI/UX Focus
- Clean, minimalist design prioritizing readability
- Responsive grid adapting to screen sizes
- Smooth animations for better user feedback
- Accessible components with keyboard support
- Clear visual hierarchy and consistent spacing

### Technical Architecture
- Modular component design
- TypeScript for type safety
- Local storage for persistence
- Optimized search with normalization
- Smart form validation and error handling

##  Future Enhancements

- [ ] Contact groups/categories for better organization
- [ ] Cloud sync and backup functionality
- [ ] Contact import/export capabilities
- [ ] Rich contact details with notes and custom fields
