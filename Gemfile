source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.6.4"

gem "rails", "~> 6.0.3", ">= 6.0.3.2"
gem "puma", "~> 3.11"
gem "sass-rails", ">= 6"
gem "webpacker", "~> 4.0"
gem "turbolinks", "~> 5"
gem "jbuilder", "~> 2.7"

gem "image_processing", "~>1.2"
gem 'carrierwave'
gem 'rmagick'
gem 'fog-aws'

gem "bootsnap", ">= 1.4.2", require: false
gem 'gmaps4rails', '~> 2.1', '>= 2.1.2'

gem "bcrypt"
gem "rails-i18n"
gem "date_validator"
gem "valid_email2"
gem "nokogiri"
gem "aws-sdk-s3", require: false

group :development, :test do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem "web-console", ">= 3.3.0"
  gem "listen", "~> 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "pg", ">= 0.18", "< 2.0"
end

group :test do
  gem "capybara", ">= 2.15"
  gem "selenium-webdriver"
  gem "webdrivers"
  gem "rspec-rails"
  gem "factory_bot_rails"
end
gem "kaminari"

group :production do
  gem "pg", ">= 0.18", "< 2.0"
  gem 'fog-aws'
end
