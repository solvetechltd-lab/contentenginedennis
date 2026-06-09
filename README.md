# McQ Properties — 8-Week Content System

An interactive, single-file HTML content system and 8-week posting calendar built for MCQ Properties. Self-contained: no build step, no dependencies, no backend. Just open `index.html`.

## Live Demo

Enable GitHub Pages (see below) and the system is live at:
`https://<your-username>.github.io/mcq-content-system/`

## Features

- Single self-contained HTML file (fonts loaded via Google Fonts CDN)
- Interactive 8-week content calendar
- Copy-ready post snippets and email blocks
- Save-as-PDF button for client handoff
- Fully responsive, no framework or build tooling required

## Run Locally

Just open the file in a browser:

```bash
open index.html
```

Or serve it locally:

```bash
python3 -m http.server 8000
# visit http://localhost:8000
```

## Deploy with GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment → Source**, select **Deploy from a branch**.
4. Choose branch `main` and folder `/ (root)`, then **Save**.
5. Wait ~1 minute; your site goes live at the URL above.

## Project Structure

```
mcq-content-system/
├── index.html      # the entire content system
├── README.md
├── LICENSE
└── .gitignore
```

## License

MIT — see [LICENSE](LICENSE).

---

Built by [Solvetech Solutions LLC](mailto:solvetechltd@gmail.com).
