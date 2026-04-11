# Philharmonia Orchestra Website

## Overview
A static landing page for the Philharmonia Orchestra's 2025–2026 season. It's a promotional and booking website featuring concert listings, ensemble information, a booking form, and venue details.

## Tech Stack
- **Language:** HTML5, CSS3, Vanilla JavaScript
- **Frameworks:** None
- **Fonts:** Google Fonts (Cormorant Garamond, Cinzel, Jost) via CDN
- **Build Tool:** None (pure static site)

## Project Structure
```
/
├── index.html                   # Main entry point (served by HTTP server)
├── philharmonia-orchestra.html  # Original source HTML file
└── replit.md                    # This file
```

## Development
The site is served using Python's built-in HTTP server on port 5000:
```
python3 -m http.server 5000 --bind 0.0.0.0
```

## Deployment
Configured as a static site deployment with the project root as the public directory.
