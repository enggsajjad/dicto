# Generalized German Dictionary — Separate JSON version

Upload these four files to the **same folder** in your GitHub repository:

- `index.html`
- `dictionary.html`
- `words.json` — A1 to C2 vocabulary
- `BSK_B2_words.json` — BSK_B2 vocabulary

The HTML loads both JSON files and combines them in the browser. Do not rename the JSON files unless you also change the names inside `index.html` and `dictionary.html`.

## GitHub Pages

After pushing, open the GitHub Pages URL. Do not open the HTML by double-clicking it locally, because browsers may block `fetch()` for local files.

If your old site still appears, use `Ctrl + F5`, clear site data, or open the page in a private window. The loader uses a version query string to reduce stale JSON caching.

Expected counts:

- A1–C2: 4,773
- BSK_B2: 1,467
- Total: 6,240


## Classification search
Use the second search field to filter by lesson or vocabulary type, for example `Lektion 1`, `Nomen`, `Nomen-Verb-Verbindung`, or `Verb mit Präposition`. The suggestions are generated automatically from the `classification` field in both JSON files.
