# frozen_string_literal: true

source "http://rubygems.org"

ruby "2.6.2"

gem "rails", "~> 5.2"
gem "doorkeeper", "~> 5.0"
gem "devise", "~> 4.6"

gem "faker"
gem "jquery-rails"

gem "coderay"
gem "redcarpet"

gem "pg", "~> 1.1", group: :production
gem "sqlite3",      group: [:development, :test]

gem "puma"
gem "rack-timeout"

group :development do
  gem "listen"
  gem "rubocop-performance"
  gem "rubocop-rails_config"
end

group :test do
  gem "rspec-rails"
end
