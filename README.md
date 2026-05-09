# jaaiworks-site

Source for [jaaiworks.org](https://jaaiworks.org) — a showcase of apps
built with [jaaicode](https://jaaicode.org).

## Local preview

```bash
pip install -r requirements.txt
mkdocs serve
```

## Deploy

Cloudflare Pages auto-deploys on push to `main`. Build settings:

- **Build command:** `pip install -r requirements.txt && mkdocs build`
- **Build output directory:** `site`
- **Environment variable:** `PYTHON_VERSION=3.12`
