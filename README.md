# League Central — Final Project Presentation Website

Static presentation website for **League Central** (Team A01-G08, COMP 3350, Summer 2026).

## Viewing the Website

### Hosted

The website is deployed with GitHub Pages. Once deployed, it is available at the repository's GitHub Pages URL.

### Locally

No build step is required — this is a plain HTML/CSS/JS static site.

1. Clone or download this repository.
2. Open `index.html` directly in any modern browser, **or** serve the folder locally:

   ```bash
   python -m http.server 8000
   ```

   Then visit `http://localhost:8000`.

## Structure

```
index.html      Main (and only) page: overview, features, demo, team, architecture, reflection
css/style.css   All styling
js/main.js      Navigation highlighting, mobile menu, scroll-reveal animations
assets/         Architecture diagrams and the demo video
```

## Demo Video

The product demonstration video is expected at `assets/demo.mp4`. Place the screen recording there and the player on the Demo section will pick it up automatically.
