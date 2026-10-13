# EvidenceFeed v4.1 — ChatGPT Import

This version removes PDF analysis from the website. The app does not require an AI backend or API key.

Workflow:
1. Send the complete scientific article PDF to ChatGPT.
2. Ask ChatGPT to generate the EvidenceFeed import file.
3. Download the `.evidencefeed.json` file.
4. Open EvidenceFeed → Import → choose the file.
5. The article is saved locally in the browser and becomes available in 30 sec, 3 min and 10 min modes, in EN/PT.

To update GitHub Pages, replace index.html, manifest.json and sw.js in the repository root.

`example.evidencefeed.json` documents the import format and can be used to test the importer.
