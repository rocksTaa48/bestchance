source "https://rubygems.org"

gem "rails", "~> 7.2.3"
gem "sprockets-rails"
gem "pg", "~> 1.1"
gem "puma", ">= 5.0"
gem "jsbundling-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "cssbundling-rails"
gem "jbuilder"
gem "image_processing", "~> 1.14"
gem "bcrypt", "~> 3.1.7"
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "bootsnap", require: false
gem "roo", "~> 2.7"
gem "csv", "~> 3.0"
gem "cancancan", "~> 3.5"
gem "combine_pdf", "~> 1.0"
gem "prawn", "~> 2.1"
gem "pagy", "~> 9.1"
gem "httparty", "~> 0.23"
gem "ox", "~> 2.14.22"
gem "aasm", "~> 5.5.0"
gem "after_commit_everywhere", "~> 1.6"
gem "redis", "~> 5.3"
gem "rack-cors", "~> 2.0"
gem "sidekiq", "~> 7.1.2"
gem "rack-attack", "~> 6.7"
gem "mini_magick", "~> 5.2.0"
group :development, :test do
  gem "dotenv-rails", "~> 3.1"
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
  gem "brakeman", require: false
  gem "rubocop-rails-omakase", require: false
  gem "rspec-rails", "~> 7.1"
  gem "factory_bot_rails", "~> 6.5"
  gem "faker", "~> 3.4"
end

group :development do
  gem "web-console"
  gem "letter_opener"
  gem "letter_opener_web", "~> 3.0"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end
