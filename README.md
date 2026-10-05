# Street Signal

**Public gatherings, on your map.**

Street Signal is a public events map for finding organizer-announced protests, rallies, marches, and vigils. It is designed to make public event details easier to browse while respecting participants’ privacy.

**Live site:** https://sarvleenwalia.github.io/gathermap/

## What it does

- Shows a map and event list with public venues, dates, times, and links to source pages.
- Lets visitors search events and filter by country.
- Includes a one-time Google Maps JavaScript API key field. The app does not save the key.
- Keeps community event additions in the visitor’s browser; they are not submitted to a shared database.
- Does not request GPS access, create accounts, or track participants.

## Event information

Listings are a snapshot, not a complete or real-time feed. Event details can change, and a source link does not guarantee that an event is still happening. Check the linked organizer or source before traveling.

Community-submitted listings are unverified. Events without a confirmed public meeting point should not be assigned a precise map pin. Never add a participant’s private or live location.

## Google Maps setup

To display the map, create a Google Maps Platform API key and restrict it to the **Maps JavaScript API** and the Street Signal site referrer. Enter it in the map’s setup panel. The key is used for that browser session and is not saved by the app. Google Maps Platform may require billing. Never commit an unrestricted key or publish a secret key in this repository.

## Updating the event snapshot

The curated event snapshot is in `index.html`. Before adding an event, use a current public source, preserve the organizer’s venue and timing, and link directly to the source. Mark unknown details as TBA; do not infer a meeting point or coordinates.

## Project status

Street Signal is a small static-site project hosted with GitHub Pages. Community additions are local to each browser and are not shared between visitors.
