# Midterms 2026 · Congressional Control

A dark, modern single-page dashboard showing who controls the U.S. Senate and House, which seats are up in the Nov 3, 2026 midterms, and key Senate battlegrounds.

No build step, no dependencies. Just open `index.html`.

## Data
Snapshot compiled from public reporting in early Oct 2026. Counts change with vacancies and special elections. Verify with [clerk.house.gov](https://clerk.house.gov) and [senate.gov](https://www.senate.gov). Edit the numbers in the `hemi(...)` calls at the bottom of `index.html`.

## Deploy
Push to `main`, then in the repo go to Settings → Pages → Source: GitHub Actions. The included workflow publishes the site.
