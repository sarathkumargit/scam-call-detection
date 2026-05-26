# Scam Call Detection

This repository contains a static HTML app for analyzing GHL call report CSVs in the browser.

## Vercel deployment

1. Ensure this repo has `index.html` in the root.
2. In Vercel, create a new project and connect your Git repository.
3. For framework preset choose `Other` / `Static Site`.
4. Leave Build Command empty.
5. Leave Output Directory empty.
6. Deploy.

Once deployed, open the site and upload your exported GHL call report CSV.

## Notes

- The root page is now `index.html` for Vercel static hosting.
- `scam-call-analyzer.html` is still available if you want to keep the original filename.
