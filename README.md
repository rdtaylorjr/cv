# rdtaylorjr.com

Static one-page CV site. Everything served is in `public/`. No build step.

## Update

Export the CV from Pages to `public/cv.pdf`, edit `public/index.html` to match, then deploy.

## Deploy

```bash
cd ~/Developer/tehillim/cv && npx wrangler deploy
```

Custom domain is attached in the Cloudflare dashboard under Workers & Pages, rdtaylorjr, Settings, Domains & Routes.

## Type

IBM Plex Sans (300, 400, 700) and Frank Ruhl Libre for Hebrew, loaded from Google Fonts.
