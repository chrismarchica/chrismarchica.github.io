# chrismarchica.github.io

Personal portfolio site, served via GitHub Pages at
[chrismarchica.github.io](https://chrismarchica.github.io).

## Structure

| File | Purpose |
|------|---------|
| `index.html` | Page markup and content sections |
| `styles.css` | All styling and design tokens (see `:root`) |
| `script.js` | Mobile nav toggle + footer year |

## Local preview

It's a static site — just open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Adding projects

The Projects section (`#projects`) is intentionally blank. To add one,
replace the `.projects__placeholder` in `index.html` with cards like:

```html
<article class="project-card">
  <h3>Project name</h3>
  <p>Short description.</p>
  <a href="#">View →</a>
</article>
```

The `.project-card` style is already defined in `styles.css`.
