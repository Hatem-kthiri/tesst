# Hatem Kthiri - Portfolio Website

## Overview
A clean, modern portfolio website for Hatem Kthiri, a Gomycode Instructor & Full Stack JavaScript Developer. Features a responsive landing page and an animated contact form. Static HTML website with embedded CSS and Tailwind CSS for the contact page.

## Project Structure
- `standalone.html` - Main landing page with embedded CSS and responsive design
- `contact.html` - Contact page with Tailwind CSS, animated form fields (name, email, textarea)

## Technology Stack
- Pure HTML5 and CSS3
- Tailwind CSS (CDN) for contact page
- Custom CSS animations and keyframes
- Python HTTP server for serving static files

## Development
The project uses Python's built-in HTTP server to serve the static HTML file on port 5000.

### Running Locally
The server is configured to run automatically via the workflow:
```bash
python -m http.server 5000 --bind 0.0.0.0
```

## Deployment
Configured for autoscale deployment using Python's HTTP server. The website is stateless and scales automatically based on traffic.

## Recent Changes
- **October 3, 2025**: Added contact page with animations
  - Created contact.html with Tailwind CSS
  - Implemented animated form with name, email, and message fields
  - Added creative animations including floating elements, gradient shifts, and staggered fade-in effects
  - Updated main page button to link to contact page
- **October 3, 2025**: Initial import and setup in Replit environment
  - Configured Python HTTP server workflow
  - Set up deployment configuration for autoscale
  - Verified website loads correctly with all styling intact
