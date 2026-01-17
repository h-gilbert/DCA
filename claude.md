# CALC Portfolio

## Project Overview
Static frontend application for THORChain/Rujira portfolio tracking and analytics.

## Tech Stack
- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Build**: None (static files)

## Port Configuration

| Service | Port | Description |
|---------|------|-------------|
| Static Server | Any | No built-in server |

## Running Locally

Simply open `index.html` in a browser, or use any static server:

```bash
# Python
python -m http.server 8001

# Node.js
npx serve -p 8001

# PHP
php -S localhost:8001
```

**Recommended port**: 8001 (to avoid conflicts)

## Project Structure
```
calc-portfolio/
├── index.html           # Landing page
├── portfolio.html       # Portfolio tracker (WIP)
├── styles.css          # Styling
└── dist/               # Distribution copies
```

## External Services
- THORChain (blockchain protocol)
- Rujira.network (DCA automation)
- CALC Finance (portfolio analytics)

## Notes
- No backend required
- No database
- No Docker
- Currently in Phase 1: Foundation
- All calculations performed client-side
