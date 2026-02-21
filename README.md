# ATEC Screener

A free, open-source web app for the **Autism Treatment Evaluation Checklist (ATEC)** — a 77-item caregiver questionnaire developed by Dr. Bernard Rimland and Dr. Stephen M. Edelson at the [Autism Research Institute](https://autism.org).

## What It Does

- Walks caregivers through all 77 ATEC items across 4 subscales
- Provides instant scoring with severity interpretation
- Shows subscale breakdown (Speech, Sociability, Sensory/Cognitive, Health/Behavior)
- Works on any device — mobile, tablet, or desktop
- 100% client-side — no data is collected, stored, or transmitted

## ⚠️ Important Disclaimer

The ATEC is **not a diagnostic tool**. It is designed to measure treatment progress over time. Results should always be discussed with a qualified healthcare professional. This app does not diagnose autism spectrum disorder.

## Deploy

This is a single-file static web app. No build step required.

### Vercel (recommended)

1. Fork or clone this repo
2. Connect to [Vercel](https://vercel.com)
3. Set the **Output Directory** to `public`
4. Deploy — done

### Other platforms

Upload `public/index.html` to any static hosting provider (Netlify, GitHub Pages, etc.).

For **GitHub Pages**: rename `public/index.html` to `index.html` in the root, or configure Pages to serve from the `public` folder.

## Tech Stack

- React 18 (CDN)
- Vanilla CSS (no frameworks)
- Single HTML file, zero dependencies

## ATEC Scoring

| Subscale | Items | Score Range | Rating Scale |
|---|---|---|---|
| Speech/Language/Communication | 1–14 | 0–28 | Not True (2) / Somewhat (1) / Very True (0) |
| Sociability | 15–34 | 0–40 | Not Descriptive (0) / Somewhat (1) / Very Descriptive (2) |
| Sensory/Cognitive Awareness | 35–52 | 0–36 | Not Descriptive (2) / Somewhat (1) / Very Descriptive (0) |
| Health/Physical/Behavior | 53–77 | 0–75 | Not a Problem (0) / Minor (1) / Moderate (2) / Serious (3) |

**Total score range: 0–179.** Lower scores = fewer concerns.

## License

This project is licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/). The ATEC content is copyright © Autism Research Institute and may be used only for non-commercial purposes.
