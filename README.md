# Careway — Home Care Workflow Prototype

An interactive concept demonstration created with AI assistance. This is a prototype, not a previously delivered client system or production healthcare platform.

## Run locally

Open `dist/index.html` in a modern web browser. No installation, API keys, dependencies, or build step is required.

Alternatively, run `python -m http.server 8000 --directory dist` and open http://localhost:8000.

## Features

- Fictional client intake and editable care profiles
- Weekly scheduling and caregiver assignments
- Drag-and-drop rescheduling and overlap checks
- Responsive caregiver view with simulated check-in/check-out
- Required task checklist and visit notes
- Dashboard counts and session activity

## Walkthrough

1. Add a fictional client under Clients & intake.
2. Schedule a visit for September 17, 2026, using a free time for the client and caregiver.
3. Switch to Caregiver view and select the assigned caregiver.
4. Start the simulated visit, complete all tasks, add a note, and check out.
5. Return to Overview to see the status change.

The demo calendar is intentionally fixed to September 14–18, 2026. All edits exist only in page memory and reset on refresh.

## Limitations

Use fictional information only. There is no backend, authentication, persistent storage, real location verification, state EVV integration, billing, claims submission, payroll, or native mobile app. This prototype makes no HIPAA or state EVV compliance claim. Role switching is a demonstration control, not access enforcement.

## Files

- `dist/index.html` — page shell
- `dist/style.css` — responsive styles
- `dist/app.js` — sample data and interactive workflows
