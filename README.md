# Vocabulary PWA v11

Updates:
- Adds an explicit expand/collapse icon in each saved card action row.
- Improves the GPT prompt to ask for past-form guidance and past-tense pronunciation tips when the term can function as a verb or action expression.
- Supports a custom GPT button icon with `gpt-icon.png`.

## Files to upload to GitHub Pages
Upload/replace these files in the repository root:

- `index.html`
- `manifest.json`
- `sw.js`
- `icon-192.png`
- `icon-512.png`
- `gpt-icon.png`

## Custom icon specs

### App icon
Use these exact filenames:
- `icon-192.png` — 192 × 192 px, PNG
- `icon-512.png` — 512 × 512 px, PNG

Recommended design:
- square image
- solid background
- logo centered with about 20% safe padding
- no tiny text

### GPT button icon
Use this exact filename:
- `gpt-icon.png` — recommended 256 × 256 px, PNG, transparent background

Recommended design:
- white mark on transparent background, because the GPT button is dark
- square image
- centered icon
- no text, unless very short

After replacing icons, commit the files and open the site with `?v=10` to avoid cache.
