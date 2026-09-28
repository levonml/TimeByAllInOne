# Time By All In One

Monorepo with:
- Node.js/Express API (root)
- React client (`Timeby/`)

## About the project
Time By All In One is a personal storytelling app where people can build a timeline of their life, ideas, or memories year by year. Instead of writing everything in one long document, users can organize their story into separate years and add short text entries to each one.

The project is built with:
- React for the website interface
- Redux for managing app data on the client side
- Node.js and Express for the server
- MongoDB with Mongoose for storing user accounts and timeline content

At a high level, the app lets people:
- create an account and sign in securely
- view a timeline made of separate years
- add new years to their timeline
- write text entries for a selected year
- delete text entries or remove an entire year page
- see a list of other users in the app

## Quick start
```bash
npm install
npm run dev
```

## Useful scripts
- `npm test` — run backend tests
- `npm run lint` — lint backend
- `npm run build:ui` — build React app and copy output to root `/build`
