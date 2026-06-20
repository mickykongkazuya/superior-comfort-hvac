# Superior Comfort Heating &amp; Cooling

Marketing website for **Superior Comfort Heating & Cooling** — a licensed HVAC company
serving Philadelphia and the surrounding counties (furnace, boiler, central air, heat pump,
and water heater service).

## Stack

Plain static HTML/CSS/JS — no build step. Everything lives in:

```
index.html            # the whole site
images/logos/         # brand marks & wordmarks
images/photos/        # job / install photography
```

## Run locally

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Hosted on **Vercel** as a static site (see `vercel.json`). Pushing to `main` triggers a
production deploy when the Vercel Git integration is connected, or deploy manually:

```bash
vercel --prod
```

## Editing content

- **Phone / email / address** — search `index.html` for `(215) 416-6557`,
  `1superiorcomfortllc@gmail.com`, and `545 N 58th Street`.
- **Gallery photos** — drop new images into `images/photos/` and update the `<img src>`
  references in the "Our recent work" section.

---
© 2026 Superior Comfort Heating & Cooling · Licensed & insured
