# 🥑 Organify

A multi-page front-end for **Organify**, an organic-food store ("Nature's Choice for Healthy Living"), built with **plain HTML and CSS**: no framework and no build step.

## Pages

| File | What it shows |
|---|---|
| `Organify_files/index.html` | Home: wholesaler highlights (fresh & healthy, free delivery, best quality, secure payments), popular organic products, "Always Fresh" product showcase, customer praise, latest blog posts, newsletter sign-up, footer |
| `Organify_files/shop.html` | Shop page |
| `Organify_files/styles.css` | Shared stylesheet for both pages |

The rest of `Organify_files/` holds the product, banner and logo images.

## Run it

No install needed:

```bash
git clone https://github.com/Ryzuuuu/Organify.git
cd Organify/Organify_files
# open index.html in your browser, or:
python -m http.server 8000   # then visit http://localhost:8000/index.html
```

## Notes

Front-end only: the cart, newsletter form and checkout are not wired to a backend.
