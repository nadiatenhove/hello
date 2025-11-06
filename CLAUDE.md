# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static HTML resume/portfolio website for Nadia ten Hove (Creative Concept Developer). The entire website is contained in a single HTML file with embedded CSS.

## Architecture

**Single-page application:**
- [index.html](index.html) - Complete standalone HTML document with embedded styles
- All CSS is inline within `<style>` tags (lines 10-540)
- No external JavaScript or CSS dependencies
- Self-contained design with no build process required

**Design approach:**
- Uses organic shapes and morphing animations for visual interest
- Bento grid layout system for content organization
- Three Google Fonts imported: Inter, Playfair Display, Space Grotesk
- Burgundy (#800020) accent color throughout
- Print styles included for PDF generation (lines 362-512)

## Key Design Features

**Hero section** (lines 31-91):
- Animated morphing profile image with organic border-radius
- Floating decorative shapes using CSS animations

**Bento grid layout** (lines 134-193):
- 6-column responsive grid system
- Organic shape variations for different cards (using border-radius)
- Hover effects for interactive elements

**Print optimization** (lines 362-512):
- Preserves colors and styling when printing to PDF
- Adjusted spacing and sizing for paper format
- Forced page breaks for proper layout

## Viewing the Website

Open [index.html](index.html) directly in a web browser - no server or build process needed.

For PDF export: Use browser print (Cmd+P / Ctrl+P) with print styles automatically applied.

## Content Sections

1. **Hero** - Name, title, contact info with profile photo
2. **Skills** (Kerncompetenties) - Core competencies displayed as interactive bubbles
3. **Education** (Opleiding) - Academic background
4. **Tools & Languages** - Adobe Suite and language proficiencies
5. **Experience** (Ervaring) - Three professional roles with organic card styling

## Responsive Design

- Desktop-first approach (1600px max-width container)
- Mobile breakpoint at 1200px switches to single column layout
- All organic shapes and animations preserved across viewports
