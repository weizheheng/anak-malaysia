source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.0.1"

gem "rails", "~> 6.1.3", ">= 6.1.3.1"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem "sass-rails", ">= 6"
gem "webpacker", "6.0.0.beta.7"
gem "jbuilder", "~> 2.7"
gem "redis", "~> 4.0"
gem "bootsnap", ">= 1.4.4", require: false
gem "inline_svg"

group :development, :test do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
  gem "rubocop-shopify", require: false
end

group :development do
  gem "web-console", ">= 4.1.0"
  gem "rack-mini-profiler", "~> 2.0"
  gem "listen", "~> 3.3"
  gem "spring"
  gem "guard", "~> 2.16", ">= 2.16.2"
  gem "guard-livereload", "~> 2.5", require: false
  gem "rack-livereload", "~> 0.3.17"
end

group :test do
  gem "capybara", ">= 3.26"
  gem "rexml"
  gem "selenium-webdriver"
  gem "webdrivers"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem "hotwire-rails", "~> 0.1.3"
