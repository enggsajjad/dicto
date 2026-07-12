# Generalized German Dictionary

A GitHub Pages-ready searchable dictionary for **A1, A2, B1, B2, C1, C2 and BSK_B2**.

## Included
- `index.html` — website, search, filters, dark mode, 20/30-word tests
- `words.json` — 4773 imported dictionary entries
- `words-template.json` — examples for adding new words, including BSK_B2

## Publish on GitHub Pages
1. Create a new public GitHub repository.
2. Upload `index.html`, `words.json`, and `words-template.json` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. GitHub will provide a URL like `https://USERNAME.github.io/REPOSITORY/`.

## Add a word
Open `words.json` and add a JSON object before the final `]`. Put a comma after the previous object.
Use exactly one of these levels: `A1`, `A2`, `B1`, `B2`, `C1`, `C2`, `BSK_B2`.

Recommended word types: `noun`, `verb`, `adjective`, `adverb`, `phrase`, `preposition`, `conjunction`.

## Important
The imported vocabulary and design originated from the supplied dictionary file. Review licensing/permission before publishing copied vocabulary publicly.
