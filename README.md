# mcp-services-site

Landing page for Sanjibani Choudhury's custom MCP server engagements.

## Files

- `index.html` — single-page static site. Drop into Netlify / Vercel / GitHub Pages.

## How to deploy

### GitHub Pages (free)

```bash
# In the repo root
cd /Users/sabyasachichoudhary/.minimax-agent/projects/mcp-services-site
gh repo create mcp-services --public --source=. --remote=origin --push
# Then on github.com: Settings → Pages → Deploy from branch → main → / (root)
```

### Netlify drag-and-drop (fastest)

1. Visit https://app.netlify.com/drop
2. Drag the folder containing `index.html` onto the page
3. Get a `*.netlify.app` URL in 30 seconds
4. Add custom domain later if you want

### Local preview

```bash
python3 -m http.server 8000
# Open http://localhost:8000
```

## What it does

- Lists the OSS MCP portfolio (6 products)
- Explains the engagement model (3 phases)
- Shows 3 pricing tiers ($25K / $60K / $120K+)
- Lists verticals I know cold
- CTA: `mailto:` link with pre-filled email body
- Self-hosted, no tracking, no third-party scripts

## License

The HTML / CSS is MIT. Copy it, fork it, host it anywhere.