source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "rails",        "5.0.1"
gem "sass-rails",   "5.0.6"
gem "uglifier", ">= 1.3.0"
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem "therubyracer", platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem "coffee-rails", "~> 4.2"
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem "turbolinks", "~> 5"
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem "jbuilder", "~> 2.5"
gem "puma", "~> 3.7"
gem "devise"
gem "redis", "~> 3.2"
gem "bootstrap", "~> 4.0.0.alpha3"


group :development, :test do
  gem "sqlite3", "1.3.12"
  gem "byebug",  "9.0.0", platform: :mri
end

group :development do
  gem "web-console",           "3.1.1"
  gem "listen",                "3.0.8"
  gem "spring",                "1.7.2"
  gem "spring-watcher-listen", "2.0.0"
end

group :production do
  gem "pg", "0.18.4"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
