source "https://rubygems.org"

# Run locally with:
#
#     bundle install
#     bundle exec jekyll serve
#
gem "jekyll", "~> 4.4"

# Theme
gem "minima", "~> 2.5"

# Plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.17"
end

# Needed by `jekyll serve` on Ruby 3.0+
gem "webrick", "~> 1.8"

# Windows and JRuby do not include zoneinfo files
platforms :windows, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end
