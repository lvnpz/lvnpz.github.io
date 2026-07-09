source "https://rubygems.org"

# GitHub Pages servers build with Ruby 3.3.x; the github-pages gem does not
# support Ruby >= 4.0. Locally use Homebrew's keg-only ruby@3.3:
#   PATH="/opt/homebrew/opt/ruby@3.3/bin:$PATH" bundle install
ruby "~> 3.3.0"

# GitHub Pages builds with the github-pages gem (bundles Jekyll 3.10 and
# minima 2.5.1). Keep this in sync with https://pages.github.com/versions/
gem "github-pages", "~> 232", group: :jekyll_plugins

gem "minima", "~> 2.5"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Required for `jekyll serve` on Ruby >= 3.0
gem "webrick", "~> 1.7"

# Windows and JRuby do not include zoneinfo files
platforms :windows, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end
