# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll", "~> 3.8.5"

# Theme
#gem "minima", "~> 2.0"

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
  gem 'jekyll-sitemap'
  gem 'jekyll-seo-tag'
  gem 'jekyll-include-with-frontmatter', '~> 0.1.1'
  gem 'jekyll-picture-tag', git: 'https://github.com/robwierzbowski/jekyll-picture-tag/'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?

gem "kramdown"
gem "mime-types"

group :test do
  gem 'rake'
  gem 'rspec'
  gem 'rubocop'
end
