# EvidenceFeed v2

Static PWA for GitHub Pages. Upload `index.html`, `manifest.json`, and `sw.js` to the repository root.

- PubMed ESearch + ESummary + EFetch (browser requests, requires remote CORS availability).
- PMID / DOI / keywords search.
- 30 sec / 3 min / 10 min reading modes, using actual abstract text (not yet AI-generated summaries).
- EN ⇄ PT translation uses MyMemory public endpoint; subject to public service limits, availability and transmission of the text to a third party. This is not an offline translation engine. Translation may fail.
- Saves selected articles in localStorage.
- Photo/PDF recognition and AI-generated critical reviews are not yet implemented.

Privacy: the public GitHub Pages site is accessible to anyone with its address. Avoid uploading confidential files. No private keys are used.
