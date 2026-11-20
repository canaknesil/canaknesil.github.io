# canaknesil.github.io

Personal website, built with [Jekyll](https://jekyllrb.com/).

## Setup (once)

```bash
bundle config set --local path vendor/bundle
bundle install
```

## Preview

```bash
bundle exec jekyll serve --livereload
```

Open http://localhost:4000. Restart the server after changing `_config.yml`.

## Build

```bash
bundle exec jekyll build
```

The site is generated in `_site/`.

## Publish

Push to `master`. GitHub Pages builds and deploys the site automatically.
