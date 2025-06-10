# CLAUDE.md
日本語で答えて！！

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Japanese web application collection featuring static HTML pages with embedded JavaScript functionality. The project consists of:

- **Tetris Game** (`tetris.html`) - Full-featured Tetris implementation with canvas-based rendering
- **Tetris Ranking System** (`tetris-ranking.html`) - Score tracking and leaderboard with localStorage persistence
- **Contact Form** (`contact.html`) - Multi-field contact form with validation
- **Login Form** (`login.html`) - Simple authentication interface
- **Search Interface** (`search.html`) - Basic search functionality with sample data
- **Notice Board** (`notice.html`) - Announcement display system with categorized notices

## Architecture

Each HTML file is completely self-contained with:
- Embedded CSS styling in `<style>` tags
- JavaScript functionality in `<script>` tags
- No external dependencies or build process
- Japanese language UI throughout

The Tetris game uses HTML Canvas for rendering and implements:
- Complete game logic with piece rotation, line clearing, and scoring
- Level progression system
- Game over handling and restart functionality

The ranking system uses localStorage for persistence and includes:
- Score registration and validation
- Statistical calculations (average, highest score)
- Dynamic ranking display with medal indicators

## Development Notes

- All pages are designed for desktop and mobile responsiveness
- The project uses vanilla JavaScript with no frameworks
- Styling follows consistent color schemes and modern CSS practices
- Form validation is implemented client-side
- Data persistence only exists in the ranking system via localStorage

## Testing

Since this is a static HTML project with no build system, testing is done by:
- Opening HTML files directly in a web browser
- Testing interactive features manually
- Verifying responsive design across different screen sizes