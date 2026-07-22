# 2026 Harvey County Community Health Needs Assessment — Web Page

A single-page website for United Way of Harvey and Marion Counties that hosts and explains the **2026 Harvey County Community Health Needs Assessment (CHNA) and Community Health Improvement Plan (2026–2029)**.

The page gives a plain-language overview of what the assessment is and how it was determined, lays out the four health priorities, and details exactly which action items United Way and the coalitions it facilitates — the Healthy Harvey Coalition, the Childcare Task Force, and the Housing Alliance — are moving forward, along with the Walk & Roll Harvey partnership.

## What's in here

```
index.html                     The complete page (self-contained — no build step)
assets/
  uwhmc-logo-color.png         Official localized logo, full color (for reference)
  uwhmc-logo-white.png         Official localized logo, white knockout (for reference)
  favicon.png                  Site icon
```

The logos and favicon are already embedded directly inside `index.html`, so the page works on its own. The files in `assets/` are included as editable source copies.

## Viewing it locally

Just open `index.html` in any web browser — double-click it, or drag it into a browser tab. There's nothing to install or build.

## Publishing with GitHub Pages

Because the page is a single self-contained file named `index.html`, GitHub Pages can host it directly:

1. Push this repository to GitHub.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, pick the `main` branch and the `/ (root)` folder, and save.
4. After a minute or two, your page will be live at `https://<your-org>.github.io/<repo-name>/`.

You can also drop `index.html` straight into your existing CMS or website if you'd rather host it alongside the rest of uwhmc.org.

## The report PDF

The **Download the full report** buttons link to the hosted PDF at:

`https://uwhmc.org/uploads/editor/files/2026 CHNA REPORT FINAL 7-21-2026.pdf`

If that file ever moves, update the two links in `index.html` (search for `uwhmc.org/uploads`).

## Editing

Everything — text, colors, fonts, and layout — lives in `index.html`. The design follows the United Way brand guidelines: the palette (blue `#0044B5`, red `#FD372C`, gold `#FFBA00`, plus green and purple for the coalitions) is defined as CSS variables in the `:root` block near the top, and the fonts are Antonio (headlines) and Palanquin (body), loaded from Google Fonts.

## Ownership

The content, the United Way logo, and the localized "Harvey and Marion Counties" lockup are the property of United Way of Harvey and Marion Counties. The United Way Circle of Hope logo is a registered trademark used here with the organization's authorization.
