# Portfolio Website

## Overview
A personal portfolio website for Sridhar, a Mainframe Developer and Digital Marketing Manager. Built with vanilla JavaScript and Webpack, featuring a modern dark theme with purple accents.

**Live Site**: Originally hosted at eliasdevis.github.io  
**Figma Design**: https://www.figma.com/community/file/1164933568884615740

## Project Structure
- **Frontend Only**: Single-page application (SPA) with client-side routing
- **Build System**: Webpack 5 with development server
- **Package Manager**: Bun
- **Styling**: Sass/SCSS
- **Languages**: Vanilla JavaScript (ES6+)

## Key Features
- Client-side routing with history API
- Multi-language support (EN, RU, UA)
- Responsive design
- Project showcase
- Skills and about sections
- Contact information

## Development Setup
The project is configured to run on Replit with the following setup:
- **Dev Server**: Port 5000 (bound to 0.0.0.0)
- **Allowed Hosts**: All (configured for Replit proxy)
- **Workflow**: `bun run serve` starts the development server

## File Structure
```
src/
├── app/              # JavaScript application code
│   ├── blocks/       # Page sections
│   ├── components/   # Reusable components
│   ├── consts/       # Constants and data
│   ├── helpers/      # Utility functions
│   ├── proxies/      # Data proxies
│   └── views/        # Page views
├── assets/
│   ├── fonts/        # Fira Code font family
│   ├── images/       # Images and icons
│   ├── locales/      # Translation files
│   └── styles/       # Sass stylesheets
└── templates/        # EJS templates
```

## Available Scripts
- `bun run serve` - Start development server
- `bun run build` - Build for production

## Recent Changes (November 10, 2025)
- Migrated from GitHub to Replit
- Removed deprecated `node-sass` dependency (using `sass` instead)
- Configured Webpack dev server for Replit environment:
  - Changed port from 9000 to 5000
  - Set host to 0.0.0.0
  - Enabled `allowedHosts: 'all'` for proxy compatibility
- Set up workflow for automatic server management

## Notes
- Sass deprecation warnings are present but don't affect functionality
- The project uses legacy Sass `@import` statements (to be migrated to `@use` in future)
- No backend or database required
