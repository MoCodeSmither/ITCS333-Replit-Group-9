# ITCS333 Web Development Course Website

## Overview
This is a static HTML website for an Internet Software Development course (ITCS333). The project serves as a learning platform with various sections for students and administrators.

**Current State:** Project successfully configured to run in Replit environment
**Last Updated:** October 17, 2025

## Project Architecture

### Technology Stack
- **Frontend:** Pure HTML5/CSS3
- **Server:** Python HTTP Server (serving static files)
- **Port:** 5000 (frontend)

### Project Structure
```
/
├── index.html              # Main homepage with navigation
├── src/
│   ├── admin/
│   │   └── manage_users.html
│   ├── assignments/
│   │   ├── admin.html
│   │   ├── details.html
│   │   └── list.html
│   ├── auth/
│   │   └── login.html
│   ├── common/
│   │   └── styles.css
│   ├── discussion/
│   │   ├── baord.html     # Note: typo in original filename
│   │   └── topic.html
│   ├── resources/
│   │   ├── admin.html
│   │   ├── details.html
│   │   └── list.html
│   └── weekly/
│       ├── admin.html
│       ├── details.html
│       └── list.html
└── assets/                 # Images and other static assets
```

### Key Features
- **Student Pages:** View resources, weekly breakdown, assignments, discussion board
- **Admin Pages:** Manage users, resources, weekly content, and assignments
- **Authentication:** Login page for secure access

## Development Setup

### Running the Website
The website is configured to run automatically using the Python HTTP server:
- Command: `python -m http.server 5000 --bind 0.0.0.0`
- The server serves static files from the root directory
- Access via the webview panel in Replit

### Workflow Configuration
- **Name:** Server
- **Port:** 5000
- **Output:** Webview (displays website preview)

## Recent Changes
- **2025-10-17:** Initial Replit environment setup
  - Installed Python 3.11 module
  - Configured HTTP server workflow on port 5000
  - Created .gitignore for Python
  - Created project documentation

## Notes
- This is a static website with no backend functionality
- All pages are currently templates with TODO comments for students to complete
- The project appears to be a learning assignment where students fill in the HTML structure
