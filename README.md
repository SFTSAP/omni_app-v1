# OMNI Electric — Mobile EV Charging Request App

This project is a single-page web app for **OMNI Electric’s on-demand mobile EV charging service**.  
It allows customers to request a mobile charger and provides an internal admin dashboard for staff to review and manage requests.

## What this app does

- Public landing page explaining OMNI’s mobile EV charging service
- “Request a Charger” multi-step form (no login required)
- Confirmation screen after form submission
- Internal admin dashboard to:
  - View incoming requests
  - Filter by status, site type, or search
  - Update request status and internal notes

⚠️ Note: This is a **front-end demo**. Data is stored in-memory (JavaScript only) and resets on refresh.

## How to run the app

1. Download or clone this repository
2. Open `index.html` in any modern web browser (Chrome, Edge, Firefox)
3. No build tools, servers, or installs required

## Tech stack

- HTML
- CSS (embedded in the file)
- Vanilla JavaScript
- No frameworks or external dependencies

## Project structure

- `index.html` — contains all markup, styles, and logic in one file
- `README.md` — project overview and instructions

## Intended use

This project is intended as:
- A product demo / prototype
- A UI + UX reference
- A foundation to later connect to a real backend (Supabase, Firebase, etc.)

## Future improvements (optional)

- Connect form submission to a real database or API
- Add authentication to protect the admin dashboard
- Persist data across sessions
- Deploy via GitHub Pages or another hosting service
