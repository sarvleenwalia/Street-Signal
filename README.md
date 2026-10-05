# Street Signal

**Public gatherings, on your map.**

Street Signal is a public events map for finding organizer-announced protests, rallies, marches, and vigils. It makes public event details easier to browse while respecting participants’ privacy.

**Live site:** https://sarvleenwalia.github.io/Street-Signal/

## What it does

- Shows a map and event list with public venues, dates, times, and source links.
- Lets visitors search events and filter by country.
- Accepts a Google Maps JavaScript API key for the current browser session only; it does not save the key.
- Keeps event suggestions in the visitor’s browser; they are not sent to a shared database.
- Does not request GPS access, create accounts, or track participants.

## Event information

Listings are a snapshot, not a complete or real-time feed. Event details can change, and a source link does not guarantee that an event is still happening. Check the linked organizer or source before travelling. Community-submitted listings are unverified. Events without a confirmed public meeting point should not be assigned precise map pins. Never add a participant’s private or live location.

## Google Maps setup

Create a Google Maps Platform API key and restrict it to the Maps JavaScript API and this website referrer: sarvleenwalia.github.io/*. Enter it in the map setup panel. The key is used for that browser session and is not saved by the app. Google Maps Platform may require billing. Never commit an unrestricted key or publish a secret key in this repository.

## Updating events

The curated event snapshot is in index.html. Before adding an event, use a current public source, preserve the organizer’s venue and timing, link directly to the source, and mark unknown details as TBA. Do not infer a meeting point or coordinates.

## Project status

Street Signal is a static website hosted with GitHub Pages. Community suggestions are local to each browser and are not shared between visitors.
