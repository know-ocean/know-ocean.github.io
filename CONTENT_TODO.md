# KnowOcean Content Creation To-Do List

This checklist tracks remaining content, metadata, and asset tasks for **KnowOcean** (`knowocean.org`).

## 1. Site Metadata & Social Profiles (`_config.yml`)
- [ ] Add your real `email` address in `_config.yml`.
- [ ] Add your `twitter.username` and `social.links` (LinkedIn, GitHub, Twitter, etc.) in `_config.yml`.
- [ ] Uncomment and populate `social_links` in `_config.yml` for the sidebar.
- [ ] Review `sharing_links` in `_config.yml` (Twitter, Facebook, Email).
- [ ] (Optional) Configure `google_analytics` or `disqus` in `_config.yml` if you want analytics or post comments.
- [ ] Verify `repo` URL in `_config.yml` (`https://github.com/know-ocean/know-ocean.github.io`).

## 2. Home Page (`index.md`)
- [ ] Write body content below the front matter in `index.md`:
  - KnowOcean mission statement and what visitors will learn.
  - Overview of applied marine science topics (fisheries, oceanography, lab/field work, STEM foundations).
  - Call-to-action links to `/blog/` and `/about/`.
  - (Optional) Featured posts or recent highlights.

## 3. About Page (`_pages/about.md`)
- [ ] Replace `[Your LinkedIn URL]` and `[Your GitHub URL]` with your actual profile links.
- [ ] Review and expand the career timeline (1997–2023+) and add photos from `assets/images/` (e.g., `jc_coral.jpg`, `jc_sail1.jpg`, `jc_yardarm.jpg`) using `{% include figure.html %}` where helpful.
- [ ] Verify the Buy Me a Coffee link (`https://buymeacoffee.com/knowocean`).

## 4. Blog Posts (`_posts/`) & Categories (`categories.md`)
- [ ] Plan and draft additional posts in `_posts/YYYY-MM-DD-title.md` to build out the blog beyond `2024-11-11-origin-story.md`:
  - *Day-in-the-life* stories (field sampling, research cruises, age & growth lab work).
  - *Applied STEM* posts showing how math, chemistry, physics, biology, and coding are used in marine science.
  - *Career paths* in marine biology (academic, government/NOAA, conservation, industry).
- [ ] Assign consistent `categories:` in post front matter (e.g., `career`, `fieldwork`, `fisheries`, `stem`) so `/categories/` becomes a useful index.
- [ ] Add `feature_image` and `excerpt` front matter to each post for clean blog list cards and social sharing previews.

## 5. Visual Assets (`assets/images/`)
- [ ] Audit unused/duplicate image files in `assets/images/` (`banner1.jpg`, `banner1.png`, `sponge_jc.jpg`, `sponge_jc.png`, `logo1.jpg`, `logo_muted.webp`, etc.) and remove any unneeded drafts once final pages are built.
- [ ] Confirm `default` social sharing image in `_config.yml` (`/assets/logos/logo_1024.png` or a dedicated `1200x630` social card).
