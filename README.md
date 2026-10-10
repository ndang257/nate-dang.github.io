# Quang Ngoc Dang — Portfolio

A lightweight, dark editorial portfolio built with Jekyll and GitHub Pages. The site is content-first: pages are Markdown files, and shared layouts and CSS handle the presentation. No JavaScript framework, database, or external build tooling is needed.

## Edit the content

- **About and homepage sections:** edit `index.md` and `_layouts/home.html`.
- **Projects:** edit or add Markdown files in `_projects/`. Each file becomes a static project page and appears in the project archive and homepage cards. Set `title`, `summary`, `category`, `visual`, and `order` in its front matter.
- **Posts:** edit or add dated Markdown files in `_posts/`, following the `YYYY-MM-DD-short-title.md` filename format. Set `title`, `excerpt`, `category`, and `visual` in the front matter.
- **Contact links and deployment path:** update `_config.yml` and the profile links in `_layouts/home.html`.
- **Look and feel:** edit `assets/css/style.css`. The project and post card illustrations are CSS placeholders; replace them with images later if desired.

The hobby sentence on the homepage is intentionally marked for personalization. The project and post entries are clearly labeled placeholders and can be replaced or removed.

## Publish with GitHub Pages

In the repository’s **Settings → Pages**, choose **Deploy from a branch**, select `main` and the root (`/`) folder, then save. GitHub Pages builds the Jekyll site and publishes it at `https://ndang257.github.io/`. The `_config.yml` uses that root URL with an empty `baseurl`; update `url` and `baseurl` there if the published URL changes.
