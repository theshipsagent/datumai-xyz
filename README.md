# datumai.xyz

The "coming soon" placeholder site for **Datum**, live at [datumai.xyz](https://datumai.xyz).

It's a single static page: no build step, no framework, no JavaScript.

## Files

| Path | What it is |
|---|---|
| `index.html` | The whole site, with its CSS in a `<style>` block in the page |
| `CNAME` | Tells GitHub Pages to serve the site at `datumai.xyz` |
| `images/bg-water.jpg` | The full-screen background photo |
| `images/hero.jpg`, `hero-bg.jpg`, `about.jpg`, `reports-bg.jpg` | Not used yet; kept for a future, fuller landing page |

## Editing and previewing

Edit `index.html` directly. To preview, open the file in a browser, or serve the folder locally:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deployment

GitHub Pages publishes the site from the `main` branch. Merging a change into `main` updates datumai.xyz, usually within a minute or two.

Keep the `CNAME` file in place. Deleting it removes the custom domain from GitHub Pages.
