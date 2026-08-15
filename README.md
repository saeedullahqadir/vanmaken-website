# VANMAKEN

Architecture and urbanism studio — one-page landing site.

**Live site:** https://saeedullahqadir.github.io/vanmaken-website/
**Repo:** https://github.com/saeedullahqadir/vanmaken-website

## Files

- `index.html` — the entire site (HTML, CSS, and JS in one file; fonts and logo are embedded as base64 so no external requests are needed except for the video/image files below).
- `city_landscape.mp4` — hero background video.
- `city_landscape1.jpg`, `city_landscape2.jpg` — poster images / photo placeholders.
- `city_landscape3.mp4` — Climate + Landscape video break.
- `city_landscape4buiding.mp4` — Buildings work card video.
- `city_landscape4places.mp4` — Places work card video.
- `city_landscape4.mp4` — Cities work card video.
- `city_landscape4climate.mp4` — Climate work card video.
- `vanmaken-logo.png` — transparent-background logo used in the nav/footer badge.
- `vanmaken.jpg` — original logo file (white background).

## Editing

Open `index.html` in any code editor. All styles are in the `<style>` block at the top; all markup follows; a small script at the bottom handles scroll reveal and video autoplay.

To preview locally, just open `index.html` in a browser (double-click it, or drag it into Chrome).

## Still needs real content

A few spots are marked as placeholders and should be replaced with real details:

- Footer: studio address, phone number, city/country
- Stats section: Projects completed / Cities studied / Awards numbers are estimates — replace with real figures
- "Places" work card still needs its own video/photo (currently reuses a placeholder)
- Selected Work image-break: project name and location

## Deploying changes

```
git add -A
git commit -m "describe the change"
git push origin main
```

GitHub Pages rebuilds automatically after every push (usually takes 1–3 minutes).
