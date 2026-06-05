# Odin Recipes

My first project from [The Odin Project](https://www.theodinproject.com/) — a simple recipe website built with **HTML only**. It brings together everything I learned in the Foundations HTML module into one small, multi-page site.

## About

The Odin Project's "Recipes" assignment asks you to build a basic website that links to several recipe pages. Each page includes a description, ingredients list, and step-by-step instructions. No CSS or JavaScript — just semantic, well-structured HTML.

## Recipes

|             Recipe              |                        Page                            |
|---------------------------------|--------------------------------------------------------|
| Lasagna                         | [`recipes/lasagna.html`](recipes/lasagna.html)         |
| Chicken Enchiladas              | [`recipes/chicken.html`](recipes/chicken.html)         |
| Lemon Texas Sheet Cake          | [`recipes/cake.html`](recipes/cake.html)               |
| Chopped Chimichurri Steak Salad | [`recipes/chimichurri.html`](recipes/chimichurri.html) |

## Project structure

```
odin-recipes/
├── index.html          # Homepage with links to all recipes
└── recipes/
    ├── lasagna.html
    ├── chicken.html
    ├── cake.html
    └── chimichurri.html
```

## HTML concepts practiced

- **Document structure** — `<!DOCTYPE html>`, `<html>`, `<head>`, and `<body>`
- **Metadata** — `charset`, `viewport`, and `<title>`
- **Headings & paragraphs** — `<h1>`, `<h2>`, and `<p>` for clear content hierarchy
- **Lists** — unordered lists (`<ul>`) for ingredients, ordered lists (`<ol>`) for steps
- **Links** — `<a href="...">` to navigate between the homepage and recipe pages
- **Images** — `<img>` with `src`, `alt`, `width`, and `height`
- **Multi-page layout** — relative paths (`../index.html`) to connect pages across folders

## License

This project is licensed under the [Mozilla Public License 2.0](LICENSE).
