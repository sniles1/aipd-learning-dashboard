# AIPD Learning Dashboard

An interactive web application for learning, referencing, and applying the AI Product Development (AIPD) Framework.

## Overview

The AIPD Learning Dashboard is designed to help users understand and implement the AIPD methodology for AI-assisted product development. It serves as both an educational tool and a lightweight project management system, allowing users to:

- Learn the AIPD Framework through interactive documentation
- Track projects through the seven AIPD phases
- Manage phase-specific checklists
- Receive contextual recommendations based on current development phase
- Maintain multiple concurrent product development efforts

Initially designed for personal use, the platform aims to eventually become a free community tool for anyone interested in AI-assisted product development.

## Features

### Core Features

- **AIPD Framework Reference**: Comprehensive, searchable access to AIPD documentation
- **Project Lifecycle Tracking**: Track projects through the seven AIPD phases with progress visualization
- **Interactive Checklists**: Phase-specific checklists with state persistence
- **Multi-Project Management**: Support for tracking multiple parallel development efforts
- **Contextual Recommendations**: Phase-appropriate tool and resource suggestions

### Technical Features

- **Local Storage**: Project data stored directly in your browser
- **No Backend Required**: Fully client-side application
- **Responsive Design**: Works on desktop and tablet devices
- **Offline Capable**: No internet connection required after initial load

## Technology Stack

- **Frontend Framework**: React
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **State Management**: React Context API with hooks
- **Storage**: Browser LocalStorage/IndexedDB
- **Deployment**: Vercel