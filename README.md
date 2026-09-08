# Amazonweb

A static storefront inspired by Amazon, built with HTML and CSS. The project explores a retail homepage layout: navigation, a search field, promotional artwork, a category grid, and a footer with multiple columns.

## Run locally

Open [index.html](index.html) in a browser, or serve the repository with Python 3:

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

Then open `http://127.0.0.1:8000/`. There are no dependencies to install or build commands to run. Font Awesome loads from a CDN and requires an internet connection.

## Source map

| File | Purpose |
| --- | --- |
| [index.html](index.html) | Storefront markup, navigation, categories, and footer |
| [style.css](style.css) | Layout, hover states, colors, and background images |
| Root PNG files | Logo, hero artwork, and category imagery |

To change the content, edit `index.html`. To change the layout or swap imagery, edit `style.css` and the referenced PNG files.

## Scope and credits

This is a visual practice project. Search, account access, cart, checkout, and order management are not implemented; footer labels are placeholders. The layout uses fixed dimensions in several places and has no dedicated mobile breakpoints.

The visual reference and branding are Amazon's. Font Awesome supplies the icons, with the embedded SVG attribution retained in the source. This repository does not establish an affiliation with Amazon or grant rights to branding and imagery belonging to others.
