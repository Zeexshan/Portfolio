# Zeeshan Khan - Portfolio Website

## Overview
This is a personal portfolio website for Zeeshan Khan, showcasing work in web development, graphic design, and video editing. The portfolio is built as a static HTML website with embedded CSS and JavaScript, featuring a modern glass-morphism design with automatic light/dark theme switching based on time of day.

## Project Details
- **Owner**: Zeeshan Khan
- **Type**: Static Portfolio Website
- **Technologies**: HTML5, CSS3, JavaScript
- **Design Style**: Glass-morphism with gradient backgrounds
- **Features**:
  - Responsive design for mobile, tablet, and desktop
  - Automatic theme switching (light mode 6 AM - 6 PM, dark mode otherwise)
  - Interactive project filtering (All, Web Projects, Graphics Projects)
  - Smooth animations and transitions
  - Profile section with contact information
  - Project galleries with external links

## Project Structure
```
.
├── portfolio/              # Main website directory
│   ├── index.html         # Main HTML file with embedded CSS/JS
│   ├── hi.png             # Profile image
│   ├── jojo.jpg           # Graphics project image
│   ├── t.jpg              # Graphics project image
│   ├── s.jpg              # Graphics project image
│   ├── n.jpg              # Graphics project image
│   ├── c.jpg              # Graphics project image
│   ├── o.jpg              # Graphics project image
│   ├── p.png              # Web project screenshot
│   ├── a.png              # Web project screenshot
│   └── r.png              # Web project screenshot
├── server.py              # Python HTTP server for development
└── replit.md              # Project documentation
```

## Development
The website runs on a Python HTTP server during development:
- **Server**: Python 3.11 SimpleHTTPServer
- **Port**: 5000
- **Host**: 0.0.0.0 (accessible from web preview)
- **Cache Control**: Disabled for development (no-cache headers)

## Deployment
Configured for static site deployment:
- **Type**: Static website
- **Public Directory**: `portfolio/`
- All static files are served directly from the portfolio folder

## Contact Information Featured
- Email: zixshankhan@gmail.com
- Instagram: @xnemesis_
- Phone: (+91) 6268719705
- YouTube: Beyond X Canon (1.2K+ subscribers)

## Project Highlights
### Web Development Projects
1. Programmers College Website (Live)
2. Admin Panel (Live)
3. Asset Rental Website (Live)

### Graphics Design Projects
1. Editing Tournament Posters (Runner Up - August 2023)
2. Tomie - Horror Poster Design (February 2023)
3. Stellar - Space Theme Design (October 2022)
4. Revolutionary Wars Poster (2024)
5. Professional GFX Designs (2024)

## Skills Showcased
- **Design Software**: Photoshop, Illustrator, Lightroom, Alight Motion
- **Web Development**: HTML/CSS, JavaScript, Bootstrap
- **3D**: Blender
- **Languages**: Hindi (Native), English (Professional), Urdu (Professional)

## Recent Changes
- **2025-11-19**: Project imported and set up in Replit environment
  - Fixed image filename case sensitivity issues
  - Configured Python HTTP server with cache control headers
  - Set up workflow for port 5000 webview
  - Configured static deployment settings
