# Ivy League STEM Summer — The Chart Academy

A website for The Chart Academy's six-week summer STEM program and Ivy League college tour. The page is `index.html` (the logo is built into it); the campus photos are in `images/`.

Live site: https://chart-academy.github.io/ivy-stem-summer/

## Publish on GitHub Pages

1. Sign in to GitHub and create a new public repository (for example, `ivy-stem-summer`).
2. Click **Add file → Upload files**, upload `index.html` and the `images` folder, and click **Commit changes**.
3. Open **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the **main** branch and the **/ (root)** folder, and click **Save**.
4. After a minute or two, the site is live at `https://<your-github-username>.github.io/ivy-stem-summer/`.

## Add the application link

When the online interest form or application is ready (Google Form, Microsoft Form or another service), open `index.html`, find this line near the bottom:

```js
var INTEREST_FORM_URL = "";
```

Paste the form's link between the quotes and commit the change. Every "Check eligibility" and "Applications open soon" button will then open the form.

## Pages

- `#home` — program overview, students walking the four-stop road, expandable week-by-week boxes and a tour preview
- `#eligibility` — student requirements (including SYEP eligibility through summerjobs.dc.gov), a quick eligibility check and the schools being recruited
- `#parents` — what parents receive on the tour and what they cover
- `#tour` — the five universities with photos, website and admissions links, and the bus route map
- `#path` — the senior-fall application checklist (progress saves in each student's browser)

## Photo credits

Campus photos are from Wikimedia Commons and are credited at the bottom of the College Tour page. The school badges are simple shields in each school's colors, not official logos.
