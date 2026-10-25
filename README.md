# Cretan Line — website

Static one-page site for Cretan Line, a Cretan road-transport company
(goods, fuel, and food, including refrigerated transport).

## Files

- `index.html` — all page content
- `style.css` — all styling
- `script.js` — mobile menu, footer year, demo contact form

No build step, no dependencies — just three files.

## Publish with GitHub Pages

1. Create a new repository on GitHub (e.g. `cretan-line`).
2. Upload `index.html`, `style.css`, and `script.js` to the root of the repo
   (drag-and-drop on the GitHub web UI works fine, or `git push`).
3. Go to **Settings → Pages**.
4. Under **Branch**, choose `main` and `/ (root)`, then **Save**.
5. GitHub gives you a URL like `https://yourusername.github.io/cretan-line/`
   within a minute or two.

## Customizing

- **Contact details** (phone, email, address) are placeholders near the
  bottom of `index.html`, in the `#epikoinonia` section — update them first.
- **Colors and fonts** are defined once at the top of `style.css` under
  `:root` — change `--navy`, `--ochre`, `--olive`, etc. to adjust the
  whole palette.
- **The contact form** doesn't send anywhere yet — it just shows a
  confirmation message. Hook it up to a form service (e.g. Formspree) or
  your own backend by editing `script.js`.
- **Partners list** (Νιτσιάκος, AVIN, Λαχανικά Ιεράπετρας) is a plain list
  in the `#pelates` section — add or remove `<li class="partner-row">`
  blocks the same way.
