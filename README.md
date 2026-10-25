# EvidenceFeed v4.2.1

Hotfix for direct ChatGPT import.

- Adds `#import64=` direct import using plain URL-safe Base64.
- Does not depend on browser gzip/DecompressionStream for the new links.
- Keeps manual `.evidencefeed.json` import.
- Keeps 30 sec, 3 min, 10 min, Questions and Review.
- Review uses 15 cards per saved article.

Replace `index.html`, `manifest.json` and `sw.js` in GitHub Pages.
