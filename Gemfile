source "http://rubygems.org"

spree_version = 'master'
gem 'spree', github: 'spree/spree', branch: spree_version
gem 'sass-rails'

# Spree Internationalization https://github.com/spree/spree_i18n
gem 'spree_i18n', github: 'spree/spree_i18n', branch: 'master'
gem 'globalize', github: 'globalize/globalize', branch: 'master'

group :test, :development do
  gem 'rspec-rails'
  gem 'sqlite3'
  gem 'factory_girl'
  gem 'pry'
  gem 'database_cleaner'
  gem 'spork'
  gem 'poltergeist'
  gem 'selenium-webdriver'
  gem 'capybara-webkit'
  gem 'capybara'
  gem 'vcr'
end

group :test do
  gem 'ffaker'
end


gemspec
