# agyamishra.com

Personal portfolio site for **Dr. Agya Mishra** — Professor & HOD, Artificial Intelligence & Data Science, Jabalpur Engineering College. AI Architect, Consultant.

A single-page static site built to present two decades of applied AI research and national-scale AI policy work — Higher Order Neural Networks, nonlinear prediction, adaptive intelligence, and the systems built on top of them.

## Stack

- Plain HTML, CSS, and vanilla JavaScript — no build step, no framework, no dependencies
- Fonts loaded from Google Fonts (Fraunces, IBM Plex Mono, Instrument Sans)
- All imagery self-hosted in `/img`

## Structure

```
index.html      # the entire site
img/            # all photos, the ICACT 2007 certificate, and the hero portrait
```

## Running locally

No build tools required. Either open `index.html` directly in a browser, or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

Static hosting only — this project deploys as-is to Vercel, Netlify, GitHub Pages, or any static host. No environment variables, no server, no database.

**Vercel / Netlify:** point either platform at this repository with no build command and `.` (repo root) as the output directory, then attach the custom domain `agyamishra.com` and update DNS at the domain registrar per the host's instructions.

## Contact

agyamishra@gmail.com
