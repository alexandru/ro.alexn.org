source 'http://rubygems.org'

gem "jekyll", "~> 4.2"
gem "support-for"
gem 'nokogiri'
gem 'classifier-reborn'
gem 'gsl'
gem "mini_magick"
gem "image_optim"
gem "fastimage"

group :jekyll_plugins do
  gem "jekyll-paginate-v2"
  gem 'jekyll-relative-links'
  gem 'jekyll-sitemap'
  gem 'jekyll-redirect-from'
  gem "jekyll-last-modified-at"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?
