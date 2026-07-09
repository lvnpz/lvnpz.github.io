# lvnpz.github.io

Personal website of Yang (Kody) Deng: [https://lvnpz.github.io](https://lvnpz.github.io)

Built with [Jekyll](https://jekyllrb.com/) on the [minima](https://github.com/jekyll/minima)
theme (2.5.x, as bundled by [GitHub Pages](https://pages.github.com/versions/)),
customized via `assets/main.scss` and `_includes/` overrides.

## Local development

GitHub Pages builds the site server-side with its own toolchain
(Ruby 3.3.x + the `github-pages` gem), so nothing below is needed to deploy —
just push to `main`.

For local preview, the `github-pages` gem requires **Ruby 3.3** (it does not
support Ruby 4.x yet). With Homebrew:

```sh
brew install ruby@3.3   # keg-only; does not change your default ruby
export PATH="/opt/homebrew/opt/ruby@3.3/bin:$PATH"

bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.
