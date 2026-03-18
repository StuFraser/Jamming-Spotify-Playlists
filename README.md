# Jamming

A Spotify playlist manager built with React, developed as part of the Codecademy Full-Stack Developer certification path — then taken a bit further.

## What it does

- Search for tracks using the Spotify API
- Preview results with album artwork
- Build and save playlists directly to your Spotify account
- Full Spotify OAuth authentication flow

## What I extended beyond the project spec

The main addition beyond the base project requirements was implementing a proper Spotify OAuth flow rather than the simplified token approach. This involved handling the authorisation redirect, exchanging tokens, and managing authenticated API requests. Album artwork is also displayed alongside search results to give it a more polished feel.

## Tech Stack

- React
- JavaScript
- Vite
- Spotify Web API
- Spotify OAuth 2.0

## Getting Started

### Prerequisites

- Node.js and npm
- A Spotify account
- A registered Spotify Developer app (for your Client ID)

### Setup

1. Clone the repo
2. Create a Spotify Developer app at [developer.spotify.com](https://developer.spotify.com) and grab your Client ID
3. Add your Client ID and set your redirect URI in the config
4. Install dependencies and run

```bash
npm install
npm run dev
```

Then open your browser at `http://localhost:5173` and log in with Spotify.

## Status

Mostly complete — core functionality is working.
