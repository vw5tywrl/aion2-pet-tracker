# Aion 2 — Pet Tracker

<p align="center">
  <img src="assets/aion2-logo.png" width="120" alt="Aion 2 Pet Tracker Logo" />
</p>

<p align="center">
  <b>A modern, responsive pet tracker and database for Aion 2.</b><br>
  Track your collection, inspect pet attributes, genus types, bonuses, and stats with instantaneous search and filtering.
</p>

---

## Features

- **Interactive Pet Grid**: Complete catalog of Aion 2 pets with high-resolution portraits.
- **Fast Search & Filtering**: Real-time filtering by name, genus, tier, and combat stats.
- **Collection Tracking**: Track which pets you have collected with persistent local state.
- **Modern Dark UI**: Clean, sleek aesthetic built with modern CSS and backdrop blurs.
- **Zero Build Step**: Pure HTML/CSS/JavaScript. Fast to load and easy to deploy anywhere.
- **Cloudflare Ready**: Pre-configured for Cloudflare Workers / Pages via `wrangler.jsonc`.

---

## Live Preview & Deployment

### Running Locally

You can serve the project using any local HTTP server:

```bash
# Using Python 3
python -m http.server 8080

# Or using Cloudflare Wrangler
npx wrangler dev
```

Then open `http://localhost:8080` in your browser.

### Deploying to Cloudflare Pages

```bash
npx wrangler pages deploy .
```

Or connect this repository directly to **GitHub Pages** or **Cloudflare Pages** for automated continuous deployment.

---

## License

MIT © [andrea marano](LICENSE)
