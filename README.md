# Northstar CLM

Northstar CLM is a browser-based demo for a contract lifecycle management (CLM) experience. It presents a fictional legal operations workspace with workflow tracking, contract repository management, templates, clause libraries, and guided contract creation.

## Overview

This project is a static front-end application built with plain HTML, CSS, and JavaScript. It simulates a modern CLM dashboard where users can:

- view a workspace overview
- create and manage contract workflows
- review contract repository records
- use reusable templates
- browse and manage clause library entries
- configure workspace settings
- interact with modal dialogs and mock workflows

## Features

- Dashboard with workflow statistics and recent activity
- Workflow management with filtering, search, and pagination
- Contract repository with searchable table and saved views
- Guided workflow creation wizard
- Document upload and review interactions
- Clause library and standard templates
- Local browser-based persistence using localStorage
- Responsive layout for desktop and mobile screens

## Project Structure

- `index.html` — app shell and main layout
- `styles.css` — all visual styling and responsive behavior
- `script.js` — application logic, mock data, rendering, modals, and interactions

## How to Run

Because this is a static site, you can serve it locally with any simple web server.

### Option 1: Python

From the project folder, run:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

### Option 2: Node.js

If you prefer Node, you can also use a local static server such as `npx serve`:

```bash
npx serve .
```

Then open the local address shown in the terminal.

## Notes

- The app uses browser localStorage to persist demo data between reloads.
- This is a front-end prototype/demo and does not connect to a real backend or external API.
- Many actions are simulated UI interactions designed to demonstrate CLM workflows rather than process live legal data.

## Use Cases Demonstrated

- Legal workflow initiation
- Contract approval tracking
- Signature packet preparation
- Version/document review
- Repository governance
- Template-based workflow creation

## Browser Support

This app is designed for modern desktop browsers and should work well in Chrome, Edge, and Firefox.

## License

This project is intended for demo and educational use.
