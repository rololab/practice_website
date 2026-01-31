# Feed Me - Static Website

## Overview
A simple static HTML/CSS website with a password-protected meme page. The site features:
- Password gate page (password: "pizza")
- Protected meme page with a hungry cat image
- Elegant dark theme styling

## Project Structure
```
.
├── index.html      # Password gate entry page
├── meme.html       # Protected meme content page
├── style.css       # Shared styling
├── assets/
│   └── images/     # Image assets (cat_hungry.jpeg)
├── .gitignore      # Python gitignore
└── replit.md       # This file
```

## Running the Project
The site is served using Python's built-in HTTP server on port 5000.

**Workflow Command:** `python -m http.server 5000 --bind 0.0.0.0`

## Deployment
Configured as a static site deployment with the root directory (`.`) as the public directory.
