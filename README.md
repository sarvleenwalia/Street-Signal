# GatherMap

A privacy-first prototype for viewing publicly announced protests and rallies on Google Maps.

## Prototype status

- Enter a restricted Google Maps JavaScript API key at runtime to load the map. This prototype does not store the key.
- Add an event by clicking its public venue and entering its title, date/time, and organizer/source URL.
- Listings are marked unverified and saved in this browser only. There is no backend, shared feed, account system, GPS access, or participant tracking.
- This repository contains no real event listings. Verify event details with the organizer before relying on them.

## Google Maps setup

Enable the Maps JavaScript API for a Google Cloud project, create a key restricted to this API and to the site referrer, then enter it in the app. Google Maps Platform may require billing. Do not commit an unrestricted key.

Security guidance: https://developers.google.com/maps/api-security-best-practices

## Safety and privacy

Only add events publicly announced by organizers or reputable public sources. Pin public venues, never participants. A public launch needs a reviewed event feed, moderation, correction/expiry tools, abuse reporting, and a privacy policy.

Google Maps Platform terms and attribution: https://developers.google.com/maps/documentation/javascript/policies
