# Skin by Margot

Site for Skin by Margot, an esthetician and skincare business — built with Jekyll,
deployed via GitHub Pages with Cloudflare in front for DNS/CDN.

## Stack

- **Jekyll** — static site generator
- **Bourbon** — Sass mixin library
- jekyll-sitemap, jekyll-paginate, jemoji

## Local Development

```bash
bundle install
bundle exec jekyll serve
```

## Deployment

Pushes to `main` deploy automatically via GitHub Actions to GitHub Pages. DNS and CDN
handled through Cloudflare.
