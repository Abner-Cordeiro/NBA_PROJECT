# Baseline — the season, in focus

The 2026–27 NBA season is getting underway, and Baseline is my excuse to revisit the film room. It is a fan-made scouting desk built around a 2024–25 season archive: player numbers, playoff storylines and the little details that make a game worth watching. Think of it as a concept for how I would explore a season, not a live scores service.

I wanted the interface to feel closer to a calm analyst’s workspace than another scoreboard: a playoff spotlight, a small league pulse chart, a searchable and sortable player shortlist, and a game-center preview. The sample fixtures and a few dashboard metrics are illustrative; they are labelled as demo data in the UI. Player stats reference the 2024–25 season.

## Run locally

```bash
npm install
npm run dev
```

## What is inside

- React with strict TypeScript and typed player/game data
- Search, derived sorting and saved-player UI state
- Responsive dashboard layout, mobile navigation and reduced-motion support
- A lightweight chart and court illustration built with CSS
- Vite production build

## Privacy and external assets

Baseline does not collect or transmit form input. Player headshots load from the NBA CDN and fonts load from Google Fonts, so opening the page makes requests to those services. The page sets a `no-referrer` policy. No API keys, credentials or private configuration are required.

## Stack

React · TypeScript · Vite · Lucide · CSS
