# EvidenceFeed v4

## New ingestion flow
EvidenceFeed v4 removes DOI/title/link search and screenshot identification. The only ingestion method is a complete scientific article PDF.

Desired production flow:
1. Upload full PDF.
2. Secure backend sends/reads the full article with an AI model.
3. AI interprets methods, statistics, results, tables/figures, limitations and implications.
4. Generate all three modes automatically:
   - 30 sec: visual Instagram-like cards
   - 3 min: expanded visual cards
   - 10 min: deep structured analysis
5. EN/PT toggle remains available.

## Important
This ZIP contains the GitHub Pages front-end and the complete PDF upload workflow UI. GitHub Pages is static hosting, so it cannot securely contain a private AI API key. The Analyze button therefore cannot perform real AI analysis until a secure backend endpoint is connected.

## GitHub update
Replace `index.html`, `manifest.json`, and `sw.js` in the repository root and commit. After GitHub Pages deploys, hard-refresh the site.
