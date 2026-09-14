# Shift Schedule Space

An interactive 3D schedule explorer for Shift 2026. Talks are displayed as blocks across conference stages, making overlapping sessions and peak concurrency easy to spot.

## Features

- Switch between conference days.
- Move the time cursor to see which talks are live.
- Orbit and zoom the 3D timeline.
- Select a talk to inspect overlapping sessions.
- Responsive layout for desktop and mobile.

## Getting started

Requirements: Node.js 20+ and npm.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite, usually `http://localhost:5173`.

## Available scripts

```bash
npm run dev      # Start the development server
npm run build    # Type-check and create a production build
npm run preview  # Preview the production build locally
npm run lint     # Run ESLint
```

## Data

The schedule is loaded from [`.canvas-data.json`](./.canvas-data.json) at build time. Update that file to change the conference sessions shown in the app.

## Tech stack

React, TypeScript, Vite, Three.js, and the React Compiler.
