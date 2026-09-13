# Adnan Abbas Shah — academic website

Built on [al-folio](https://github.com/alshedivat/al-folio) (Jekyll). Content is already filled in:
publications, CV, projects, blog posts, news and profile photo.

## Deploy on GitHub Pages (recommended)

1. Create a repo named `adnanabbasshah.github.io` on GitHub.
2. Push these files to the `main` branch.
3. Repo → Settings → Pages → Build and deployment → Source: **GitHub Actions**.
4. Repo → Settings → Actions → General → Workflow permissions → **Read and write permissions**.
5. Push once more. `.github/workflows/deploy.yml` builds and publishes automatically.

Site URL will be `https://adnanabbasshah.github.io`.

If you instead use a repo named something else (e.g. `portfolio`), set in `_config.yml`:

```yaml
url: https://adnanabbasshah.github.io
baseurl: /portfolio
```

## Deploy on Netlify

Build command: `bundle exec jekyll build`
Publish directory: `_site`
Add env var `JEKYLL_ENV=production`.

## Run locally

```bash
bundle install
bundle exec jekyll serve
```

Or with Docker: `docker compose up`.

## Where the content lives

| What | File |
|---|---|
| Bio, profile photo, subtitle | `_pages/about.md` |
| Publications | `_bibliography/papers.bib` |
| CV (rendered page) | `_data/cv.yml` |
| CV PDF | `assets/pdf/adnan_abbas_shah_cv.pdf` |
| Projects | `_projects/*.md` |
| Blog posts | `_posts/*.md` |
| News ticker | `_news/*.md` |
| Social links, ORCID, Scholar | `_data/socials.yml` |
| Site title, URL, theme | `_config.yml` |

## Things to check before going live

- `_config.yml` → `url` and `baseurl` match your repo.
- Google Scholar ID in `_data/socials.yml` is `D7YV-1wAAAAJ`. Confirm it is correct.
- Publication preview images live in `assets/img/publication_preview/`.
- Two papers are marked under review (`@unpublished`). Move them to `@article` once accepted.
