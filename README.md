# KnowOcean (`knowocean.org`)

A Jekyll website sharing applied marine science resources and real-life stories of marine biologists.

## Local Development

Install dependencies and run the local Jekyll server:

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000` in your browser.

## Project Structure

- `_config.yml` — Site configuration, navigation, SEO metadata, and favicons
- `index.md` — Home page
- `_pages/` — Standalone pages (`about.md`, `blog.md`)
- `_posts/` — Blog posts (`YYYY-MM-DD-title.md`)
- `_layouts/` & `_includes/` — HTML templates and reusable partials
- `_sass/` — SCSS stylesheets (`_theme.scss` for custom overrides)
- `assets/` — Images, logos, and `search.json` index
- `elements.md` — Unlinked local formatting & shortcode reference (`indexing: false`)
- `CONTENT_TODO.md` — Content creation checklist

## Credits

Built with Jekyll using the [Alembic](https://github.com/daviddarnes/alembic) theme as a starting point.
