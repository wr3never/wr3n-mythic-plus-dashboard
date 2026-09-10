# Wr3n Mythic+ Dashboard

A phone-friendly Frost Death Knight Mythic+ dashboard and rotation trainer for Wrénêvër-Illidan.

## What is included

- Live Raider.IO character sync through `/api/raider`
- Best-next-key recommendation card
- Current rating, item level, ranks, dungeon best runs, and recent runs
- Great Vault and goal tracking
- Frost DK top-DPS priority trainer with ST / cleave / AoE modes
- Local browser saving for trainer score and custom dashboard data

## Deploy on Vercel

### Easiest route
1. Create a new GitHub repository.
2. Upload all files from this folder to the repository root.
3. In Vercel, choose **New Project** and import that repository.
4. Deploy with the default settings.
5. Open the production URL and tap **Refresh Raider.IO**.

No Raider.IO API key is required for ordinary public profile requests. Raider.IO rate-limits unauthenticated calls, so the included serverless route caches responses briefly and passes through `Retry-After` on rate limits.

## Local development

Install the current Vercel CLI, then from this folder run:

    vercel dev

Open the local URL shown by the CLI.

## Character

Default profile:
- Region: US
- Realm: Illidan
- Character: Wrénêvër

You can change the character from the app's **Character** button.

## Raider.IO attribution

The app links back to Raider.IO, as required for public-facing applications using the Raider.IO API.
