# Soundcheck -- Project Summary

## What we built
A static single-page music player for showcasing AI-generated tracks. No framework, no build step -- just `index.html` + `tracks.json` + media files.

## Current state

**Repo:** [github.com/silkelc/soundcheck](https://github.com/silkelc/soundcheck) (public)
**Vercel:** Connected via GitHub -- auto-deploys on every push

**Tracks:**
1. **Too many thoughts - echoes of self** -- Suno
2. **Too many thoughts - remix layering** -- ElevenLabs

## Changes made (2026-05-23 session)

- Created `tracks.json` (was missing)
- Renamed: Aria to Soundcheck, Queue to Tracks
- Added full tagline: "Generative AI for Sound & Music - Showcase Silke Sonnenberg"
- Aligned details section with player on desktop
- Made scroll hint more prominent (pill button with pulse animation)
- Fixed mobile sliders (touch events + `touch-action: none` + larger tap targets)
- Added spacing between controls
- Removed diamond icon from tool badge
- Scaled down detail headline for longer text
- Added paragraph support (`white-space: pre-line`) for description + reflection
- New cover image for track 1 (shared by both tracks)
- Full metadata for both tracks (description, prompt, tool, reflection)

## Adding a new track

1. Drop audio into `tracks/`
2. Drop cover into `covers/`
3. Add entry to `tracks.json`
4. `git add . && git commit && git push` -- Vercel auto-deploys

## What's next

- Add more tracks
- Design tweaks
- Vercel CLI install (optional -- currently deploying via GitHub integration)
