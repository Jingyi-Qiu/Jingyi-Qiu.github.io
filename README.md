# jingyiqiu.com

Personal academic website of Jingyi Qiu, served at https://www.jingyiqiu.com via GitHub Pages.
Look and layout follow the al-folio (v0.1) theme as used on zongyi-li.github.io.

GitHub Pages builds this repository with its built-in Jekyll on every push to `main`; no Actions or plugins are needed.

Where to edit:

- Bio, title line, photo: `_pages/about.md` (photo: `assets/img/prof_pic.jpg`)
- News: add a file to `_news/` (front matter `date:` for ordering, `display_date:` for the label)
- Publications: `_data/publications.yml`
- CV: replace `assets/pdf/Jingyi_Qiu_CV.pdf`; summary sections in `_pages/cv.md`
- Teaching: `_pages/teaching.md`
- Name, email, social links, nav: `_config.yml`
- Styling: `assets/css/custom.css` (base theme in `assets/css/main.css`)

Local preview (optional): `bundle install && bundle exec jekyll serve`, then open http://localhost:4000.
