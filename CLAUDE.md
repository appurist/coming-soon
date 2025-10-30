# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple "Coming Soon" landing page collection with three self-contained HTML variations:

- `index.html` - Basic version (currently active)
- `index-basic.html` - Minimal design with just title and description
- `index-contact.html` - Includes email signup form
- `index-countdown.html` - Features countdown timer and email signup

## Architecture

- **Self-contained HTML files**: Each variation is a complete, standalone HTML page with embedded CSS and JavaScript
- **No build process**: Pages can be opened directly in browsers or served by any web server
- **Responsive design**: All variations include mobile-responsive CSS using flexbox and media queries
- **Shared design system**: Consistent gradient background (#667eea to #4ba272), typography (Segoe UI), and glassmorphism effects

## File Structure

The main file is `index.html` which currently contains the basic version. The other files are alternative implementations:

- Basic version: Simple coming soon message
- Contact version: Adds email collection form with client-side validation
- Countdown version: Includes 30-day countdown timer that updates every second

## Development

Since this is a static HTML project:
- Open files directly in browser for testing
- No package manager or build tools required
- Modifications involve editing HTML, CSS, and JavaScript directly within the files
- To switch versions, copy desired variation content to `index.html`

## Styling Patterns

- Uses CSS custom properties for consistent theming
- Glassmorphism effects with `backdrop-filter: blur(10px)` and semi-transparent backgrounds
- Responsive breakpoint at 768px for mobile optimization
- Consistent spacing using rem units