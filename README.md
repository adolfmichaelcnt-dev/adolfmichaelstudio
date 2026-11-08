# ADOLF MICHAEL STUDIO

Turning Ideas Into Impact.

This repository contains the editable Vite source for the public portfolio and private project dashboard.

## Project location
The Vercel project Root Directory is `src`.

## Local development
1. Open the `src` folder.
2. Install dependencies with `npm install`.
3. Start the local server with `npm run dev`.
4. Build with `npm run build`.

## Pages
- `src/index.html` — public portfolio
- `src/admin.html` — private admin dashboard

## Admin media
- Image projects and thumbnail uploads
- MP4 uploads (50 MB maximum on the current Supabase bucket)
- YouTube and Vimeo links
- Draft / Publish, edit and delete

## Backend security
The frontend uses only the Supabase publishable key. Project writes and Storage uploads are restricted by Supabase RLS to the studio admin email. Never add a service-role key to frontend code.

The full self-contained source ZIP includes the original logo asset. This GitHub copy references the currently hosted logo URL so the repository remains buildable without storing a binary asset in Git.
