# pllst.xyz

A Jekyll-based site for hosting redirect pages to playlists.

## Purpose

Provides short, memorable URLs (like pllst.xyz/skcnqrr) that redirect to playlist pages for easy promotion.

## Hosting

Hosted on GitHub Pages.

## Contributing

Open for contributions. Pull requests will be served on a best-effort basis.

## Adding a redirect

Create a new `.md` file in the site root with:

```yaml
---
layout: forward
to: YOUR_PLAYLIST_URL
---
```
