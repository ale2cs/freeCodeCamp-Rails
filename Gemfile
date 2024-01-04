source "https://rubygems.org"

ruby "3.2.2"
gem "rails", "~> 7.1.2"
gem "sprockets-rails"
gem "puma", ">= 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "bootsnap", require: false
gem 'devise', '~> 4.9', '>= 4.9.3'
gem 'bcrypt', '~> 3.1', '>= 3.1.20'
gem 'nokogiri', '~> 1.16'

group :development, :test do
  gem "debug", platforms: %i[ mri windows ]
  gem "sqlite3", "~> 1.4"
end

group :production do
  gem 'mysql2', '~> 0.5.5' 
end

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end
