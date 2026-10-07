# datumai.xyz

The **test site** for Datum, live at [datumai.xyz](https://datumai.xyz). It's kept on a separate domain from the real `.ai` site so work in progress never touches it.

It's a single static page: no build step, no framework, no JavaScript. The page has a hero, About, Focus, Reports ("coming soon") and Contact sections.

## Files

| Path | What it is |
|---|---|
| `index.html` | The whole site, with its CSS in a `<style>` block in the page |
| `CNAME` | Tells GitHub Pages to serve the site at `datumai.xyz` |
| `_config.yml` | GitHub Pages settings; stops this README being published on the site |
| `images/hero.jpg` | Hero background (refinery at dusk) |
| `images/about.jpg` | About section photo (bulk cargo loading) |
| `images/hero-bg.jpg` | Focus section background (launch on dark water) |
| `images/reports-bg.jpg` | Reports section photo (bow wave) |
| `images/bg-water.jpg` | Contact section background |

## Editing and previewing

Edit `index.html` directly. To preview, open the file in a browser, or serve the folder locally:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deployment

GitHub Pages publishes the site from the `main` branch. Merging a change into `main` updates datumai.xyz, usually within a minute or two.

Keep the `CNAME` file in place. Deleting it removes the custom domain from GitHub Pages.

## Search engines

Because this is a test site, `index.html` carries `<meta name="robots" content="noindex, nofollow">` so search engines leave it out of their results. Remove that tag only if this page is moved to the real domain.
