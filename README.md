# thexyzzyone.github.io

Source for my GitHub Pages site, built with [Jekyll](https://jekyllrb.com/) via the `github-pages` gem.

## Prerequisites

- [Ruby](https://www.ruby-lang.org/) (see [GitHub Pages' supported version](https://pages.github.com/versions/))
- [Bundler](https://bundler.io/): `gem install bundler`

## Setup

Install dependencies:

```sh
bundle install
```

## Running locally

Start the development server:

```sh
bundle exec jekyll serve
```

Then open [http://localhost:4000](http://localhost:4000) in your browser.

The server watches for file changes and rebuilds automatically. Note that `_config.yml` is **not** watched — restart the server after editing it.

### Useful variants

- `bundle exec jekyll serve --livereload` — auto-refresh the browser on changes
- `bundle exec jekyll serve --drafts` — include posts in `_drafts`
- `bundle exec jekyll build` — build the static site into `_site` without serving it

## License

This project is licensed under the [MIT License](LICENSE).
