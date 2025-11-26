# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for Moonloch Games, hosted on GitHub Pages at moonlochgames.com. It's a single-page landing site for a tabletop RPG and video game company.

## Tech Stack

- **Single HTML file** (`index.html`) - no build process required
- **Tailwind CSS** via CDN with inline configuration
- **Google Fonts**: Cinzel (headings) and Lora (body text)
- **GitHub Pages** deployment (via CNAME)

## Development

Open `index.html` directly in a browser or use any local server. No npm/build steps needed.

## Design System

Custom Tailwind colors defined inline:
- `moonloch-dark`: #1a1a1a
- `moonloch-darker`: #0f0f0f
- `moonloch-cream`: #f5f0e6
- `moonloch-gold`: #c9a959
- `moonloch-muted`: #8b8b7a

Custom CSS classes: `.font-cinzel`, `.font-lora`, `.bg-texture`, `.glow`, `.text-shadow`, `.card-hover`

## Image Assets

- `moonloch-games-logo.png` - Main hero logo
- `moonloch-games-image.webp` - Compact version for nav/footer
- `moonloch-games-text.svg` - Text-only logo
