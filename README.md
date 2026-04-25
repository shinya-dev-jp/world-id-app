# Shinya Dev — Mini Apps Landing Page

Landing page introducing the Mini Apps published by Shinya Dev for the
World App ecosystem. Deployed at **https://world-id-app.vercel.app/**.

Apps featured:
- **TuringVote** — 2-choice poll app for World ID Verified Humans only. Social category. (Live)

Past entries (DailyPredict, MealPact and others) have been retired and are no
longer linked from the landing page. The hub is the canonical Official Website
referenced from the Worldcoin Developer Portal for currently active apps.

## Structure

- `index.html` — Main landing page
- `privacy.html` — Privacy Policy (covers all currently active Mini Apps)
- `terms.html` — Terms of Service (covers all currently active Mini Apps)

Pure static HTML with Tailwind CDN. No build step required; Vercel serves
directly.

## Deploy

Connect this repository to the `world-id-app` Vercel project and it will
auto-deploy to `world-id-app.vercel.app` on every `main` push. Manual deploys
can be triggered with `npx vercel deploy --prod` from this directory.

## Used by

- Worldcoin Developer Portal — App **Official Website** field for TuringVote
  points here. Future Mini Apps will be added to this same hub.
