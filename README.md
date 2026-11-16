# cheng-shuyao.github.io

Personal academic homepage of **Cheng, Shuyao (承书尧)**, Associate Professor at the
Institute of Computing Technology, Chinese Academy of Sciences.

A single-page site built with Jekyll on top of the [Academic Pages](https://github.com/academicpages/academicpages.github.io)
theme, deployed to GitHub Pages through GitHub Actions.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://127.0.0.1:4000/>. Note that `assets/js/main.min.js` is generated
at build time (`npm run build:js`, requires Node.js) and is not committed; the CI
workflow regenerates it on deploy.

## Deployment

Push to the `main` branch. `.github/workflows/jekyll.yml` builds the site and
publishes it to <https://cheng-shuyao.github.io/>.
