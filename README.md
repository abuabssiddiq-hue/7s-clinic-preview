# 7S Clinic — website preview

Temporary preview of two website design options for 7S Clinic, prepared by Madhras.com × ETECH.

| Page | Option B (recommended) | Option A |
|---|---|---|
| Home | `/` | `/option-a` |
| Booking | `/booking` | `/option-a/booking` |

A small A/B switch at the bottom-left of each page moves between the two options.

Text in [brackets] (doctor names, fees, area) is placeholder content until 7S Clinic confirms it.

## Deploy on Vercel

1. Push this repository to GitHub.
2. In Vercel: **Add New → Project → Import** this repository.
3. Framework preset: **Other**. Leave build command and output directory empty.
4. Click **Deploy**.

Every push to `main` redeploys automatically.

## Notes

- Static HTML only, no build step.
- The preview is hidden from search engines (`robots.txt`, `noindex` meta tag and `X-Robots-Tag` header in `vercel.json`). Remove these when the real site goes live.
