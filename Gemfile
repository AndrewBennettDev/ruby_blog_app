source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.2"

gem "rails", "~> 7.0.8"
gem "sprockets-rails"
gem "sqlite3", "~> 1.4"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem 'bulma-rails', '~> 0.9.4'
gem 'simple_form', '~> 5.2'
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]

end

group :development do
  gem "web-console"
  gem 'better_errors', '~> 2.10', '>= 2.10.1'
  gem 'guard', '~> 2.18', '>= 2.18.1'
  gem 'guard-livereload', '~> 2.5', require: false

end

group :test do
  gem "capybara"
  gem "selenium-webdriver"

end
