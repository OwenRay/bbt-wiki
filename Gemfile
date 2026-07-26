source "https://rubygems.org"

# Jekyll 4.3.x (4.4.x also satisfies ~> 4.3) — used instead of the
# pinned github-pages gem so we can load jekyll-polyglot in the
# GitHub Actions build.
gem "jekyll", "~> 4.3"

# webrick is required to serve Jekyll locally on Ruby 3+ (no longer in stdlib).
gem "webrick", "~> 1.8"

group :jekyll_plugins do
  # Enables the `remote_theme:` setting (just-the-docs is loaded from GitHub).
  gem "jekyll-remote-theme", "~> 0.4"
  gem "jekyll-include-cache", "~> 0.2"
  gem "jekyll-seo-tag", "~> 2.8"
  # Multilanguage support (i18n). Activated by the `languages:` block in
  # _config.yml — installed here so it is ready when that config is added.
  gem "jekyll-polyglot", "~> 1.8"
end
