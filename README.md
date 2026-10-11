# Vanshika & Aayush — Wedding Invitation

A mobile-first, single-page wedding invitation built with HTML, CSS, inline SVG illustration and GSAP ScrollTrigger. Ready for GitHub Pages; no build step required.

## Details currently filled in
- Couple: Vanshika & Aayush
- Wedding date: Tuesday, 24 November 2026
- Venue: Bal Samand Lake Palace
- City: Jodhpur, Rajasthan
- Venue button opens a Google Maps search for the venue.
- The countdown is set to the start of the wedding date (midnight India time), because the ceremony time has not been supplied.
- The optional sound button plays a gentle browser-generated ambient pad after a guest taps it. It is not a recorded music track; it can be replaced with a licensed audio file if desired.

## Before sharing the final invitation
1. Confirm the exact schedule and dates/times for Mehendi, Haldi, Sangeet and Reception. Only the main wedding date is currently filled in.
2. Replace the sample WhatsApp number `910000000000` in the RSVP link with the family's number in international format: digits only, including country code, without `+`, spaces or dashes.
3. Confirm the exact venue address / map pin and ceremony time. If the ceremony is at a specific time, update `WEDDING_DATE` near the bottom of `index.html` to an ISO timestamp such as `2026-11-24T18:00:00+05:30`.
4. Preview the site on both desktop and mobile before sharing it with guests.

## Publish on GitHub Pages
1. Download and extract this ZIP.
2. Create a public repository, e.g. `vanshika-aayush-wedding`.
3. Open the extracted `vanshika-aayush-wedding` folder and upload `index.html` and `README.md` directly to the repository root (not the enclosing folder).
4. Commit the uploaded files to the `main` branch.
5. Go to **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, branch **main**, folder **/(root)**, then click **Save**.
6. Wait for deployment; GitHub displays the public website URL in the Pages settings.

GSAP is loaded from jsDelivr and Google Fonts from Google Fonts, so those features need an internet connection. The content remains readable if animation scripts fail or reduced-motion preferences are enabled.
