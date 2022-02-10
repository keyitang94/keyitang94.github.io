source "https://rubygems.org"

gem "jekyll", "~> 4.2.0"

gem: jekyll-sitemap

bundle init
bundle add jekyll
bundle exec jekyll new --force --skip-bundle .
bundle install
bundle exec jekyll serve


group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end
