# frozen_string_literal: true

source "https://rubygems.org"

gem "rails", "~> 8.0.1"

gem "bootsnap", require: false
gem "devise"
gem "importmap-rails"
gem "jbuilder"
gem "pg"
gem "propshaft"
gem "puma", ">= 5.0"
gem "stimulus-rails"
gem "thruster", require: false
gem "turbo-rails"
gem "tzinfo-data", platforms: %i[windows jruby]

# Use the database-backed adapters for Rails.cache, Active Job, and Action Cable
gem "solid_cable"
gem "solid_cache"
gem "solid_queue"

# Deploy this application anywhere as a Docker container [https://kamal-deploy.org]
gem "kamal", require: false

group :development, :test do
  gem "debug", platforms: %i[mri windows], require: "debug/prelude"

  # Static analysis for security vulnerabilities [https://brakemanscanner.org/]
  gem "brakeman", require: false
  gem "bullet"
  gem "reek"
  gem "rubocop"
  gem "rubocop-md", require: false
  gem "rubocop-performance", require: false
  gem "rubocop-rails", require: false
  gem "rubocop-rspec", require: false
  gem "rubocop-thread_safety", require: false
end

group :development do
  gem "overcommit"
  gem "web-console"
end
