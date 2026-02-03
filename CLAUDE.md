# Piston Docs

Internal documentation hub for Piston Labs.

## Deployment

**No GitHub Actions configured.** Deploy manually using Wrangler:

```bash
npx wrangler pages deploy . --project-name=piston-docs
```

This deploys all static files to Cloudflare Pages at https://piston-docs.pages.dev

## Structure

```
/                   - Doc hub index
/docs/*.html        - Individual documentation pages
/assets/style.css   - Shared styles
/review.html        - Review interface
```

## Adding New Docs

1. Create HTML file in `/docs/`
2. Add link card to `index.html`
3. Deploy with wrangler command above
