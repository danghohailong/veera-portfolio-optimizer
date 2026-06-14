# Veera Portfolio Optimizer — Pixel Mascot Netlify Build

This is a Netlify-ready HTML/CSS/JavaScript + Serverless Functions project.

## What changed in this build

- Added the Bonnie Rookie Pixel 8-second launch intro video.
- Added the Veera mascot logo across the app without regenerating the character artwork.
- Added background music from the provided MP4 extraction, with a visible Music On/Off toggle.
- Redesigned the landing page into a pixel / cyan / purple / pink poster-style theme.
- Added a floating mascot guide that follows the user through the flow.
- Kept the existing quant/data logic and Netlify serverless adapters intact.

## Local run

Do not double-click `index.html` if you need live data. Use Netlify Dev so serverless functions work.

```bash
npm install
npm install -g netlify-cli
netlify dev
```

Open the local Netlify URL, usually:

```text
http://localhost:8888
```

## Netlify deploy

- Build command: leave blank
- Publish directory: `.`
- Functions directory: `netlify/functions`

## Notes

Browser autoplay policies may block background music until the first user click. The Music button remains visible so users can enable or disable it manually.

The dashboard is educational and is not investment advice. Live-data failures are shown as errors instead of fabricated data.
