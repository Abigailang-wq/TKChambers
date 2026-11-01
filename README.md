# Tan & Khong Chambers website

The site lives at **tkchambers.com**.

## Where things are

| What | Where |
|---|---|
| All page text, layout and styles | `index.html` |
| Photos and logos | `assets/images/` |
| Fonts | `assets/fonts/` |
| Page engine (don't edit) | `assets/js/` |

## Common edits

- **Change text:** search `index.html` for the words you want to change and edit them.
- **Swap a photo:** replace the file in `assets/images/` with a new one of the same name, or change the `src="assets/images/..."` in `index.html`.
- **Phone, email, address:** these appear in several places, so search `index.html` for each one and update every match.
- **Translations:** the BM and 中文 versions are near the bottom of `index.html`, so update them when you change English text.

## Preview on your computer

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000. Opening `index.html` by double-clicking may not work, so use the command above.
