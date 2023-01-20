source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"
gem "rails", "~> 7.0.4", ">= 7.0.4.1"
gem "sprockets-rails"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false

gem "solidus_core", ">= 0"
gem "solidus_backend", ">= 0"
gem "solidus_api", ">= 0"
gem "solidus_sample", ">= 0"
gem "canonical-rails"
gem "solidus_support"
gem "truncate_html"
gem "view_component", "~> 2.46"
gem 'solidus_stripe', '< 5'

# gem "sassc-rails"
# gem "redis", "~> 4.0"
# gem "kredis"
# gem "bcrypt", "~> 3.1.7"
# gem "image_processing", "~> 1.2"

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  gem "web-console"

  # gem "rack-mini-profiler"
  # gem "spring"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end

group :development, :test do
  gem "rspec-rails"
  gem "apparition", "~> 0.6.0", github: "twalpole/apparition"
  gem "rails-controller-testing", "~> 1.0.5"
  gem "rspec-activemodel-mocks", "~> 1.1.0"
  gem "capybara-screenshot", "~> 1.0"
  gem "database_cleaner", "~> 1.7"
  gem "factory_bot", ">= 4.8"
  gem "factory_bot_rails"
  gem "ffaker", "~> 2.13"
  gem "rubocop", "~> 1.0"
  gem "rubocop-performance", "~> 1.5"
  gem "rubocop-rails", "~> 2.3"
  gem "rubocop-rspec", "~> 2.0"
end

# FIXME: Please remove this line if `solidus_auth_devise` appears anywhere else in the gemfile
#        or replace it with a simple `gem 'solidus_auth_devise'` otherwise.
gem 'solidus_auth_devise' unless File.read(__FILE__).lines[__LINE__..-1].grep(/solidus_auth_devise/).any?

