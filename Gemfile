# frozen_string_literal: true
source "https://rubygems.org"

#don't upgrade
gem "rails", "5.1.5"

ruby "2.4.3"

gem "aruba", ">= 0.14.13"
gem "bcrypt"
gem "coffee-rails", ">= 5.0.0"
gem "execjs"
gem "foreman", ">= 0.86.0"
gem "jquery-fileupload-rails", ">= 1.0.0"
gem "jquery-rails", ">= 4.3.2"
gem "minitest"
gem "powder" # Pow related gem
gem "pry-rails" # not in dev group in case running via prod/staging @ a training
gem "rails-perftest"
gem "rake"
gem "responders" , ">= 2.4.1" #For Rails 4.2
gem "ruby-prof"
gem "sass-rails", ">= 5.0.8"
gem "simplecov", require: false, group: :test
gem "sqlite3"
gem "therubyracer"
gem "turbolinks"
gem "uglifier"
gem "unicorn"

# Add SMTP server support using MailCatcher
# NOTE: https://github.com/sj26/mailcatcher#bundler
# gem 'mailcatcher'

group :development, :mysql do
  gem "better_errors"
  gem "binding_of_caller"
  gem "brakeman"
  gem "bundler-audit", ">= 0.7.0"
  gem "guard-brakeman", ">= 0.8.4"
  gem "guard-livereload"
  gem "guard-rspec"
  gem "guard-shell", ">= 0.7.2"
  gem "pry"
  gem "rack-livereload"
  gem "rb-fsevent"
  gem "rubocop-github"
  gem "travis-lint"
end

group :development, :test, :mysql do
  gem "capybara", ">= 2.18.0"
  gem "database_cleaner"
  gem "launchy"
  gem "poltergeist", ">= 1.18.0"
  gem "rspec-rails", ">= 3.8.0"
  gem "test-unit"
end

group :mysql do
  gem "mysql2"
end
