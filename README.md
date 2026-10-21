# rdtaylorjr.com

Static one-page CV site. Everything served is in `public/`. No build step.

## Update

Save the new version as `docs/CV Rusty Taylor YYMMDD.pages` and export it to a PDF of the same name, copy the PDF to `public/cv.pdf`, edit `public/index.html` and `public/sitemap.xml` to match, then deploy.

Only the current version in `docs/` is tracked. Change the `!docs/CV Rusty Taylor YYMMDD.*` line in `.gitignore` to the new date so older versions stay local.

## Deploy

```bash
cd ~/Developer/research/cv && npx wrangler deploy
```

Custom domain is attached in the Cloudflare dashboard under Workers & Pages, rdtaylorjr, Settings, Domains & Routes.

## Type

IBM Plex Sans (300, 400, 700) and Frank Ruhl Libre for Hebrew, loaded from Google Fonts.
