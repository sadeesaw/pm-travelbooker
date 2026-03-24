# TravelBooker

TravelBooker is a modern, AI-powered travel booking platform designed to simplify how users plan and manage their journeys. This project was developed as part of an undergraduate BIS program, focusing on building an interactive, user-friendly web application using core frontend technologies.

## Overview

The platform enables users to explore travel packages, manage bookings, coordinate group trips, and track expenses in a single interface. It combines intuitive design with practical features such as real-time pricing and smart search capabilities.

## Key Features

### Core Functionality

* AI-based travel assistant for answering queries and guiding users
* Access to 4,000+ curated travel packages across global destinations
* Advanced search and filtering by destination, budget, duration, and travel type
* Group booking coordination for families, teams, and large groups
* Real-time pricing with dynamic updates
* User dashboard for managing bookings and preferences

### Travel Management Tools

* Budget tracking with detailed expense breakdowns
* Split payment functionality for group travel
* Corporate booking support with approval workflows and invoicing
* Multi-language support for wider accessibility

### Package Categories

* Solo travel packages with flexible itineraries
* Family-oriented travel experiences
* Group travel plans with shared management tools

## Getting Started

### Prerequisites

* A modern web browser (Chrome, Firefox, Safari, or Edge)
* A local development server

### Installation

1. Download or clone the repository
2. Navigate to the project directory
3. Start a local server:

```bash
# Python
python -m http.server 8000

# Node.js
npx http-server -p 8000

# PHP
php -S localhost:8000
```

4. Open your browser and visit:

```
http://localhost:8000
```

## Project Structure

```
travel-booker/
├── index.html
├── styles.css
├── app.js
└── Code Citations.md
```

## Technologies Used

* HTML5
* CSS3 (Grid and Flexbox)
* JavaScript (ES6+)
* Google Fonts (Playfair Display, DM Sans)
* Unsplash API for images
* Inline SVG icons

## Design Approach

The interface follows a clean and modern design system with:

* A consistent color palette based on green tones
* Clear typography hierarchy using serif and sans-serif combinations
* Responsive layouts optimized for desktop, tablet, and mobile devices
* Reusable components such as cards, modals, and forms

## Implementation Highlights

### Frontend Architecture

* Single-page application structure
* Client-side routing using the History API
* Dynamic content rendering

### Data Handling

* JSON-based structure for travel packages
* Real-time filtering, sorting, and search functionality
* Package comparison features

### User Experience

* Responsive design across all screen sizes
* Accessibility considerations (ARIA labels, keyboard navigation)
* Loading states and error handling

## Sample Data Model

```javascript
{
  id: number,
  title: string,
  region: string,
  dest: string,
  duration: number,
  price: number,
  rating: number,
  reviews: number,
  img: string,
  badge: string,
  discount: object,
  desc: string,
  includes: array,
  highlights: array,
  itinerary: array,
  reviewsList: array
}
```

## Purpose

This project was developed as part of an academic assignment in a Bachelor of Information Systems program. It demonstrates frontend development skills, UI/UX design principles, and the implementation of interactive web application features.

## Future Improvements

* Backend integration for real-time data persistence
* Authentication and user account management
* Payment gateway integration
* Enhanced AI assistant capabilities
* API-based live travel data

## License

This project is intended for educational use. Refer to the code citations file for third-party resources and licensing details.
