# Hatem Kthiri - Portfolio Website

## Overview
A clean, modern portfolio landing page for Hatem Kthiri, a Gomycode Instructor & Full Stack JavaScript Developer. This is a static HTML website with embedded CSS, featuring a responsive design with gradient background and call-to-action button.

## Project Structure
- `standalone.html` - Main HTML file with embedded CSS and responsive design

## Technology Stack
- Pure HTML5 and CSS3
- No dependencies or build system required
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
- **October 3, 2025**: Initial import and setup in Replit environment
  - Configured Python HTTP server workflow
  - Set up deployment configuration for autoscale
  - Verified website loads correctly with all styling intact
