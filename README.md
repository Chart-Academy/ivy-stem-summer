# Ivy League STEM Summer — The Chart Academy

A one-file website (`index.html`) for The Chart Academy's six-week summer STEM program and Ivy League college tour. The logo is built into the file, so nothing else needs to be uploaded.

## Publish on GitHub Pages

1. Sign in to GitHub and create a new public repository (for example, `ivy-stem-summer`).
2. Click **Add file → Upload files**, upload `index.html`, and click **Commit changes**.
3. Open **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the **main** branch and the **/ (root)** folder, and click **Save**.
4. After a minute or two, the site is live at `https://<your-github-username>.github.io/ivy-stem-summer/`.

## Add the application link

When the online interest form or application is ready (Google Form, Microsoft Form or another service), open `index.html`, find this line near the bottom:

```js
var INTEREST_FORM_URL = "";
```

Paste the form's link between the quotes and commit the change. Every "Check eligibility" and "Applications open soon" button will then open the form.

## Pages

- `#home` — program overview, the four-component graphic and the tour route
- `#eligibility` — student requirements, a quick eligibility check and the schools being recruited
- `#parents` — what parents receive on the tour and what they cover
- `#path` — the senior-fall application checklist (progress saves in each student's browser)
