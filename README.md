# AMANOTOSHI  
Modular static personal art website with separate pages for intro, gallery, Blood story series, blog, and links.

## Pages

- `index.html`: landing / self introduction
- `gallery.html`: gallery with category tabs
- `blog.html`: short articles
- `links.html`: curated external links

## Content-first architecture

Update content without touching rendering logic:

- `content/site.json`: site name, intro text, footer text
- `content/gallery.json`: categories and artworks
- `content/blog.json`: blog entries
- `content/links.json`: links list


# Example Item Title

![Optional hero image](./data/header.png)

Main paragraph text.

## Section Heading

- Bullet one
- Bullet two

> Optional quote or highlight
```
## Run locally

1. Use any static server. Example:
   - `python3 -m http.server 4173`
2. Open `http://localhost:4173`

## Extend

- Add a page file and corresponding renderer in `assets/js/pages/`
- Register page renderer in `assets/js/main.js`
- Keep shared layout in `assets/js/components/layout.js`
