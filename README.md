# ScreenScout

## Project Overview
ScreenScout is a web platform designed to help moviegoers find the absolute best theatrical experience. It aggregates and compares granular movie theater data—specifically screen sizes, aspect ratios, and premium projection technologies—that theaters typically hide or obscure. 

**Primary Goal:** Allow users to filter theaters by specific premium formats (IMAX, Dolby Cinema, Laser) and visually compare screen sizes and aspect ratios to make informed ticket-buying decisions.

## AI Context Note
*Note to AI coding assistants: The creator of this project is a beginner to this specific tech stack. Please provide complete, detailed instructions, explain the "why" behind architectural decisions, and assume a basic level of underlying programming knowledge but a beginner level for these specific frameworks.*

## Core Features
- **Visual Screen Comparator:** A UI tool that visually demonstrates the difference between screen sizes and aspect ratios (e.g., 1.43:1 vs 1.90:1 vs 2.39:1).
- **Premium Format Filtering:** Filter local theaters by True IMAX, Digital IMAX, Dolby Cinema, Standard, 70mm, and Laser projection.
- **Interactive Theater Map:** A map interface (Google Maps API) showing theater locations with their top screen specs.
- **Theater Rankings & Recommendations:** Scoring theaters based on screen tech, sound systems, and user preferences.

## Tech Stack
**Frontend:**
- Next.js (React Framework - App Router)
- TypeScript
- Tailwind CSS (for styling)

**Backend:**
- FastAPI (Python)
- PostgreSQL (Database for storing theater/screen specs)

**Integrations:**
- Google Maps API (Location/Mapping)
- OpenAI API (For processing/scraping theater data or powering smart recommendations)