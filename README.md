# 🇩🇪 Sajjad German Learning

A free, searchable German-learning website for **A1–C2** and **BSK B2**. It combines a bilingual dictionary, sentence examples, grammar notes, collocations, lesson-based Redemittel, and useful expressions for workplace meetings.

> Deutsch lernen mit Wortschatz im Kontext — German vocabulary with English meanings and practical examples.

## 🌐 Live website

After enabling GitHub Pages, the site will normally be available at:

```text
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/
```

Main pages:

- `index.html` — dictionary landing page
- `dictionary.html` — searchable dictionary
- `redemittel.html` — Redemittel and meeting expressions

## ✨ Features

- Searchable vocabulary for **A1, A2, B1, B2, C1, C2 and BSK_B2**
- German words with English meanings
- German example sentences with English translations
- Grammar, articles, collocations and classifications
- Filters by CEFR level and part of speech
- Classification search, including lessons, **Verb mit Präposition** and **Nomen-Verb-Verbindung**
- 20-word and 30-word vocabulary tests
- Lesson-wise **Wichtige Redemittel**
- Lesson-wise **Verbindungen für Besprechungen**
- Light and dark mode
- Responsive design for desktop and mobile
- Custom Sajjad Hussain favicon and app icon

## 📚 Content overview

| Area | Content |
|---|---|
| Dictionary | A1–C2 vocabulary and BSK B2 workplace vocabulary |
| Examples | German example sentences and English translations |
| Grammar | Articles, plural information, cases and prepositions |
| Classifications | Lessons, nouns, verbs, Verb mit Präposition, Nomen-Verb-Verbindung |
| Redemittel | Speaking, discussions, telephone calls, emails, appointments and presentations |
| Besprechungen | Useful workplace combinations organised by lesson |
| Practice | Search, filters and random vocabulary tests |

## 🗂️ Repository structure

```text
.
├── index.html
├── dictionary.html
├── redemittel.html
├── words.json
├── BSK_B2_words.json
├── redemittel.json
├── verbindungen_besprechungen.json
├── sajjad-hussain-icon.png
├── favicon.ico
├── favicon-16x16.png
├── favicon-32x32.png
├── apple-touch-icon.png
├── icon-192.png
├── icon-512.png
├── manifest.webmanifest
└── README.md
```

## 🚀 Publish with GitHub Pages

1. Create or open your GitHub repository.
2. Upload all files from this package to the same folder, normally the repository root.
3. Commit and push the files.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and `/ (root)` folder.
7. Save and wait for GitHub Pages to finish deployment.
8. Refresh the live page with `Ctrl + F5` after an update.

## ➕ Add a dictionary entry

Edit either `words.json` or `BSK_B2_words.json`. Add a new object before the final closing bracket:

```json
{
  "german": "Rücksprache halten",
  "article": "",
  "english": "to consult / check with someone",
  "level": "BSK_B2",
  "pos": "phrase",
  "irregular": false,
  "reflexive": false,
  "grammar": "mit + Dativ",
  "example_de": "Ich muss zuerst mit meiner Vorgesetzten Rücksprache halten.",
  "example_en": "I first need to consult my supervisor.",
  "collocations": ["mit der Leitung Rücksprache halten"],
  "classification": "Nomen-Verb-Verbindung"
}
```

Keep valid JSON syntax: objects are separated by commas, strings use double quotation marks, and the full file remains inside one array `[...]`.

## ➕ Add Redemittel or meeting expressions

- Edit `redemittel.json` for lesson-based Redemittel and examples.
- Edit `verbindungen_besprechungen.json` for German–English workplace combinations.
- Keep the existing structure so lesson filters continue to work.

## 🎨 Website icon

The website uses `sajjad-hussain-icon.png` in the page header and the favicon/app-icon files in browser tabs and mobile shortcuts. Replace the image files with identically named files to update the branding without editing the HTML.

## ⚖️ Usage

This project is intended for personal learning and educational use. Confirm that you have permission to republish any vocabulary or learning material obtained from third-party sources.

---

**Viel Erfolg beim Deutschlernen!**  
**Good luck learning German!**
