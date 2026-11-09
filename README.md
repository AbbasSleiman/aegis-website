# Aegis Website

## Overview

Aegis is the starting point for a web application flow. The current page presents a single “Start application” action. The supporting code sets up a Next.js App Router layout, a reusable button, and a typed Redux Toolkit store with an empty reducer map. The project is at the foundation stage, with the application steps still to be built.

## How it’s built

- **Page and layout.** [The entry page](app/page.tsx) contains the initial action, and the root layout sets up shared styling and fonts.
- **Reusable UI.** [The button component](components/ui/button.tsx) brings styling and variants into one place using the project’s shadcn and Tailwind setup.
- **State setup.** [The store factory](lib/store.ts) defines the store and TypeScript types for future state slices.

## Run or explore locally

Run `npm install` and `npm run dev` from the repository root. Open `http://localhost:3000` to view the entry screen.
