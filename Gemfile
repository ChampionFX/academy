source "https://rubygems.org"
ruby RUBY_VERSION

gem "jekyll", "3.5.1"

group :jekyll_plugins do
   gem "jekyll-feed", "~> 0.6"
   gem 'wdm', '>= 0.1.0' if Gem.win_platform?
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

