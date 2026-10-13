# Tao Feng’s academic website

A static academic homepage with a layout adapted from [Cheng Qian’s homepage](https://github.com/qiancheng0/qiancheng0.github.io/tree/home): a warm background, profile panel, news, research directions, and publication rows.

## Edit and preview

- `index.html`: profile, news, and all 45 publication entries. Each entry includes its categories, year, selected status, and search text.
- `stylesheet.css`: colors, layout, and responsive styles.
- `publications.js`: selected/date/topic views and search. Without JavaScript, every publication remains visible.
- `images/` and `data/`: existing photos, research figures, and documents.

Run `python3 -m http.server 8766` from this directory and open `http://localhost:8766/`.

The site uses relative asset paths, so it can be served from either a domain root or a GitHub Pages project path. Existing Google Analytics and site-verification settings are preserved.

The earlier site credited [Jon Barron’s academic website](https://jonbarron.info/).
