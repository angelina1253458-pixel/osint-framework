# OSINT Framework — GitHub Pages mirror

This repository publishes a static copy of the public website from the upstream [OSINT Framework](https://github.com/lockfale/OSINT-Framework).

## Website

https://angelina1253458-pixel.github.io/osint-framework/

## Deployment and updates

GitHub Actions downloads the upstream `public/` directory and publishes it with GitHub Pages. It deploys on pushes to `main`, can be started manually from the Actions tab, and refreshes from upstream daily at 04:17 UTC.

## Notes

This is a static GitHub Pages deployment. The interactive directory, search, and navigation are provided by the upstream frontend. Server-side API features from the upstream Cloudflare Worker (for example, ratings, reports, and click tracking) are not hosted by this repository and may not work here.

## Attribution and license

The website source and data are maintained by [lockfale/OSINT-Framework](https://github.com/lockfale/OSINT-Framework). The upstream repository includes an MIT License; retain its copyright and license notices when redistributing source.
