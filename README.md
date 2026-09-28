# Webb's Enterprises — Website

Static site for webbsenterprises.com. There's no build step: plain HTML, CSS and JS.

```
index.html            Homepage
assets/css/styles.css Styles (brand colors are defined at the top in :root)
assets/js/main.js     Nav, scroll animations, particle hero, GA4 click tracking
assets/img/           Favicon and images
```

Preview locally with `python3 -m http.server`, then open http://localhost:8000.

## Hosting
Hosted on GitHub Pages from the `main` branch (repo root). `CNAME` sets the
custom domain to webbsenterprises.com. Pushing to `main` updates the live site.

## To do
- Add GA4: uncomment the snippet in `<head>` and set your Measurement ID.
- Add a testimonials section once real client quotes are ready (the previous layout is in git history).
- Build the About, Services, Results, Blog and Contact pages; the menu currently links to homepage sections.
