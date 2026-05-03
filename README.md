# Hugo Lab Website Starter

This is a minimal Hugo starter for my research group website with pages for:

- Home
- News
- Research
- People
- Publications
- Contact

## License

This repository contains both source code and website content.

- Source code is licensed under the MIT License (see LICENSE file)
- Website content (text, images, figures) is licensed under:
  Creative Commons Attribution-NonCommercial 4.0 (CC BY-NC 4.0),
  unless otherwise stated

Third-party materials may be subject to separate copyrights.


## Run locally

```bash
hugo server
```

Then open the local address Hugo prints in the terminal.

## Build static files

```bash
hugo
```

The generated site will appear in `public/`.

## Customize

- Edit `config.yaml` for lab name, tagline, affiliation, email, and menu.
- Edit `data/people.yaml` for group members.
- Edit `news/` markdown files for each news.
- Edit `data/publications.yaml` for selected publications.
- Edit `content/` markdown files for each page.
- Edit `assets/css/style.css` to change appearance.

## Suggested next improvements

- Add a `positions/` page
- Import publications automatically from BibTeX or CSL JSON
- Add profile photos under `static/images/`
- Deploy with GitHub Pages or Netlify

