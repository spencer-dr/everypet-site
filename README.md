# everypet-site

Public pages for the EveryPet iPhone app, served by GitHub Pages:

- `/confirmed/` — where email confirmation links land (Supabase Site URL). Strips the token from the address bar; no trackers.
- `/privacy/` — the privacy policy. PostHog / RevenueCat sections are hidden placeholders until those ship.
- `/` — a small home page.

Static HTML + CSS only, no third-party requests. Fonts (Baloo 2, Nunito) are self-hosted under the SIL Open Font License — see `fonts/`.
