# PawLink

PawLink is a privacy-first lost-pet reunification aid for AnimalHack 2026. It compares structured, approximate report details against synthetic community-board entries and explains why each possible match was surfaced.

## What works

- Lost/found report flow with species, size, color, approximate neighborhood, and markings
- Transparent weighted matching rather than an opaque identity claim
- Safe next-step guidance for each lead
- Human verification and privacy safeguards built into the interface
- Single-file static app with no external API, account, or real-person data dependency

## Run locally

Open `index.html` in a modern browser, or serve this folder with any static web server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Scope and limitations

This is an event-specific MVP using synthetic reports. It is not a production animal registry, does not use facial recognition, does not expose exact addresses, and must not be treated as proof of ownership. A production version would add consent-based shelter partnerships, moderation, secure messaging, audit logs, and carefully tested welfare escalation protocols.

## Demo path

1. Keep the default Dog / Medium / Brown / Sreenidhi campus values.
2. Click **Find explainable matches**.
3. Review the signal chips and safe next action for each lead.
4. Change the markings or approximate area and run the comparison again.

Created by Battini Sadwik as a solo prototype.
