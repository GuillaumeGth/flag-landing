# flag-landing — CLAUDE.md

## Context

This is the **marketing website** for **Fläag**, a geolocated messaging mobile app.
The mobile app source lives at `/Users/guillaumezarb/Documents/GitHub/flag-project`.

## What is Fläag?

Fläag is a geolocated messaging app. Users leave messages anchored to GPS coordinates — messages can only be read when you're physically near the drop point. Combines map discovery, proximity notifications, and private/public messaging.

## App Details

- **Bundle ID (iOS)**: `com.flagapp.app`
- **Package (Android)**: `com.flagapp.app`
- **Version**: 1.0.0
- **Platforms**: iOS & Android
- App Store links: TBD (placeholders in HTML)
- Support email: support@flaag.app (placeholder)

## Design System

Pulled directly from `src/theme-redesign.ts` in the mobile app:

### Colors
- Background primary: `#0A0A12` (deep space black)
- Background secondary: `#12121D`
- Surface elevated: `#1E1E2D`
- Primary accent: `#A78BFA` (medium purple / violet)
- Primary light: `#C4B5FD`
- Primary dark: `#7C3AED`
- Accent lavender: `#D8B4FE`
- Text primary: `#FFFFFF`
- Text secondary: `#B8B8D0`
- Text muted: `#7A7A95`
- Border default: `rgba(167, 139, 250, 0.2)`
- Border glow: `rgba(167, 139, 250, 0.45)`
- Success: `#5FD68A`
- Warning: `#FFA94D`
- Error: `#FF5C7C`

### Gradients
- Button: `#A78BFA` → `#8B5CF6` → `#7C3AED` → `#6D28D9` → `#5B21B6`
- Hero: `#D8B4FE` → `#A78BFA` → `#7C3AED`
- Glow: `rgba(167, 139, 250, 0.3)` → `rgba(124, 58, 237, 0.3)`

### Style
- Glassmorphism (backdrop-filter: blur + semi-transparent background)
- Dark theme only
- Purple accent throughout
- "Neo-Cartographic" / premium exploration aesthetic

## Website Structure

```
flag-landing/
├── index.html     # Main landing page
├── cgu.html       # Terms of Service (CGU)
└── CLAUDE.md      # This file
```

## Landing Page Sections

1. **Hero** — App name, tagline, store download buttons
2. **Features** — 3-4 key features with icons
3. **How it works** — Simple 3-step explanation
4. **Download** — App store CTAs
5. **Support** — Contact form / email link
6. **Footer** — CGU link, copyright

## Key Constraints

- Pure HTML/CSS/JS (no build step, no framework)
- Single file per page (self-contained)
- Mobile-responsive
- Dark theme matching app design system
- French language (app is French-first)
- Store links are placeholders until app is published
